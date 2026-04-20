# 📚 Library Management System (Java)

## 📌 Overview
This project is a simple Java console-based application that manages book records. It allows users to input multiple book details and displays them in a structured format along with a unique book code.

The project demonstrates basic Object-Oriented Programming (OOP) concepts and array handling in Java.

---

## ⚙️ Features
- Accepts multiple book records from user input
- Stores book details using a class and array
- Displays formatted book information
- Generates a unique book code for each entry
- Simple and beginner-friendly implementation

---

## 🧠 Concepts Used
- Classes and Objects  
- Constructors  
- Arrays  
- String Manipulation (`split`)  
- Loops (`for loop`)  
- Input Handling using `Scanner`  

---

## 🏗️ Class Structure
```
book Class
   ├── name (String)
   ├── author (String)
   ├── type (String)
   ├── price (String)
   ├── buy (String)
   ├── Constructor
   └── details() Method

project_2_library_management_system (Main Class)
   └── Handles user input and displays output
```

---

## 🖥️ How It Works
1. The program asks for the number of books.
2. User enters book details in the format:
   ```
   name,author,type,price,buy
   ```
3. The system stores each book in an array.
4. Each book is displayed with:
   - Unique Book Code  
   - Name  
   - Author  
   - Type  
   - Price  
   - Status (Available/Purchased)

---

## 💻 Sample Input
```
2
Java Basics,James Gosling,Programming,500,Available
Python Guide,Guido van Rossum,Programming,600,Purchased
```

## 📤 Sample Output
```
Book code = 100251
 Details:
Book Name   : Java Basics
Author Name : James Gosling
Book Type   : Programming
Book Price  : 500
Book Status : Available
..................................

Book code = 100252
 Details:
Book Name   : Python Guide
Author Name : Guido van Rossum
Book Type   : Programming
Book Price  : 600
Book Status : Purchased
..................................
```

---

## 📂 Project Structure
```
Library-Management-System/
│── project_2_library_management_system.java
```

---

## 🚀 How to Run
1. Compile the program:
   ```
   javac project_2_library_management_system.java
   ```
2. Run the program:
   ```
   java project_2_library_management_system
   ```

---

## 📌 About
A Java console application that manages book records using arrays, classes, and user input, and displays structured book information.

---

## ✍️ Author

KARTHIKEYAN K U
