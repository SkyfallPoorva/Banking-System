# Terminal Banking System

A terminal-based banking system built with Python that supports account creation, login, deposits, withdrawals, balance check, and transaction history logging.

## Features

- Account creation with PIN authentication
- Login system
- Deposit and withdraw money
- View balance and transaction history
- File-based data storage using `accounts.txt` and `transactions.txt`
- Styled console output using ANSI colors

## Usage

Run the following command:

```bash
python banking_system.py

# Project Structure
terminal-banking-system-v2/
├── banking_system.py         # Main Python application
├── accounts.txt              # Stores account number, PIN, and balance (auto-generated)
├── transactions.txt          # Stores transaction logs (auto-generated)
├── README.md                 # Documentation file


💡 How It Works
Create Account

Enter an account number and set a 4-digit PIN.

A new entry is created in accounts.txt.

Login

Users authenticate using their account number and PIN.

If successful, they enter a secure banking menu.

Banking Operations

Deposit: Add money to your account.

Withdraw: Remove money (if balance is sufficient).

Check Balance: View current balance.

Transaction History: View past transactions stored in transactions.txt.

Logout

Safely exit the user session.
