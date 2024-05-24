# User Management App

This is a Node.js application for managing users. The application uses MongoDB for data storage and includes a development setup, as well as CI/CD integration using GitHub Actions.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Environment Variables](#environment-variables)
- [Database](#database)
- [CI/CD with GitHub Actions](#cicd-with-github-actions)

## Prerequisites
- Node.js (version 14.x or higher)
- npm (version 6.x or higher)
- MongoDB (version 4.x or higher)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/user-management-app.git
   cd user-management-app

## Install dependencies
    npm install

## Running the Application
    npm run dev

## API Documentation
    To facilitate API testing, a Postman collection is provided.

    Importing the Postman Collection
    Open Postman.
    Click on the Import button in the top left corner.
    Select the Collection tab.
    Drag and drop the JSON file located in the postman_collection folder of this repository, or click Upload Files and select the file manually.
    The collection will be imported, and you can now use the predefined requests to test the API.

## CI/CD with GitHub Actions
    This project uses GitHub Actions for continuous integration and deployment.

    Setting up GitHub Actions
    Create a .github/workflows directory in the root of your project.
    Add a ci.yml file in the .github/workflows directory with the following content: