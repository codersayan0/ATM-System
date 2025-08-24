# ATM System

A **console-based ATM simulation** built in Java.  
This project enables users to log in with a Customer Number and PIN, access **Checking & Savings accounts**, perform transactions, and **securely change their PIN**.

---

## Features

- **Secure Login System**
  - Predefined Customer Numbers & PINs
  - Handles invalid inputs gracefully

- **Checking Account**
  - View Balance
  - Withdraw Money
  - Deposit Funds

- **Savings Account**
  - View Balance
  - Withdraw Money
  - Deposit Funds

- **PIN Management**
  - Change PIN with confirmation

- **Console Navigation**
  - Easy menu-driven interface

---

## Project Structure

```plaintext
ATM.java          // Main entry point
OptionMenu.java   // Handles login, menus, navigation
Account.java      // Manages balances, deposits, withdrawals
