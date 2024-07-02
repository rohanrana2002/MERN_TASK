
E-Commerce Website
Description
This is an e-commerce website built using React for the frontend and Node.js/Express for the backend. It utilizes MongoDB for the database and requires API keys for secure operations.

Frontend Setup
Install Dependencies

bash
Copy code
npm install
Environment Variables

Create a .env file in the root directory of the frontend.
Add the following environment variable:
bash
Copy code
REACT_APP_API_BASE_URL=http://localhost:5000  # Replace with your backend URL
Run the Application

bash
Copy code
npm start
This command starts the frontend server.

Backend Setup
Install Dependencies

bash
Copy code
cd backend
npm install
Environment Variables

Create a .env file in the backend directory.
Add the following environment variables:
makefile
Copy code
MONGODB_URI=<your_mongodb_uri>
SECRET_KEY=<your_secret_key>
TOKEN_KEY=<your_token_key>
Run the Backend Server

bash
Copy code
npm run dev
This command starts the backend server using nodemon for automatic reload on changes.

Testing

Describe any testing procedures, if applicable.
Technologies Used
React
Node.js
Express
MongoDB
Cloudinary (if applicable)
