# Mini-Project
This is a simple banking system code that allows users to create bank accounts, make deposits, withdrawals, check balances, and view transaction history. Here's a breakdown of how the code works:

The program defines two classes: 

Transaction and BankAccount.

Transaction represents a transaction with properties like amount and type.

BankAccount represents a bank account with properties like accountNumber, accountHolderName, balance, transactionCount, and an array of Transaction objects to store transaction history.


The program also defines several functions:

createAccount: Creates a new bank account and adds it to the accounts array if there is space. It takes parameters like account number, account holder name, and initial balance.

findAccount: Searches for a bank account with a given account number and returns a pointer to that account.


In the main function, 

the program initializes an array of BankAccount objects and an accountCount variable to keep track of the number of accounts. It also provides a simple command-line interface for interacting with the banking system.
