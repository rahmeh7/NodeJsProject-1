Assessment Tasks

Implement assignment using:
Language: Node
Framework: Express
Two endpoints are required

    GET /items: returns a list of medical bills
    POST /items: creates a new medical bill

A medical bill has the following properties:

 - patient name and address

 - the hospital name

 - date of service

 - bill amount.

Both endpoints should accept and return JSON.

You do not need to persist the bills to a database. Keep them in memory.

Provide API tests for both endpoints.

Instructions To Run the File:-

This is a simple medical billing system implemented using Node.js and the Express framework.

Requirements
1) Node.js
2) npm

Installation
Clone the repository:
git clone https://github.com/rahmeh7/NodeJsProject-1

Navigate to the project directory:
cd NodeJsProject-1

npm install
It will Install the dependencies

Running the Application
Start the application by running the following command:
npm start

The application will be running on http://localhost:3000.

Running the Tests
Run the tests by using the following command:
npm test

Endpoints and the Data Structure used here:-

Endpoints
GET /items: Returns a list of medical bills.
POST /items: Creates a new medical bill.
Data Structure
A medical bill has the following properties:

patientName: Patient name
patientAddress: Patient address
hospitalName: Hospital name
dateOfService: Date of service
billAmount: Bill amount
