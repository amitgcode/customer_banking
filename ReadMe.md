# Banking System Project

# Overview
This project is a simple banking system that allows customers to two types of accounts, savings accounts and CD accounts. The system provides functionality to calculate interest earned and update account balances.

# Files
* Account.py
    
    This file contains the Account class, which is the class for all account types. It has attributes for balance and interest, and methods to set and get these values.

* cd_account.py
    
    This file contains the create_cd_account function, which creates a cd account as instance of account class, calculates interest earned, and updates the account balance.

* savings_account.py
    
    This file contains the create_savings_account function, which creates a savings account as instance of account class, calculates interest earned, and updates the account balance.

* customer_banking.py
    
    This file contains the main module.
        It interacts with user to get saving account information like initial balance, interest rate and term in months. Based these inputs, it calculate interest and account balance for saving account after term is over. 
        It also interact with user to get cd account information like initial balance, interest rate and term in months.Based these inputs, it calculate interest and account balance for CD account after term is over.

# Usage
    To use this project, simply run the customer_banking.py file. This will allow you to calculate interest and account balance after the term over for CD as well as Saving Account. 

# License
    This project is licensed under the MIT License. See the LICENSE file for details.
