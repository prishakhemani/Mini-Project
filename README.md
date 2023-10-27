# Mini-Project
This is a simple banking system code that allows users to create bank accounts, make deposits, withdrawals, check balances, and view transaction history. Here's a breakdown of how the code works:

The program defines two classes: 

1)Transaction 

2)BankAccount.

Transaction represents a transaction with properties like amount and type.

BankAccount represents a bank account with properties like accountNumber, accountHolderName, balance, transactionCount, and an array of Transaction objects to store transaction history.


The program also defines several functions:

createAccount: Creates a new bank account and adds it to the accounts array if there is space. It takes parameters like account number, account holder name, and initial balance.

findAccount: Searches for a bank account with a given account number and returns a pointer to that account.


In the main function, 

the program initializes an array of BankAccount objects and an accountCount variable to keep track of the number of accounts. It also provides a simple command-line interface for interacting with the banking system.

Brief summary of the functionality for each menu option:

Option 1: Allows the user to create a new bank account.

Option 2: Allows the user to deposit money into an existing account.

Option 3: Allows the user to withdraw money from an existing account.

Option 4: Allows the user to check the balance of an existing account.

Option 5: Allows the user to view the transaction history of an existing account.

Option 6: Exits the program.
