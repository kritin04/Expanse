
MERN Stack Expense Management System
A full-stack web application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack that allows users to track their income and expenses, visualize their spending habits, and manage their finances effectively.

✨ Live Demo
(Note: Replace with your actual deployment link after hosting the application.)

Features
Secure User Authentication: Users can sign up and log in securely, with JWT-based authentication protecting user-specific data.

Full CRUD Functionality: Create, Read, Update, and Delete income and expense transactions.

Interactive Dashboard: A dynamic dashboard provides a quick overview of total income vs. expenses.

Data Visualization: See a breakdown of spending by category with responsive pie charts and progress bars.

Advanced Filtering: Filter transactions by date range (e.g., last 7 days, custom range), type (income/expense), and category.

Responsive Design: A clean and modern UI built with Ant Design that works seamlessly on desktop and mobile devices.

Login Page	Dashboard & Analytics	Transaction List

Export to Sheets
Technologies Used
Frontend	Backend	Database
React.js	Node.js	MongoDB
Ant Design	Express.js	Mongoose
Axios	JWT	
React Router	Morgan	
Moment.js		

Export to Sheets
Setup and Installation
Follow these steps to set up the project locally on your machine.

Prerequisites:

Node.js (v14 or later)

NPM (Node Package Manager)

MongoDB (local instance or a cloud instance from MongoDB Atlas)

1. Clone the Repository:

Bash

git clone https://github.com/your-username/expense-management-system.git
cd expense-management-system
2. Install Backend Dependencies:
Navigate to the server directory and install the required npm packages.

Bash

cd server
npm install
3. Install Frontend Dependencies:
Navigate to the client directory and install the required npm packages.

Bash

cd ../client
npm install
4. Set Up Environment Variables:
Create a .env file in the server directory and add the following configuration. Replace the placeholder with your actual MongoDB connection string.

Code snippet

# .env file in the /server directory

# Port for the backend server
PORT=8080

# Your MongoDB Connection URI
MONGO_URL=mongodb+srv://<username>:<password>@your-cluster.mongodb.net/expense-app
5. Run the Application:
You can run both the frontend and backend servers concurrently from the root directory using the concurrently package.

From the root project directory, run:

Bash

npm run dev
This will start:

The React development server on http://localhost:3000

The Node.js backend server on http://localhost:8080 (or the port you specified in .env)
