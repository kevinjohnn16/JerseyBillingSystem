Perfect 👍
Here is a **clean, professional, full README.md** for your **Jersey Billing System (SQLite Version)**.
You can copy-paste this directly into GitHub.

---

# 👕 Jersey Billing System

### Java Mini Project – Object Oriented Programming

---

## 📌 Project Description

The **Jersey Billing System** is a Java-based mini real-world application developed using Object-Oriented Programming principles. The application allows users to enter a team name and select a sport to generate the jersey price.

The system uses:

* ✅ Java Swing for GUI
* ✅ Abstraction, Inheritance, and Polymorphism
* ✅ Custom Exception Handling
* ✅ Multithreading
* ✅ SQLite Database (JDBC) for data storage

The program automatically creates a database file (`jersey.db`) and stores team and price details permanently.

---

## 🎯 Objective

The objective of this project is to:

* Implement core OOP concepts in Java
* Develop a user-friendly GUI
* Handle invalid inputs using custom exceptions
* Demonstrate multithreading
* Integrate SQLite database using JDBC

---

## 🧠 Concepts Implemented

| Concept            | Implementation                                       |
| ------------------ | ---------------------------------------------------- |
| Abstraction        | `abstract class Jersey`                              |
| Inheritance        | `FootballJersey` and `CricketJersey` extend `Jersey` |
| Polymorphism       | `Jersey jersey = new FootballJersey()`               |
| Exception Handling | `InvalidTeamException`                               |
| Multithreading     | `BillThread extends Thread`                          |
| JDBC               | SQLite connection using `DriverManager`              |
| GUI                | Java Swing components                                |

---

## 🛠 Technologies Used

* Java (JDK 8+)
* Java Swing
* SQLite Database
* JDBC (sqlite-jdbc driver)
* VS Code

---

## 📂 Project Structure

```
JerseyBillingSystem
│
├── JerseyBillingSystem.java
├── lib
│   └── sqlite-jdbc-3.51.2.0.jar
└── jersey.db (auto-created)
```

---

## ▶️ How to Run the Project

### Step 1: Download SQLite JDBC Driver

Download from:
[https://github.com/xerial/sqlite-jdbc/releases](https://github.com/xerial/sqlite-jdbc/releases)

Place the `.jar` file inside the `lib` folder.

---

### Step 2: Compile (Windows)

```
javac -cp ".;lib/sqlite-jdbc-3.51.2.0.jar" JerseyBillingSystem.java
```

---

### Step 3: Run

```
java -cp ".;lib/sqlite-jdbc-3.51.2.0.jar" JerseyBillingSystem
```

---

## 🖥 Sample Input

Team Name: Argentina
Sport: Football

---

## 🖥 Sample Output

Team: Argentina | Price: ₹1200

Console:

```
Database Ready ✅
Generating bill...
Saved in DB: Argentina
Bill generated successfully!
```

---

## 🗄 Database Details

* Database File: `jersey.db`
* Table Name: `jerseys`
* Columns:

  * `team_name` (Primary Key)
  * `price`

The database is automatically created when the program runs.

---

## 📈 Future Enhancements

* Add more sports categories
* Generate printable bill (PDF)
* Add admin panel
* Display all stored teams
* Improve UI design

---

## 👨‍💻 Author

Kevin John Samuel
Jain J Kolady
Mini Project – Object Oriented Programming Using Java

---
![img1](https://github.com/kevinjohnn16/JerseyBillingSystem/blob/839db6aa1b2e13a6a2c51400336c61196ed71e13/Screenshot%202026-02-13%20194730.png)
![img2](https://github.com/kevinjohnn16/JerseyBillingSystem/blob/6d6f83d66966988ffba72425ae574057d15e501c/Screenshot%202026-02-13%20194803.png)
