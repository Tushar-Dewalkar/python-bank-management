# Bank Management System

This is a simple Bank Management System implemented in Python. It allows users to perform various operations related to account management, such as creating a new account, depositing and withdrawing money, checking the account balance, displaying account details, closing an account, and modifying account information.

## Features

1. *New Account*: Users can create a new bank account by providing details such as account number, account holder name, account type (Savings or Current), and initial deposit amount.

2. *Deposit Amount*: Users can deposit money into an existing account by specifying the account number and the amount to be deposited.

3. *Withdraw Amount*: Users can withdraw money from an existing account, provided they have sufficient balance, by specifying the account number and the amount to be withdrawn.

4. *Balance Enquiry*: Users can check the account balance for a given account number.

5. *All Account Holder List*: This option displays the details of all existing bank accounts.

6. *Close an Account*: Users can close an existing bank account by providing the account number.

7. *Modify an Account*: Users can modify the account details, including the account holder name, account type, and balance, for an existing account.

8. *Exit*: Exit the Bank Management System.

## How to Use

1. Run the script in a Python environment.
2. The program will display a menu with options from 1 to 8.
3. Select an option by entering the corresponding number.
4. Follow the instructions provided by the program for each operation.
5. To exit the program, choose option 8.

Note: The data is stored using Python's `pickle` module, which serializes the account objects and saves them to a file named "accounts.data". Make sure not to delete this file if you want to retain the account data between program executions.

## Sample Usage

Here's a sample usage scenario to demonstrate the functionality of the Bank Management System:

1. Create a new account:
   
   MAIN MENU
   1. NEW ACCOUNT
   2. DEPOSIT AMOUNT
   3. WITHDRAW AMOUNT
   4. BALANCE ENQUIRY
   5. ALL ACCOUNT HOLDER LIST
   6. CLOSE AN ACCOUNT
   7. MODIFY AN ACCOUNT
   8. EXIT
   Select Your Option (1-8): 1

   Enter the account no: 1234
   Enter the account holder name: John Doe
   Enter the type of account [C/S]: S
   Enter the initial amount (>= 500 for Savings and >= 1000 for current): 1000

   Account Created
   

2. Deposit amount into an existing account:
   
   MAIN MENU
   1. NEW ACCOUNT
   2. DEPOSIT AMOUNT
   3. WITHDRAW AMOUNT
   4. BALANCE ENQUIRY
   5. ALL ACCOUNT HOLDER LIST
   6. CLOSE AN ACCOUNT
   7. MODIFY AN ACCOUNT
   8. EXIT
   Select Your Option (1-8): 2

   Enter the account no: 1234
   Enter the amount to deposit: 500

   Your account is updated
   

3. Withdraw amount from an existing account:
   
   MAIN MENU
   1. NEW ACCOUNT
   2. DEPOSIT AMOUNT
   3. WITHDRAW AMOUNT
   4. BALANCE ENQUIRY
   5. ALL ACCOUNT HOLDER LIST
   6. CLOSE AN ACCOUNT
   7. MODIFY AN ACCOUNT
   8. EXIT
   Select Your Option (1-8): 3

   Enter the account no: 1234
   Enter the amount to withdraw: 200

   Your account is updated
   

4. Check account balance:
   
   MAIN MENU
   1. NEW ACCOUNT
   2. DEPOSIT AMOUNT
   3. WITHDRAW AMOUNT
   4. BALANCE ENQUIRY
   5. ALL ACCOUNT HOLDER LIST
   6. CLOSE AN ACCOUNT
   7. MODIFY AN ACCOUNT
   8. EXIT
   Select Your Option (1-8): 4

   Enter the account no: 1234

   Your account balance is = 1300
   

5. Display all account holders:
   
   MAIN MENU
   1. NEW ACCOUNT
   2. DEPOSIT AMOUNT
   3. WITHDRAW AMOUNT
   4. BALANCE ENQUIRY
   5. ALL ACCOUNT HOLDER LIST
   6. CLOSE AN ACCOUNT
   7. MODIFY AN ACCOUNT
   8. EXIT
   Select Your Option (1-8): 5

   1234 John Doe S 1300
   

6. Close an account:
   
   MAIN MENU
   1. NEW ACCOUNT
   2. DEPOSIT AMOUNT
   3. WITHDRAW AMOUNT
   4. BALANCE ENQUIRY
   5. ALL ACCOUNT HOLDER LIST
   6. CLOSE AN ACCOUNT
   7. MODIFY AN ACCOUNT
   8. EXIT
   Select Your Option (1-8): 6

   Enter The account No.: 1234

   Account closed successfully
   

7. Modify an account:
   
   MAIN MENU
   1. NEW ACCOUNT
   2. DEPOSIT AMOUNT
   3. WITHDRAW AMOUNT
   4. BALANCE ENQUIRY
   5. ALL ACCOUNT HOLDER LIST
   6. CLOSE AN ACCOUNT
   7. MODIFY AN ACCOUNT
   8. EXIT
   Select Your Option (1-8): 7

   Enter The account No.: 1234
   Enter the account holder name: John Doe
   Enter the account Type: C
   Enter the Amount: 2000

   Account modified successfully
   

8. Exit the program:
   
   MAIN MENU
   1. NEW ACCOUNT
   2. DEPOSIT AMOUNT
   3. WITHDRAW AMOUNT
   4. BALANCE ENQUIRY
   5. ALL ACCOUNT HOLDER LIST
   6. CLOSE AN ACCOUNT
   7. MODIFY AN ACCOUNT
   8. EXIT
   Select Your Option (1-8): 8

   Thanks for using the bank management system
   

Please note that the actual execution may vary depending on user inputs and the state of the accounts.data file. The program will prompt for user input and display appropriate messages based on the selected options.

## Note

This is a basic Bank Management System implementation for learning purposes. In real-world applications, security measures, error handling, and other features would be essential considerations. Additionally, using pickle for data storage has limitations, and other more robust data storage methods would be preferred for production use.
