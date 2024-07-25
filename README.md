API Testing Postman Projects
API Testing - SOAP Project#1 Number To Words
Project Name : Number Conversion Service
# API Testing - SOAP Project#1: Number To Words

## Project Name: Number Conversion Service

## Project URL
[Number Conversion Service API Documentation](https://www.dataaccess.com/webservicesserver/NumberConversion.wso?op=NumberToWords)

## Project Description
This project involves testing the SOAP API for number to words conversion. The API converts numerical input into its English word equivalent. The testing focuses on validating the functionality of the API endpoint and handling various input scenarios.

## Test Cases
A set of Postman test cases have been created to cover different scenarios for the number to words conversion API. These include positive and negative test cases to ensure robustness and accuracy in conversion results.

## Running Tests with Newman
Newman is a command-line collection runner for Postman. It allows you to run and test a Postman collection directly from the command line.

### Prerequisites
- Node.js installed on your system.
- Newman installed globally via npm.

### Installation
1. Install [Node.js](https://nodejs.org/).
2. Install Newman globally using npm:
   ```sh
   npm install -g newman

URL of the project https://www.dataaccess.com/webservicesserver/NumberConversion.wso?op=NumberToWords

Newman Report




Project Details:

Create booking with valid data
- create booking with invalid first name (null)
- Invalid JSON
- invalid total price
- empty values of all fields
- invalid mandatory
- min and mx values for all - Total=11000000000000000222002002
- Invalid URL
- Deposit false
- Long name
- Arabic names
- Different date formats
- Special chars
- Reponse time

Integration Scenario:
- Create a booking-> Update the booking name -> Get booking id and verify
- Create a booking-> delete the booking name -> Get booking id and verify if it exists
- Create a booking-> delete the booking name 
- Get existing booking-> Update the booking name -> Get booking id and verify
