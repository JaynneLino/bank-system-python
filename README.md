# Bank Management System 🏦

A Python-based CLI application that simulates a banking environment with two distinct access levels: **Administrator** and **Client**.

### 🔑 Access Levels
- **Admin:** Can register new clients, list all users, search by NIF, and generate bank-wide statistics (Total balance, average, max/min holders).
- **Client:** Can check balance, deposit, withdraw (with password validation), and transfer funds to other IDs.

### ⚙️ Technical Highlights
- **Security:** Login system with a maximum of 3 attempts before lockout.
- **Data Integrity:** NIF and CC validation (checking for duplicates and length).
- **Automation:** Real-time financial reports and transaction timestamps.
- **Libraries used:** `datetime`, `getpass`, `os`, `sys`.

---
*Developed as part of my Python Logic studies.*
