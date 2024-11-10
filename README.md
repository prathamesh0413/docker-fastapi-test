# docker-fastapi-test
This project contains a FastAPI application that allows you to manage user data, including creating and retrieving user profiles. User data is stored in a JSON file, and the application is containerized using Docker to enable easy deployment.

Key Features
Add User Profiles: Create user profiles with fields for first name, last name, and age.
Retrieve User Profiles: Retrieve all stored user profiles from a JSON file.
Persistent Storage: User data is saved in a users.json file located in a data directory within the application.
Interactive API Documentation
FastAPI generates interactive API documentation, allowing easy testing of available endpoints.

Accessing the Documentation
Open your preferred web browser.
Go to http://localhost:8000/docs to view the interactive API documentation.
Using the API
To Retrieve the List of Users:
Find the GET /users endpoint in the documentation.
Click the "Try it out" button.
Press the "Execute" button to send the request.
The response will appear below, showing user information from the users.json file.

Prerequisites

Make sure you have the following installed:
 
Docker: Install Docker
Docker Compose
Getting Started

1. Clone the Repository
To start, clone this repository to your local machine:

git clone https://github.com/prathamesh0413/docker-fastapi-test
      cd docker-fastapi-test
      
1. Build and run the Docker container
   Run the following commands to start the app using Docker Compose:

    docker-compose up --build

2. Access the application
   
   Once running, the FastAPI application is accessible at http://localhost:8000.

3. Stopping the Docker container
   
     docker-compose down

API Endpoints
Using the API

To Retrieve the List of Users:

  Find the GET /users endpoint in the documentation.
  Click the "Try it out" button.
  Press the "Execute" button to send the request.
  The response will appear below, showing user information from the users.json file.

