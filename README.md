Bank Management System (C++)
A simple, menu-driven banking application developed in C++ using
Object-Oriented Programming (OOP) concepts. It demonstrates basic
banking operations such as creating accounts, depositing money,
withdrawing money, checking account details, displaying all accounts,
and transferring money.
Features
Create Savings and Current accounts
Deposit money into an account
Withdraw money according to account rules
Check account details and current balance
Display all accounts and the total balance
Transfer money between accounts
Input validation for account numbers, amounts, and names
Automatically generated account numbers starting from `1001`
Account Rules
---
Account Type                        Rule
---
Savings Account                     Requires a minimum opening balance
of ₹500 and must maintain at least
₹500 after withdrawal.
Current Account                     Supports an overdraft of up to
₹5,000.
OOP Concepts Used
Class and Object: Organise account and bank-related data and
operations.
Encapsulation: Protect account data and provide controlled
access through member functions.
Inheritance: `SavingsAccount` and `CurrentAccount` inherit from
the `Account` base class.
Polymorphism: Different account types implement their own
withdrawal rules.
Abstraction: The abstract `Account` class defines common
behaviour for account types.
Technologies
Language: C++
Concepts: Object-Oriented Programming
Compiler: GNU C++ (`g++`) or another standard C++ compiler
How to Run
Save the source code in a file named `bank.cpp`.
Open a terminal in the folder containing the file.
Compile the program:
    ``` bash
    g++ bank.cpp -o bank
    ```
Run the program:
Linux / macOS
    ``` bash
    ./bank
    ```
Windows
    ``` bash
    bank.exe
    ```
You can also open the source file in an IDE such as Code::Blocks,
Dev-C++, or Visual Studio and use Compile & Run.
Main Menu
The program provides these options:
Create a new account
Deposit money
Withdraw money
Check account details
Display all accounts
Transfer money
Exit
Project Purpose
This mini project is created for learning and demonstrating the use of
C++ and OOP concepts in a simple real-world-style banking application.
Limitations
This is a basic console-based educational project.
Account information is stored in memory while the program is
running; it is not a production banking system.
It does not include database connectivity, user login, or online
banking security.
Author
Kanishak Thakur  
UID: 25BCD10017  
Subject: Object Oriented Programming  
College: Chandigarh University  
Submitted to: Ms Suman
