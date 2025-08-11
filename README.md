# 🛒 Supermarket Management System

A **desktop-based application** developed in **Java** using **Swing** for the GUI and **MySQL** as the backend database.  
This project is designed to help supermarkets efficiently manage **products**, **employees**, and **categories** through a simple and intuitive interface.  
The system uses **JDBC** to interact with the MySQL database for data storage and retrieval.

---

## 📋 Features

### 🔑 Login System
- Only registered employees can access the system.

### 👨‍💼 Employee Management
- ➕ Add new employees  
- ✏️ Update employee passwords  
- ❌ Delete employee records  

### 📦 Product Management
- ➕ Add new products  
- ✏️ Update product quantities  
- ❌ Delete products  

### 🏷️ Category Management
- ➕ Add new categories  
- ❌ Delete categories  

### 💾 MySQL Database Integration
- Data persistence with MySQL database  
- Real-time add, update, and delete operations via JDBC  

---

## 🛠️ Technologies Used
- **Java (JDK 8+)**
- **Java Swing** – GUI creation
- **MySQL** – Data storage
- **JDBC** – Database interaction
- **NetBeans IDE** – Version 22

---

## 🗄️ Database Structure

### **employees** table:
| Column        | Description                |
|---------------|----------------------------|
| EID           | Employee ID                |
| EmployeeName  | Name of the employee        |
| Password      | Employee login password     |

### **products** table:
| Column        | Description                |
|---------------|----------------------------|
| PID           | Product ID                  |
| ProductName   | Name of the product          |
| Quantity      | Stock quantity available     |

### **categories** table:
| Column        | Description                |
|---------------|----------------------------|
| CID           | Category ID                 |
| Category      | Product category name        |

---

## ⚙️ How to Set Up

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/supermarket-management-system.git
