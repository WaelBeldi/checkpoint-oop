## Objective

The objective is to create a Python class named **`Account`** with methods for depositing, withdrawing, and checking balances.  
The class should be encapsulated in a script called **`bank_account.py`** to simulate basic bank account operations.

---

## Class Definition

Create a class called **`Account`** with the following attributes:

- **`account_number`** (string)  
- **`account_balance`** (float)  
- **`account_holder`** (string)

---

## Methods

The `Account` class should include the following methods:

- **`deposit(amount: float)`**  
  Adds the given amount to the account balance.

- **`withdraw(amount: float)`**  
  Subtracts the given amount from the account balance **only if** the current balance is greater than or equal to the withdrawal amount.

- **`check_balance()`**  
  Returns the current account balance.

---

## Instructions

1. Define the `Account` class and its attributes as specified above.  
2. Define the `deposit()` method to add the deposited amount to the account balance.  
3. Define the `withdraw()` method to subtract the withdrawal amount from the balance only if sufficient funds are available.  
4. Define the `check_balance()` method to return the current balance.  
5. Create an instance of the `Account` class and assign it to a variable called **`my_account`**.  
6. Use the class methods to deposit money, withdraw money, and check the account balance.  
7. Test the program by creating multiple instances of the class and performing different transactions on each account.

---
