# 💳 Terminal Banking System

A terminal-based banking system built using Python. This system allows users to securely create accounts, log in, deposit and withdraw funds, check balances, and view transaction history—all from the command line.

---

## 🚀 Features

- 🆕 Account Creation with PIN authentication
- 🔐 Login System
- 💰 Deposit and Withdraw Money
- 🧾 Balance Check and Transaction History
- 📁 File-based Data Storage:
  - `accounts.txt` for account details
  - `transactions.txt` for transaction logs
- 🎨 Styled console output using ANSI color codes

---

## 🛠️ Project Structure


---

## 💡 How It Works

### 🆕 Create Account
- Enter an **account number** and set a **4-digit PIN**.
- A new record is added to `accounts.txt`.

### 🔐 Login
- Authenticate using account number and PIN.
- Access the secure banking menu on successful login.

### 🏦 Banking Operations
- **Deposit**: Add money to your account.
- **Withdraw**: Withdraw money (if balance allows).
- **Check Balance**: View your current balance.
- **Transaction History**: View all past transactions from `transactions.txt`.

### 🔓 Logout
- Safely exit your session.

---

## ▶️ Usage

To run the banking system:

```bash
python banking_system.py
