# Employee Management System

This is a simple Employee Management System web application that allows users to sign up, log in, and manage employee details. It features a landing page that redirects users to either login or signup pages, stores user details in a MongoDB database, and redirects users to a home page upon successful login.

## Features and Technologies Used

- User registration with username and password.
- Login authentication.
- Secure password validation (minimum of 6 characters).
- Responsive design using Bootstrap.
- Backend built with Express.js and MongoDB.
- MongoDB is used for storing user data.
- Basic error handling and validation.
- **Front End**: HTML5, CSS3, Bootstrap 5
- **Back End**: Node.js, Express.js
- **Database**: MongoDB
- **Libraries**: Body-Parser, Cors
- **Version Control**: Git
- **Deployment**: Localhost

## Setup Instructions

To get a local copy of the project up and running, follow these steps:

### Prerequisites

1. Make sure you have [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) installed on your machine.
2. Install MongoDB locally or use MongoDB Atlas (cloud database service).

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/natashagargn/employee_management_system.git
2. Navigate to the project directory:

    ```bash
    cd employee-management-system

3. Install the required dependencies:
    ```bash
    npm install

4. Update the MongoDB connection string in App.js:
    ```bash
    const dbconnect = 'your_mongodb_connection_string';

5. Start the application:
    ```bash
    node App.js

6. To view the application, open index.html by pasting the file path directly into our browser. It should look something like this:
file:///your_path_to_project/employee-management-system/index.html
