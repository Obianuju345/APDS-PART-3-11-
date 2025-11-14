# APDS-PART-3-11-
# Mainette World Bank - International Payments System

## Overview
A sophisticated banking application that enables secure international money transfers. Customers can send funds overseas while bank employees efficiently review and approve transactions with robust security measures.

 ## What This Application Does
This is a secure online banking system that allows:
#### •	Bank Customers to send money to other countries
#### •	Bank Employees (also known as admins) to check and approve these international payments
Look at it like online banking, but specifically for sending money overseas safely.

## Setup Instructions for Visual Studio Code
### Step 1: Open the Project in VS Code
1.	Open Visual Studio Code
2.	Click File then Open Folder
3.	Select the main project folder that contains both frontend and backend folders
4.	Click Open
### Step 2: Set Up the Backend (Server)
In VS Code:
1.	Look at the left sidebar and find the backend folder
2.	Right-click on the backend folder
3.	Select "Open in Integrated Terminal"
#### In the Terminal:
##### 1.	Type this command and press Enter:
npm install
This downloads all required server components

##### 2.	After installation, type:
node server.mjs
This starts the server

##### 3.	You should see: Server running on https://localhost:3000
Keep this terminal window open!

### Step 3: Set Up the Frontend (Website)
#### Open a NEW Terminal in VS Code:
1.	Click Terminal then choose New Terminal
2.	In the new terminal, navigate to the frontend folder by typing:
cd frontend
## Install and Start the Website:
### 1.	Type this command and press Enter:
npm install
This downloads all website components

### 2.	After installation, type:
npm start
This starts the website

### 3.	Your browser should automatically open to: http://localhost:3000

## How to Use the Application
For Customers - Sending Money Overseas
### Step 1: Choose Your Role
•	Open the website at http://localhost:3000
•	Click on "Customer"
### Step 2: Log In
•	Enter your bank account number
•	Enter your password
•	Click "Secure Login"
### Step 3: Make a Payment
•	Click "Make New Payment"
•	Fill in the recipient's details:
o	Recipient's full name
o	Recipient's bank account number
o	Recipient's bank name
o	SWIFT code (international bank code)
o	Amount to send
o	Currency type (USD, EUR, etc.)
•	Click "Submit Payment"
### Step 4: Check Your Payments
•	View all your payments on the dashboard
•	See which are:
o	Pending (waiting for bank approval)
o	Approved (successfully sent)
o	Declined (not approved - contact bank)

## For Employees - Checking Payments
### Step 1: Choose Your Role
•	Open the website at http://localhost:3000
•	Click on "Bank Employee"
### Step 2: Log In
•	Use the username and password provided by the bank
•	Click "Secure Login"
### Step 3: Review Payments
•	See all payments waiting for approval
•	Check each payment's details:
o	Is the recipient's name correct?
o	Is the bank account number valid?
o	Is the SWIFT code correct?
### Step 4: Approve or Decline
•	Click " Verify Payment" if everything looks good
•	Click " Decline Payment" if there are problems
•	Approved payments are automatically sent to the international banking system



## Running Both Systems Together
In VS Code, You Need TWO Terminal Windows:
### Terminal 1 (Backend):
•	Should show: Server running on https://localhost:3000
•	Don't close this terminal!
### Terminal 2 (Frontend):
•	Should show: webpack compiled successfully
•	Don't close this terminal!
#### If You Need to Stop the Systems:
•	Click in each terminal window
•	Press Ctrl + C to stop that part
•	To restart, use the same commands as before
Troubleshooting in VS Code
## Common Problems:
Problem: "npm install" doesn't work
Solution: Make sure you're in the correct folder in the terminal
Problem: Website won't load
Solution: Check that both backend and frontend are running in separate terminals
Problem: Error messages in terminal
## Solution:
1.	Make sure you ran “npm install” command first in both folders
2.	Check that no other programs are using ports 3000 or 5000
Problem: Can't find the folders
Solution: Use VS Code's file explorer on the left to navigate


# Project Structure

Mainette World Bank/
├── 📁 backend/                 # Server Application
│   ├── 📁 routes/             # API Endpoints & Logic
│   ├── 🚀 server.mjs          # Main Server File
│   └── 📄 package.json        # Server Dependencies
│
└── 📁 frontend/                # Client Application
    ├── 📁 src/
    │   ├── 📁 components/      # UI Components & Pages
    │   ├── 📁 services/        # Server Communication
    │   └── 🔧 App.js           # Main Application File
    └── 📄 package.json         # Client Dependencies

## Security Features
### Your Data is Protected By:
•	Bank-level encryption - like a secure tunnel for your information
•	Automatic hacking protection - stops unauthorized access
•	Secure login - your password is always protected
•	Input checking - prevents typing mistakes and malicious entries
### Tips for Using VS Code
•	Use Ctrl+` (backtick) to open/close the terminal quickly
•	The left sidebar shows all your files - click to explore
•	Green lines in the terminal mean things are working properly
•	Red lines usually mean errors that need fixing

# GitHub Link


# Demo Video
https://www.youtube.com/watch?v=Yt4w1dz0L4g

# Team Members
Mainette Mupataie
Genevieve Udodi
