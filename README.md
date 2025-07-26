Project Title: WanderLust 🏨
A full-stack clone of the Airbnb web application. This project is currently a work in progress.

✨ Description
WanderLust is a web application inspired by Airbnb. It allows users to browse, view, and list properties for rent. The goal is to replicate the core functionalities of Airbnb, providing a seamless experience for both property owners and renters.

📸 Screenshots
<img width="1918" height="867" alt="image" src="https://github.com/user-attachments/assets/5a9cc57d-9e22-4327-9791-c9bc7027c1fb" />
<img width="1919" height="870" alt="image" src="https://github.com/user-attachments/assets/ba68db3b-692e-48af-90d7-c32cb0f5a217" />

Example:
A screenshot of the homepage 

WanderLust (Airbnb Clone) 🏨
A full-stack clone of the Airbnb web application, created as a major project for the Apna College DELTA 2.0 course. This project is currently a work in progress.

✨ Features
User Authentication (Sign Up, Login, Logout) using Passport.js.

Browse and view property listings with details like price, location, and description.

Full Create, Read, Update, and Delete (CRUD) operations for listings.

Image uploads hosted on Cloudinary.

Interactive maps to show property locations using the Mapbox API.

Planned Features
User reviews and ratings for properties.

Booking and reservation system.

Enhanced user profiles.

🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript, EJS

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

APIs & Libraries: Mapbox API, Passport.js, Cloudinary, connect-flash, express-session, etc.

⚙️ Installation & Setup
Follow these steps to set up the project locally on your machine.

Prerequisites
Make sure you have the following installed:

Node.js: Download & Install Node.js

MongoDB: Download & Install MongoDB

Get Started
Clone the repository:
Open your terminal and run the following command to clone the project.

Bash

git clone https://github.com/Aaditya0807/MAJORPROJECT2.git
cd MAJORPROJECT2
Install dependencies:
Install all the necessary npm packages defined in the package.json file.

Bash

npm install
Set up Environment Variables:
Create a new file named .env in the root of your project. This file will store sensitive information and must not be committed to Git. Add the following variables:

MONGO_URL="your_mongodb_connection_string"
MAPBOX_TOKEN="your_mapbox_api_key"
CLOUDINARY_CLOUD_NAME="your_cloudinary_cloud_name"
CLOUDINARY_KEY="your_cloudinary_api_key"
CLOUDINARY_SECRET="your_cloudinary_secret"
SECRET="somegoodsecret"
Start the MongoDB server:
Before running the application, open a new, separate terminal window and start the MongoDB service using the command:

Bash

mongod
Leave this terminal running in the background to keep the database connection alive.

Start the application server:
Go back to your original terminal (in the project directory) and start the application server.

Bash

node app.js
Your server should now be running! Open your browser and go to http://localhost:8080. 🎉

🙏 Acknowledgements
This project was built as part of my learning journey through the Apna College DELTA 2.0 batch. The core concepts and structure are based on the full-stack web development curriculum taught in the course. A huge thank you to the instructors for their guidance.

📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.

🧑‍💻 Contact
Aaditya Sharma - aadityasharma08072004@gmail.com

Project Link: https://github.com/Aaditya0807/MAJORPROJECT2
