# Secure File Management System

This is a C++ based project implementing:
- User authentication
- OTP-based login (2FA)
- Role-based access control
- File encryption and decryption
- Threat detection for malicious files


# 🔐 Secure File Management System (C++)

## 📌 Overview
The Secure File Management System is a C++-based application designed to provide secure file handling using multiple layers of protection. It ensures that only authorized users can access, modify, or delete files.

---

## 🚀 Features

### 🔑 1. User Authentication
- Login using username and password
- Passwords are stored securely using hashing

### 🔐 2. OTP-Based Two Factor Authentication (2FA)
- Generates a one-time password after login
- Adds an extra layer of security

### 🛡️ 3. Role-Based Access Control
- Supports roles like **Admin**, **User**, and **Guest**
- Controls access to file operations based on role

### 📁 4. File Operations
- Create, read, and delete files
- Deletion allowed only for authorized users

### 🔒 5. File Encryption & Decryption
- Files are encrypted before storage
- Prevents unauthorized access to data

### 📊 6. Logging & Security Checks
- Logs user activities
- Detects suspicious or invalid operations

---

## 🛠️ Technologies Used
- C++
- File Handling (fstream)
- Basic Security Techniques (Hashing, Encryption)
- Standard Libraries

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Secure-File-Management-System.git
