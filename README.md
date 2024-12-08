# Hi, I'm Vrajesh! 👋, this is my


# *Banking Management System*

This project implements a simple *Banking Management System* in C, allowing users to perform essential banking operations such as creating accounts, managing customer information, and handling transactions. The system uses file handling to store data persistently, making it reusable across multiple program executions.

---

# *Table of Contents*

- [🛠 Features](#features)  
- [🔄 Working Flow](#working-flow)  
- [💾 Data Storage](#data-storage)  
- [📚 Key Functionalities Explained](#key-functionalities-explained)  
- [🚀 Future Improvements](#future-improvements)  
- [🌟 Advantages](#advantages)  
- [⚠ Limitations](#limitations)  
- [✅ Conclusion](#conclusion)
- [🔗 Links](#links)
- [🧑‍💻 Authors](#authors)

---

## *🛠Features*

*Create New Account*  
   - Enables users to create a new customer account by providing details such as name, date of birth, address, contact number, account type, and initial deposit.
   - Validates account numbers to avoid duplicates.

*View All Accounts*  
   - Displays a list of all accounts stored in the system, including account numbers, names, and addresses.

*Edit Account Information*  
   - Allows updating the address or phone number of an existing account while maintaining other details.

*Deposit and Withdrawal*  
   - Provides options for depositing or withdrawing money from an account.
   - Ensures transactions are validated based on the available balance.

*Erase Account*  
   - Permanently deletes a specified account from the system, ensuring the data is removed from the file.

*View Account Details*  
   - Displays all details of a specific account, including the account holder’s name, address, balance, and transaction history.

*Calculate Interest*  
   - Calculates simple interest for a savings or fixed deposit account based on the deposit amount and the duration.

*Persistent Storage*  
   - All account data is stored in a text file (record.dat) for persistent record-keeping.

---

##  *🔄Working Flow*

*Main Menu*  
   - The system begins by displaying a menu of operations for the user to select from.
   - Based on the user’s choice, the corresponding functionality is executed.

*Data Handling*  
   - All customer account data is stored in a file (record.dat).
   - A temporary file (new.dat) is used for editing and deleting operations to ensure data integrity.

*Control Flow*  
   - Each operation reads data from the file, processes it, and writes updates back to the file.
   - The program loops back to the main menu after completing an operation, allowing the user to perform multiple tasks.

---

## *💾Data Storage*

### File Structure: record.dat
- *Fields Stored*
  - Account Number  
  - Name  
  - Date of Birth  
  - Address  
  - Phone Number  
  - Account Type (Savings/Fixed)  
  - Balance  

- *File Usage*:  
  - Append mode is used for creating new accounts to preserve existing data.  
  - Read/write modes are used for viewing or modifying accounts.

### Temporary File: new.dat
- Used as an intermediary during editing or deletion to ensure no data is lost during file updates.

---

## *📚Key Functionalities Explained*

*Account Creation*  
   - Validates the uniqueness of the account number.  
   - Captures customer details and stores them in record.dat.

*View All Accounts*  
   - Reads record.dat and displays all stored accounts in a tabular format.

*Edit Account*  
   - Searches for the account using the account number.  
   - Updates only the address or phone number without altering other data.

*Transactions (Deposit/Withdraw)*  
   - Prompts the user for transaction details and validates the operation (e.g., ensures sufficient balance for withdrawals).  
   - Updates the account balance in record.dat.

*Erase Account*  
   - Searches for the account using the account number and deletes it by rewriting the data to new.dat (excluding the deleted account).  
   - Renames new.dat to record.dat after completion.

*View Account Details*  
   - Searches for a specific account and displays all stored details, including transaction history and interest calculations.

*Interest Calculation*  
   - Uses simple interest formulas based on the type of account and the specified time period.  
   - Provides estimated interest earnings for savings or fixed deposits.

---

## *🌟Advantages*

*Persistence*  
   - Data stored in a file ensures it remains available even after the program terminates.

*Scalability*  
   - The system can handle an increasing number of accounts due to efficient file handling.

*Ease of Use*  
   - A menu-driven interface ensures simplicity, making it accessible for non-technical users.

*Customizable*  
   - The modular structure of the code allows easy enhancements and feature additions.

---

## *⚠Limitations*

*No Security Measures*  
   - Lacks user authentication and encryption for sensitive data.

*Single-User Access*  
   - Only one user can access the system at a time due to local file handling.

*No Backup System*  
   - There’s no mechanism for automatic backups or recovery from data corruption.

*Text File Dependency*  
   - Using text files for data storage limits performance with larger datasets compared to databases.

---

##  *🚀Future Improvements*
- Implementing password protection for secure access.
- Adding more account types and interest schemes.
- Introducing graphical user interface (GUI) for better usability.
- Enabling network-based operations for multi-user environments.
- Adding data encryption to enhance security.

---

## *✅Conclusion*

The *Banking Management System* is a foundational project designed to demonstrate basic concepts of file handling, modular programming, and control flow in C. It provides essential banking features in a lightweight, offline environment and serves as an excellent starting point for more advanced systems. 

The system's design allows for further enhancements like integrating database management systems (DBMS), securing data with encryption, and providing multi-user access through networked implementations.

---


## *🔗Links*
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://vrajesh-sharma.github.io/Personal-Portfolio/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vrajesharma-7-dsa/)
[![twitter](https://img.shields.io/badge/youtube-DC143C?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Data-Nebula)

---
## *🧑‍💻Authors*

*[@Vrajesh-Sharma](https://www.github.com/Vrajesh-Sharma)*
