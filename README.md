# JavaLab_Session6
Java program demonstrating custom exception handling (LowBalanceException) in a banking withdrawal scenario.

This program simulates a simple banking system where users can attempt to withdraw money from their account, and it handles insufficient balance situations using custom exceptions.

LowBalanceException Class: A custom exception that is thrown when a withdrawal amount exceeds the account balance.

BankAccount Class: Contains the balance attribute and a withdraw() method. The method throws a LowBalanceException if the withdrawal amount is greater than the available balance.

BankApp Class (Main Class): Demonstrates the use of try-catch-finally blocks to handle exceptions. It attempts multiple withdrawals, showing both successful and failed transactions. The finally block ensures that a message is displayed after every transaction, regardless of success or failure.

The program emphasizes key Java concepts such as custom exceptions, throw and throws keywords, and structured exception handling to make banking transactions safe and predictable.

## Program Output:

Attempting to withdraw 6000...

Withdrawal failed: Insufficient balance!

Transaction completed.

Attempting to withdraw 3000...

Withdrawal successful! Remaining balance: 2000

Transaction completed.
