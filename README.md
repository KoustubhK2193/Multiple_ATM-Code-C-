# ATM Management System

## Overview

The **ATM Management System** is a C++ application designed to simulate an ATM interface for two major banks: ICICI and HDFC. This prototype allows users to manage their banking needs efficiently, including account creation, secure PIN setup, and essential banking transactions such as deposits, withdrawals, and balance checks.

## Features

- **Account Creation**: Users can create a new bank account through a simple interface.
- **Secure PIN Setup**: Users can set their ATM PIN via an OTP (One-Time Password) verification process to ensure account security.
- **Transaction Operations**:
  - **Deposit**: Easily deposit funds into the bank account.
  - **Withdrawal**: Withdraw cash as needed, with customizable amounts.
  - **Check Balance**: View current account balance at any time.
- **Transaction History**: File handling is implemented to track and display the history of transactions for user reference.
- **Inter-Bank Functionality**: Users from ICICI can use HDFC ATMs and vice versa, with applicable fees for inter-bank transactions.

## Technologies Used

- **Programming Language**: C++
- **OOP Concepts**:
  - **Classes and Objects**: Structuring the code with relevant entities.
  - **Inheritance**: Extending functionalities for various bank operations.
  - **Polymorphism**: Utilizing method overriding for flexible operations.
- **File Handling**: For persistent storage of user data and transaction history.

## Installation

To set up the ATM Management System on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/KoustubhK2193/ATM-Management-System-for-Multiple-Banks.git
2. **Navigate to the project directory**:
   ```bash
   cd ATM-Management-System-for-Multiple-Banks
3. **Compile the C++ files**:
   ```bash
   g++ main.cpp -o atm_system
4.**Run the Program**:
   ```bash
  ./atm_system
   ```
## Usage

To use the ATM Management System, follow these steps:

1. **Launch the Application**:
   - Open your terminal or command prompt.
   - Navigate to the project directory where the compiled executable (`atm_system`) is located.
   - Run the application using the following command:
     ```bash
     ./atm_system
     ```

2. **Follow the On-Screen Prompts**:
   - After launching the application, you will be presented with a menu of options.
   - You can create a new bank account by selecting the corresponding option.

3. **Create a Bank Account**:
   - Enter the required information (e.g., name, initial deposit).
   - Confirm the creation of your account.

4. **Set Your ATM PIN**:
   - Choose the option to set your ATM PIN.
   - You will receive an OTP (One-Time Password) for verification.
   - Enter the OTP and then input your desired PIN to complete the setup.

5. **Perform Transactions**:
   - You can choose from the following operations:
     - **Deposit**: Input the amount you wish to deposit into your account.
     - **Withdrawal**: Specify the amount you want to withdraw.
     - **Check Balance**: View your current account balance.

6. **Access Transaction History**:
   - Select the option to view your transaction history.
   - The application will display a list of past transactions, allowing you to review your activity.

By following these steps, you can effectively manage your banking needs through the ATM Management System.
