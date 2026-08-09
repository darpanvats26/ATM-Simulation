# ATM-Simulation
A menu-driven ATM Simulation System developed in Python using Object-Oriented Programming (OOP). The application supports account creation, secure login, balance inquiry, deposits, withdrawals, money transfers, PIN management, and transaction history, with all data stored in CSV files using Pandas.

# ATM Simulation System

The ATM Simulation System is a menu-driven Python application that simulates the basic functionalities of an Automated Teller Machine (ATM). The project is developed using Object-Oriented Programming (OOP) concepts and stores account and transaction data in CSV files using the Pandas library.

Users can create accounts, securely log in using their account number and PIN, perform banking operations, and view transaction history through an interactive command-line interface.

---

## Features

- Create a new bank account
- Automatically generate unique account numbers
- Secure login using a 4-digit PIN
- Check account balance
- Deposit money
- Withdraw money
- Transfer money between accounts
- Change account PIN
- View mini statement (last 5 transactions)
- View complete transaction history
- Store account details and transactions in CSV files
- Exception handling for invalid inputs
- Menu-driven user interface

---

## Technologies Used

- Python 3
- Pandas
- Object-Oriented Programming (OOP)
- CSV File Handling

---

## OOP Design

The project is organized into three classes:

### Account
Handles account-related operations:
- Account creation
- Login authentication
- Account number generation
- Loading and saving account data

### Transaction
Manages transaction records:
- Generate transaction IDs
- Store transaction history
- Display mini statements
- Display complete transaction history

### ATM
Controls all banking operations:
- Balance inquiry
- Deposit
- Withdrawal
- Money transfer
- PIN management
- Menu navigation

---

## Project Structure

```
ATM-Simulation-System/
│
├── ATM_Simulation.ipynb
├── accounts.csv
├── transactions.csv
├── README.md
└── LICENSE
```

---

## How to Run

1. Install Python 3.
2. Install the required library:

```bash
pip install pandas
```

3. Open the project in Jupyter Notebook.
4. Run all notebook cells from top to bottom.
5. Execute the final cell to start the ATM application.

---

## Main Menu

```
==================================================
          PYTHON NATIONAL BANK
==================================================

1. Create Account
2. Login
3. Exit
```

---

## ATM Menu

```
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Transfer Money
5. Mini Statement
6. Full Statement
7. Change PIN
8. Logout
```

---

## Files Used

### accounts.csv

Stores account information.

| Field |
|-------|
| Account Number |
| Name |
| PIN |
| Balance |

---

### transactions.csv

Stores transaction history.

| Field |
|-------|
| Transaction ID |
| Date |
| Time |
| Account Number |
| Transaction Type |
| Amount |
| Balance |

---

## Concepts Demonstrated

- Object-Oriented Programming (OOP)
- Classes and Objects
- Constructors (`__init__`)
- Methods
- Functions
- Conditional Statements
- Loops
- Exception Handling
- File Handling
- Pandas DataFrames
- CSV File Operations

---

## Future Enhancements

Possible improvements include:

- Login attempt limit
- Transaction receipts
- PIN masking during login
- Interest calculation
- Account deletion
- Admin panel
- Graphical User Interface (GUI)
- Database integration (SQLite/MySQL)

---

## Author

**Darpan Vats**

MSc Bioinformatics | Python | Machine Learning | Computational Biology
