# Library-Management-System-C-
![Made with C++](https://img.shields.io/badge/Made%20with-C++-blue?style=for-the-badge&logo=cplusplus)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Console-lightgrey?style=for-the-badge)

---

## 🔹 Project Overview
This is a beginner-friendly *Library Management System* built in *C++* using *Object-Oriented Programming (OOP)* concepts.  

It allows:
- *Admins* to add, view, and delete books  
- *Users* to search, borrow, and return books  
- Data is managed using *C++ STL containers* (unordered_map, vector, etc.)  

This project is *console-based* and is ideal for learning *C++ OOP + Data Structures*.

---

## 🔹 Features
✅ *Admin Features*
- Add books  
- Delete books  
- View all books  

✅ *User Features*
- Register new user  
- Borrow books  
- Return books  
- Search books by title  

✅ *Technical Highlights*
- *Language:* C++17  
- *OOP Concepts:* Classes, structs, encapsulation  
- *Data Structures Used:*  
  - unordered_map → store books & users  
  - vector → manage borrowed books list  
  - optional → safe retrieval of users  

---

## 🔹 File Structure
LibraryMS/
├── main.cpp # Entry point
├── Book.h/.cpp # Book struct
├── User.h/.cpp # User struct
├── Library.h/.cpp # Core library logic
├── Menu.h/.cpp # User/Admin menu system
├── Makefile # (optional) easy build
├── LICENSE # License file (MIT)
├── CONTRIBUTING.md # Contribution guidelines
└── README.md # Project documentation
