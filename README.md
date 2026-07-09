# 📚 Library Management System (Java)

![Java](https://img.shields.io/badge/Java-17%2B-orange?style=for-the-badge&logo=java)
![OOP](https://img.shields.io/badge/OOP-Concepts-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)

A **console-based Library Management System** developed using **Core Java**. This project demonstrates Object-Oriented Programming (OOP), Collections Framework, Exception Handling, and Java Date & Time API by simulating real-world library operations such as adding books, issuing books, returning books, searching books, and calculating overdue fines.

---

# ✨ Features

- 📖 Add new books
- 👤 Register library members
- 📚 Issue books to members
- 🔄 Return issued books
- 💰 Automatic overdue fine calculation
- 🔍 Search books by title
- ✍️ Search books by author
- 📋 Display all books
- ✅ Display available books
- 📕 Display issued books
- 👥 Display registered members
- ⚠️ Custom exception handling for invalid operations

---

# 🛠 Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Collections Framework
- Exception Handling
- Java Date & Time API (`java.time`)
- HashMap
- ArrayList

---

# 📚 Java Concepts Implemented

| Concept | Implementation |
|---------|----------------|
| Encapsulation | Book & Member classes |
| Inheritance | StudentMember extends Member |
| Polymorphism | Method overriding (`toString()`) |
| Collections | ArrayList & HashMap |
| Exception Handling | Custom Exceptions |
| Date & Time API | LocalDate & ChronoUnit |
| Utility Classes | DateUtil & FineCalculator |

---

# 📂 Project Structure

```text
LIBRARY-MANAGEMENT-SYSTEM/
│
├── Book.java
├── Member.java
├── StudentMember.java
├── Library.java
├── Main.java
├── BookNotFoundException.java
├── BookAlreadyIssuedException.java
├── BookNotIssuedException.java
├── InvalidMemberException.java
├── FineCalculator.java
├── DateUtil.java
└── README.md
```

---

# ▶️ How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/karupothulamalliswari3112/LIBRARY-MANAGEMENT-SYSTEM.git
```

### 2️⃣ Open Project

Open the project in:

- VS Code
- IntelliJ IDEA
- Eclipse

### 3️⃣ Compile

```bash
javac *.java
```

### 4️⃣ Run

```bash
java Main
```

---

# 🖥 Sample Output

## Main Menu

```text
===== LIBRARY MANAGEMENT SYSTEM =====

1. Add Book
2. Add Member
3. Issue Book
4. Return Book
5. Search Book by Title
6. Search Book by Author
7. Display All Books
8. Display Available Books
9. Display Issued Books
10. Display All Members
0. Exit
```

---

## Issue Book

```text
Book "The Alchemist" issued to member M201.
Due Date: 23-07-2026
```

---

## Return Book

```text
Book "The Alchemist" returned.
Returned on time.
No Fine.
```

---

## Fine Calculation

```text
Book "The Alchemist" returned.
Overdue!
Fine: Rs. 25.0
```

---

# 📸 Screenshots

> *(Upload screenshots later.)*

| Menu | Issue Book | Return Book | Fine |
|------|------------|-------------|------|
| Coming Soon | Coming Soon | Coming Soon | Coming Soon |

---

# 🚀 Future Enhancements

- 💾 File Handling
- 🗄 Database Integration (MySQL)
- 🖥 GUI using JavaFX or Swing
- 🌐 Web-based Library Management System
- 📊 Reports & Analytics
- 🔐 Login Authentication
- 📧 Email Notifications

---

# 🎯 Learning Outcomes

This project helped me understand:

- Object-Oriented Programming
- Java Collections Framework
- Exception Handling
- Java Date & Time API
- Clean Code Structure
- Real-world Project Development

---

# 👩‍💻 Author

**Karupothula Malliswari**

B.Tech – Computer Science & Engineering

GitHub: https://github.com/karupothulamalliswari3112

---

⭐ **If you found this project useful, consider giving it a Star!**
