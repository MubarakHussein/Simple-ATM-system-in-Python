# Simple ATM Machine System 🏧

Welcome to the **Simple ATM Machine System** project! This Python script simulates a basic ATM interface where users can perform common banking operations such as checking balance, depositing money, and withdrawing money (with both predefined and custom withdrawal amounts). This project is designed to demonstrate fundamental concepts of Python such as functions, loops, conditionals, and user input handling.

## Features

- **PIN Authentication**: Secure login with a 4-digit PIN.
- **ATM Menu**: Users can select from options like:
  - Checking the balance
  - Withdrawing money (with predefined and custom amounts)
  - Depositing money
  - Exiting the system
- **Custom Withdrawal**: Allows users to enter any withdrawal amount (multiples of £10).
- **Input Validation**: Ensures correct and valid inputs from the user.
  
## How It Works

1. **PIN Entry**: 
   - The user is prompted to enter a PIN.
   - If the entered PIN matches the stored PIN (default: `7634`), the user gains access to the ATM menu.
   - Incorrect PINs are rejected.

2. **ATM Menu**:
   - The user can select from the following options:
     1. **Check Balance**: Displays the current account balance.
     2. **Withdraw Money**: Allows the user to select from predefined withdrawal amounts or enter a custom amount.
     3. **Deposit Money**: Placeholder for deposit functionality (not yet implemented).
     4. **Exit**: Ends the session and prints a goodbye message.

3. **Withdrawal Menu**:
   - Users can select from predefined withdrawal amounts (£10, £20, £50, £100).
   - A custom withdrawal option is available for amounts in multiples of £10.

4. **Balance Update**: The account balance is updated after each withdrawal, and the updated balance is displayed.

## Requirements

- Python 3.x
- Basic understanding of Python concepts like loops, conditionals, and user input handling.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/MubarakHussein/Simple-ATM-system-in-Python.git
