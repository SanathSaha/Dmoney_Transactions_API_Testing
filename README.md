# Dmoney-Transactions-REST-API-Test-Project Using Postman

## Project Overview

.This project focuses on testing the Dmoney REST API to validate its functionality, identify potential issues, and provide improvement recommendations. The testing
covers the creation, management, and processing of transactions across various user roles, including Admin, System User, Agent, Customers, and Merchant.

## Tools and Technology

- Postman
- Newman
- Nodejs
- VSCode

## Tasks and Flows

Created test cases for the following scenarios:

### 1. Test Cases

- Admin creates an Agent, 2 Customers, and a Merchant.
- System deposits money to the Agent.
- Agent deposits money to a Customer.
- Check Agent's balance.
- Send money between Customers.
- Customer withdraws money to the Agent.
- Check Customer's balance and transaction statement.
- Customer makes a payment to a Merchant.
- Check balances and transaction statements for Customers,
- The Merchant checks his balance.

#### Test cases Report : [Click Here](https://docs.google.com/spreadsheets/d/1v3_kUXm4l5Mucah1Gv2cTjyPeuagwmIb/edit?usp=sharing&ouid=117230072684772729129&rtpof=true&sd=true)

### 2. Postman Collection

- Created a Postman collection for all the scenarios.
- Added negative test cases for validation and error handling.
- Postman Collection : [Click here to see Postman Collection](https://.postman.co/workspace/Personal-workspace~09355ca1-1a07-4b42-ac99-18513d734993/collection/28043563-78741567-2ff0-4620-a711-e66989f9dd3f?action=share&creator=28043563)
- Endpoint Used :
     [User API](https://dmoney.roadtocareer.net/api-docs/user/)
     [Transactions API](https://dmoney.roadtocareer.net/api-docs/transaction/)

### 3. Newman Report

- Generate a report of all test cases using NEWMAN.
- Included Summary screenshots of the execution.
View the NEWMAN screenshots below :

<img width="841" height="834" alt="image" src="https://github.com/user-attachments/assets/8d4f7a76-c020-42a7-b808-f68d73f07421" />
<img width="560" height="700" alt="image" src="https://github.com/user-attachments/assets/b43a03ef-ca25-423d-92b5-a0da581981b5" />
<img width="538" height="830" alt="image" src="https://github.com/user-attachments/assets/0b0ac2d2-6bb9-4a22-b5e6-2f32812540c3" />
<img width="561" height="495" alt="image" src="https://github.com/user-attachments/assets/f54a0da4-c3a8-4ee2-91e0-7f69c1fc06c2" />

### 4. Postman Documentation

Postman documentation for the test cases and endpoints is available:
[Click Here to see the Postman Documentation](https://documenter.getpostman.com/view/28043563/2sB3HhsMaW)

### 5. Bug Report 

Reported Bug or Improvements in a Google Sheet, with details such as:

 - Issue Type (Bug/Improvement)
 - Issue Title
 - Description and Steps to Reproduce
 - Actual vs Expected Results
 - Priority and Severity
 - Attachments with screenshots
The Bug Report link : [Click here to see the bug report](https://docs.google.com/spreadsheets/d/1K825D2pXOx7taz2-IkwtXZJk4ODBQs4y/edit?usp=sharing&ouid=117230072684772729129&rtpof=true&sd=true)

### How to run this Project :

This project is designed to test the Dmoney REST API using JavaScript. It utilizes Node.js to run the test scripts and I provide a step-by-step guide for anyone to clone and run the project on their machine.

#### Prerequisites
      - NodeJs
      - Git
      
#### Installation

1. Clone this repo
      ``` git clone https://github.com/SanathSaha/Dmoney_Transactions_API_Testing ```

2. Install Dependencies
    ``` npm install ```

3. create '.env' file and copy from env.template and set your own PMAT key
4. Hit this command to run : ``` npm start ```

#### Running the Project

Run the 'reports.js' script using Node.js in the terminal :
``` npx newman run "copy & paste published collection link without inverted comma" ``` Then ``` node Reports.js ```

### Expected output

The script will run tests against the Dmoney REST API and display the results in the terminal.

### Contact

For any further queries please contact with - [](sanath.saha007@gmail.com)




     
