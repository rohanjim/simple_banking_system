# simple_banking_system
A console-based banking system written in Python that allows Admins and Customers to perform basic banking operations.
The system uses simple .txt files as a lightweight database to store user accounts and transaction history.
🚀 Features
👨‍💼 Admin Functions

Secure Admin Login

Create New Customer Profile

Search Customer Details

View Customer Transaction History

Automatically logs initial balance as a Deposit

👤 Customer Functions

Customer Login

Deposit Money

Withdraw Money

View Transaction History

Real-time balance calculation

📁 Database Files

This system uses three text files as databases:

admin_db.txt
customer_db.txt
transaction_db.txt


All files must be in the same folder as the Python script.

🧩 Sample Data Included
📌 admin_db.txt
A1001,David,admin123
A1002,Sophia,securepass
A1003,Michael,pass2025

📌 customer_db.txt
C2001,Alice Tan,Kuala Lumpur,0123456789,alice2025,1500
C2002,Ravi Kumar,Penang,0119988776,ravi789,2500
C2003,Linda Wong,Johor,0175544332,linda123,3200
C2004,Marcus Lee,Selangor,0136677889,marcus88,500
C2005,Siti Aisyah,Sabah,0194433221,siti556,1000

📌 transaction_db.txt
C2001,1500,Deposit
C2001,-300,Withdrawal
C2001,200,Deposit

C2002,2500,Deposit
C2002,-500,Withdrawal

C2003,3200,Deposit

C2004,500,Deposit
C2004,-200,Withdrawal
C2004,-50,Withdrawal

C2005,1000,Deposit
C2005,300,Deposit

▶ How to Run
1. Install Python 3

Download from https://www.python.org

2. Open the project in VS Code

File → Open Folder

Select your project folder

3. Install Python extension

From VS Code extensions panel:
Python – by Microsoft

4. Run the script

Open the VS Code terminal and type:

python banking_system.py

🎯 Learning Objectives

This beginner‐friendly project demonstrates:

File handling (read/write operations)

Menu-driven programs

User authentication

Banking logic implementation

Modular functional programming

Text-based data storage

Ideal for Python students, assignments, and mini-projects.

📌 Limitations

Passwords stored in plain text

No validation for phone numbers, IDs, etc.

No real database (uses .txt files)

No GUI

Some menus use recursion instead of loops

🌟 Possible Future Improvements

Migrate to SQLite/MySQL

Add GUI (Tkinter / PyQt / Web App)

Add transaction filters (date, type, amount)

Use OOP instead of procedural style

Encrypt passwords

Add account deletion/update
