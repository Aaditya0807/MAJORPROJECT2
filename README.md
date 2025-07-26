# Project Title: WanderLust 🏨
A full-stack clone of the Airbnb web application. This project is currently a work in progress.

## ✨ Description
WanderLust is a web application inspired by Airbnb. It allows users to browse, view, and list properties for rent. The goal is to replicate the core functionalities of Airbnb, providing a seamless experience for both property owners and renters.

📸 Screenshots
<img width="1918" height="867" alt="image" src="https://github.com/user-attachments/assets/5a9cc57d-9e22-4327-9791-c9bc7027c1fb" />
<img width="1919" height="870" alt="image" src="https://github.com/user-attachments/assets/ba68db3b-692e-48af-90d7-c32cb0f5a217" />

Example:
A screenshot of the homepage 

## Key Features

* **Full CRUD Functionality**: Users can Create, Read, Update, and Delete property listings.
* **User Authentication**: Secure user registration and login system implemented with Passport.js.
* **Image Uploads**: Seamless image hosting and delivery via the Cloudinary API.
* **Interactive Maps**: Dynamic maps from Mapbox show the precise location of each property.
* **Reviews and Ratings**: Users can post reviews and ratings for properties they've visited.

## Tech Stack 🛠️

* **Frontend**: EJS, HTML, CSS, JavaScript, Bootstrap
* **Backend**: Node.js, Express.js
* **Database**: MongoDB, Mongoose
* **APIs & Libraries**: Mapbox, Cloudinary, Passport.js, `connect-flash`, `express-session`

## Getting Started

Follow these instructions to get a local copy of the project up and running for development and testing.

### Prerequisites

Make sure you have the following installed on your system:
* [Node.js](https://nodejs.org/) (which includes npm)
* [MongoDB](https://www.mongodb.com/try/download/community)
* [Git](https://git-scm.com/)

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/Aaditya0807/MAJORPROJECT2.git](https://github.com/Aaditya0807/MAJORPROJECT2.git)
    cd MAJORPROJECT2
    ```

2.  **Install Node.js dependencies:**
    *(This installs all required packages like Express, Mongoose, etc.)*
    ```sh
    npm install
    ```

### Running the Application 🚀

You need to run **two** terminal sessions simultaneously: one for the database and one for the application server.

1.  **Start the MongoDB Database:**
    Open a terminal and run the MongoDB daemon. Leave this terminal running.
    ```sh
    mongod
    ```

2.  **Start the Node.js Server:**
    Open a **new** terminal, navigate to the project directory (`MAJORPROJECT2`), and run:
    ```sh
    node app.js
    ```

3.  **Access the application:**
    Open your web browser and go to `http://localhost:8080/listings`.

## How to Use

1.  Navigate to the application URL in your browser.
2.  Register for a new account or log in with existing credentials.
3.  Browse the property listings on the homepage.
4.  Click on any listing to see its full details, reviews, and location on the map.
5.  Use the "Add New Listing" button to create and upload your own property.

## Author & Acknowledgements 🤝

This project was built by **Aaditya Sharma** as part of the Apna College DELTA 2.0 curriculum.

* **Aaditya Sharma** - [GitHub: Aaditya0807](https://github.com/Aaditya0807)

## License

Distributed under the MIT License. See `LICENSE` for more information.
