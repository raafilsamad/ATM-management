ATM Management System (Interactive UI in Google Colab)
Project Overview

This project is a simulation of an ATM Management System with an interactive user interface designed to run in Google Colab.
It allows users to:

Login securely using a PIN

Check their account balance

Deposit money

Withdraw money

Exit the ATM interface

The interface is interactive, fully functional inside Colab, and mimics the behavior of a real ATM.

Features

PIN Authentication

Users must enter a valid PIN to access the ATM.

Invalid PIN attempts are handled with error messages.

Balance Management

Users can view their current account balance at any time.

Deposit Functionality

Users can deposit any positive amount.

Updated balance is displayed immediately.

Withdrawal Functionality

Users can withdraw money as long as sufficient balance is available.

Invalid or excessive withdrawals are handled properly.

Interactive User Interface

Built with ipywidgets for clickable buttons and input boxes.

All outputs and messages appear dynamically within the same interface.

Technology Stack

Language: Python 3

Libraries:

ipywidgets – For interactive input and buttons

IPython.display – For rendering widgets in Colab

Platform: Google Colab

How to Use

Open Google Colab.

Create a new notebook.

Copy and paste the project code into a cell.

Run the cell.

Enter PIN in the password box to log in.

Use the buttons to Check Balance, Deposit, Withdraw, or Exit.

Getting Started
# Install ipywidgets if not already installed
!pip install ipywidgets


Run the notebook after installation.

PIN is initially set to 1234.

Initial balance is ₹5000.

Project Flow

Login Page → Enter PIN

ATM Menu → Buttons for Check Balance, Deposit, Withdraw, Exit

Deposit/Withdraw → Enter amount in input box and confirm

Result Display → Confirmation or error messages appear dynamically

Exit → Ends the session with a goodbye message

Advantages

No web server or Flask required → runs instantly in Colab

Fully interactive → mimics real ATM functionality

Easy to modify for multiple users or different starting balances

Future Enhancements

Support multiple users with different PINs and balances

Add transaction history for each account

Enable dynamic initial balance setup for different users

Improve UI with colors, icons, and styling

Author

Raafil A S– Developer & Project Creator
