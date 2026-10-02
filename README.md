# Simulated Parking System

## Project Overview
Contained in this project are Java and CSS files that comprise the front and backend of this system. We built a mobile app using modern JavaFX structures and MVC architecture to create an interactive map of the parking where a user can register multiple cars and select a parking spot to reserve. We use a remote and hosted SQL database to hold transactional records for parking reservations and user information. User's can create an account with us by providing a valid username and password to be stored within our table records. Furthermore, the system features an integrating payment system using Stripe's API that allows for various payment methods including credit cards, Apple Pay, Cashapp, Klarna, etc.

## Frontend
JavaFX & SceneBuilder: All views and screens on the template are managed by the JavaFX Scenes that contain raw html code and styling. Information is passed to and from the backend Java controllers. Scene items are accessed via descriptive ID names to transfer data.

## Backend
Java: The backend of our application is orchestrating using Java controllers and object models to contain data and transfer it to respective areas for processing. API keys are securely stored in environmental variables in order to access Stripe payment systems.

## Database
MySQL & DBeaver: Our data is hosted on a remote MySQL server where parking spot, car, and personal information is neatly stored to be pulled back out and transformed into Java objects. We primarily interacted with our database through the help of a management tool called DBeaver. After discovering latency problems, we converted our database connection to a Singleton Pattern where the application accesses a single, global connection point to maintain performace.

Please watch our demonstration of our application and hard work!: https://youtu.be/Sgfebme__08
