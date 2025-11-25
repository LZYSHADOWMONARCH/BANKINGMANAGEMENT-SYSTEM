🏦 Online Banking Management System
A Java-based desktop application that simulates essential banking operations such as account creation, deposits, withdrawals, PIN generation, balance enquiry, and more.
This project uses Java Swing (GUI) and MySQL / JDBC for backend operations.
📌 Overview
The Online Banking Management System is designed to provide basic banking functionalities in a secure and user-friendly interface.
Users can create new accounts, log in using a PIN, and perform various transactions through an intuitive ATM-style GUI.
This project is ideal for learning Java, Swing, Object-Oriented Programming, and Database Connectivity (JDBC).
🎯 Objectives
To implement a functional banking system using Java.
To provide a graphical user interface that resembles real ATM operations.
To demonstrate CRUD operations using MySQL database.
To ensure secure login and PIN verification.
To store and manage user accounts efficiently.
🧩 Features
👤 User Features
Create a new bank account
Auto-generated application form number
Secure PIN generation
Login using card number + PIN
Money Deposit
Money Withdrawal
Fast Cash options
Balance Enquiry
View and update account details
🛢️ Backend Features
JDBC connection to MySQL
Separate classes for each operation
ATM-style UI using Java Swing
Fully object-oriented modular structure





📂 Project Structure
BANKING MANAGEMENT SYSTEM
│
├── Signup.java           # Page 1: Personal details form
├── Signup2.java          # Page 2: Additional information
├── Signup3.java          # Page 3: Account type + card + PIN
├── Login.java            # Login window
│
├── Deposit.java          # Deposit money
├── Withdrawl.java        # Withdraw money
├── FastCash.java         # Quick withdrawal options
├── BalanceEnquiry.java   # Check account balance
│
├── Conn.java             # JDBC connection class
├── Main_Class.java       # Main ATM menu
│
└── README.md             # Project documentation






🛠️ Technology Used
Java (JDK 23)
Java Swing / AWT – Graphical User Interface
JDBC – Database connectivity
MySQL / MariaDB – Database management
IntelliJ IDEA / VS Code – IDE
🗄️ Database Structure
Database Name: bankmanagementsystem
You will need the following tables:
signup
Stores user personal details.
signup2
Stores additional details (religion, income, etc.)
signup3
Stores account type, card number, and PIN
login
Stores card number + PIN for authentication.
bank
Stores all transactions (deposit, withdrawal, fast cash)
🚀 Getting Started
1. Clone the Repository
git clone https://github.com/LZYSHADOWMONARCH/BANKINGMANAGEMENTSYSTEM.git
2. Import the Project
Open in IntelliJ, Eclipse, or VS Code.
3. Configure MySQL
Create the database:
CREATE DATABASE bankmanagementsystem;
4. Update Database Credentials
Inside Conn.java, update:
String username = "root";
String password = "your_mysql_password";
5. Run the Project
Run Login.java to start the application.
📷 Screenshots (Optional)
You can attach UI screenshots here (login, signup, ATM menu, etc.)
📘 How It Works
➤ New User
Completes all 3 signup pages → Gets Card Number + PIN → Can log in.
➤ Existing User
Logs in → ATM menu → Perform transactions.
➤ Transactions
Every deposit + withdrawal is stored in bank table and balance is calculated dynamically.
🤝 Contributing
You can contribute by:
Fixing bugs
Improving UI
Adding new features like fund transfer, mini statement, etc.
📝 License
This project is for educational purposes. Free to modify and use.
