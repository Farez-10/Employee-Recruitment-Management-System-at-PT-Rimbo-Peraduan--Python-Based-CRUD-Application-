# Employee Recruitment Management System at PT Rimbo Peraduan  
*(Python-Based CRUD Application)*

## 📌 Project Overview
This project is a **console-based Employee Recruitment Management System** developed using **Python**, designed to simulate an internal recruitment data management system at **PT Rimbo Peraduan**.

The application enables HR administrators to manage applicant data efficiently through **Create, Read, Update, and Delete (CRUD)** operations, complete with **input validation**, **authentication**, and **change history tracking**.  
This project was developed as part of a **capstone / portfolio project** to demonstrate fundamental Python programming and data management skills.

---

## 🎯 Business Understanding
In recruitment processes, accurate and structured applicant data management is essential to support fair evaluation and effective decision-making.  
This system addresses the need for a **simple, reliable, and well-organized recruitment data management tool**, suitable for internal HR operations.

### **Business Benefits**
- Centralized recruitment data management  
- Improved data accuracy through validation rules  
- Reduced administrative errors  
- Transparent tracking of applicant recruitment status  
- Audit trail through recorded data change history  

---

## 👥 Target Users
This application is intended for:
- HR Administrators  
- Recruitment Officers  
- HR Data Entry Staff  

who are responsible for managing applicant records and monitoring recruitment progress at PT Rimbo Peraduan.

---

## 🚀 Application Features

### 🔐 Authentication & Security
- Admin login system with limited login attempts  
- User session tracking for data modification history  

### ➕ Create (Add Applicant Data)
- Automatic applicant ID generation  
- Mandatory field validation (no empty input)  
- Email and phone number format validation  
- Confirmation before saving data  

### 📄 Read (View & Search Data)
- Display all applicant data in a structured table  
- Search applicant records by ID  
- Clear and readable data output  

### ✏️ Update (Modify Applicant Data)
- Edit specific applicant attributes  
- Controlled recruitment status updates  
- Automatic logging of all changes (before & after values)  

### ❌ Delete (Remove Applicant Data)
- Delete single or multiple applicant records  
- Confirmation prompts to prevent accidental deletion  

### 🕒 Change History Tracking
- Records every data modification with:
  - Date & time of change  
  - Admin username  
  - Applicant ID  
  - Modified field  
  - Previous and updated values  

---

## 🗂️ Data Structure
The application uses **Python Lists and Dictionaries** to store recruitment data in memory.

### **Applicant Data Fields**
- Applicant ID  
- Full Name  
- Position Applied  
- Education  
- Work Experience  
- Contact Number  
- Email Address  
- Recruitment Status  

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Standard Library:**  
  - `datetime` (for logging change history)

---

## ▶️ How to Run the Application

1. Ensure **Python 3.x** is installed on your system  
2. Run the application using the command below:
   ```bash
   python Employee Recruitment Management System at PT Rimbo Peraduan (Python-Based CRUD Application).py
