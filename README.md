Family-Tracker

Description

Family Tracker is a web application that helps users track and manage their family members' locations and activities in real-time. The project is built using EJS, CSS, JavaScript, PostgreSQL, Node.js, and Express.

Features

Add, update, and remove family members

Track family members' locations

View location history

Responsive UI with EJS templates

Secure backend with Express and PostgreSQL

Technologies Used

Frontend: EJS, CSS, JavaScript

Backend: Node.js, Express.js

Database: PostgreSQL

Installation

Clone the repository:

git clone https://github.com/haseebtahir-dev/family-tracker.git
cd family-tracker

Install dependencies:

npm install

Set up PostgreSQL database and update the connection details in .env file:

DB_USER=your_username
DB_PASSWORD=your_password
DB_NAME=family_tracker
DB_HOST=localhost
DB_PORT=5432

Run database migrations (if applicable):

npm run migrate

Start the application:

npm start

Open the app in your browser at http://localhost:3000

API Endpoints

GET / - Home Page

GET /login - Login Page

POST /login - Authenticate User

GET /signup - Signup Page

POST /signup - Register New User

GET /dashboard - View Family Members

POST /add-member - Add a Family Member

DELETE /delete-member/:id - Remove a Family Member

Contributing

Feel free to submit issues and pull requests to improve the project.

License

This project is open-source and available under the MIT License.

Contact

Developed by Haseeb TahirGitHub: haseebtahir-dev
