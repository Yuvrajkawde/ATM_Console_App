

This Java program simulates a user-friendly ATM interface with essential banking functionality. 
It encompasses five main components: AccountHolder, Account, BankTransaction, Bank, and ATM. 
The program enables users to interact with their bank accounts by providing a secure login, 
viewing transaction history, withdrawing funds, checking their balance, making deposits, transferring money between accounts, and quitting the application.

Key Features:
AccountHolder: Represents a bank account holder with attributes like name, user ID, and PIN. It ensures secure access to the ATM interface.
Account: Each AccountHolder has an associated Account object. It stores information about the account, including the account number and balance.
BankTransaction: Manages individual transactions, including deposits, withdrawals, and transfers. It keeps track of transaction history for each account.
Bank: The central component that holds all bank accounts and manages their operations. It allows creating new accounts, authenticating account holders, 
and performing account-related operations.

ATM: The user interface for the ATM system. It provides a menu-driven interface for users to perform various banking tasks.

Functionality:
Login Authentication: Users enter their user ID and PIN to access their accounts securely.
View Transaction History: Users can check their transaction history to monitor their financial activities.
Withdraw Funds: Users can withdraw money from their accounts, ensuring they have sufficient balance.
Check Balance: Users can check the current balance in their accounts.
Make Deposits: Users can deposit money into their accounts.
Transfer Money: Users can transfer funds between their own accounts or to another account within the bank.
Quit the Application: Users can exit the ATM interface.

Overall, this Java program provides a simple and secure way for users to manage their bank accounts through an intuitive ATM interface. 
It ensures the safety of user information and maintains a record of all financial transactions. Users can perform all essential banking tasks conveniently from this application.
