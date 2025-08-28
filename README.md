# 💳 Banking System (Java Swing + JDBC)

A **modern Banking System** built using **Java Swing** for the GUI and **JDBC with MySQL** for database management.  
This project demonstrates **real-world banking operations** like creating accounts, deposits, withdrawals, and balance management in a sleek desktop application.  

---

## 🚀 Features

- 🔐 **User Account Management** – Create and manage bank accounts securely.  
- 💰 **Deposit & Withdraw** – Perform real-time transactions.  
- 📊 **Balance Inquiry** – Check account balances instantly.  
- 🗂 **Transaction Records** – Track and store operations in a database.  
- 🎨 **Java Swing UI** – Stylish and interactive desktop interface.  
- 🛠 **JDBC + MySQL** – Persistent storage of customer and account data.  

---

## 🖼 Pages   
- **Login Page**  
- **Dashboard**  
- **Transaction Window**  

---

## 🏗 Project Structure  

```
📂 BankingSystem
 ┣ 📜 Accounts.java            # Model class for accounts
 ┣ 📜 AccountsDAO.java         # Data Access Object (DAO) for account operations
 ┣ 📜 BankingSystem.java       # Main application (GUI + logic)
 ┣ 📜 ConnectionProvider.java  # Database connection manager
 ┗ 📂 resources                # (Optional) icons, images, etc.
```

---

## ⚙️ Tech Stack  

- **Language:** Java  
- **UI:** Swing  
- **Database:** MySQL (via JDBC)  
- **Architecture:** MVC (Model - View - Controller)  

---

## 🛠 Setup & Installation  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/banking-system.git
   cd banking-system
   ```

2. **Configure Database (MySQL)**  
   - Create a database:  
     ```sql
     CREATE DATABASE bankdb;
     ```
   - Update `ConnectionProvider.java` with your MySQL credentials:
     ```java
     String url = "jdbc:mysql://localhost:3306/bankdb";
     String user = "root";
     String password = "yourpassword";
     ```

3. **Compile and Run the Project**  
   ```bash
   javac *.java
   java BankingSystem
   ```

---

## 🔮 Future Enhancements  

- 🌐 Online Banking Portal (Spring Boot + REST API)  
- 📱 Mobile Banking App Integration  
- 🔔 Notifications (Email/SMS Alerts)  
- 🛡️ Enhanced Security with AES/RSA Encryption  

---

## 👨‍💻 Author  

**Pratik Roy**  
📌 MTech | Computer Science | NIT Durgapur  
🚀 Passionate about Java, Distributed Systems, and FinTech solutions  

---
