Below is a **fully copy-paste ready `README.md`** written inside a **single Markdown box**, with **clean formatting, clear sections, and recruiter-friendly language**.

You can **directly paste this into `README.md`** of your **HardwareProManager** repository.

---


# 🛠️ HardwareProManager

**HardwareProManager** is a desktop-based **Windows Forms (WinForms)** application developed as an **academic subject learning project**.  
The system is designed to assist a **small hardware shop owner** in managing customers, sales, and billing using a **LocalDB-backed database**.

This project focuses on strengthening fundamentals of **C# WinForms**, **ADO.NET**, **2-Tier Architecture**, and **database connectivity**.

---

## 📌 Project Objective

- Apply classroom concepts to a real-world style application
- Understand desktop application development using WinForms
- Learn database connectivity with LocalDB and ADO.NET
- Build confidence in CRUD-based business applications

---

## 🔑 Key Features

- Windows desktop application using **WinForms**
- **LocalDB** for structured data storage
- Customer management (Add / View / Update)
- Sales and billing management
- Invoice & report generation using **SAP Crystal Reports**
- Simple login system for **Shop Owner**
- **2-Tier Architecture** implementation
- Beginner-friendly and academically focused design

---

## 🛠 Technology Stack

| Layer | Technology |
|-----|-----------|
| Language | C# |
| UI Framework | Windows Forms (WinForms) |
| Database | SQL Server LocalDB |
| Data Access | ADO.NET |
| Architecture | 2-Tier |
| Reporting | SAP Crystal Reports |
| IDE | Visual Studio |

---

## 🏗 Application Architecture

This project follows a **2-Tier Architecture**:

### 1️⃣ Presentation Layer
- Windows Forms UI
- Handles user input and display logic

### 2️⃣ Data Layer
- SQL Server LocalDB
- ADO.NET for database operations

This separation improves readability and maintainability.

---

## 🗄 Database Overview

- LocalDB is used as the backend database
- Tables include:
  - Customers
  - Sales
  - Billing
  - Item-related data
- CRUD operations are implemented using parameterized queries

---

## ⚙ Installation & Setup

### Prerequisites
- Windows OS
- Visual Studio 2019 or later
- SQL Server LocalDB
- SAP Crystal Reports for Visual Studio

### Setup Steps

1. Clone the repository:
```bash
   git clone https://github.com/HardikDharaiya/HardwareProManager.git
```

2. Open the solution file: Hardware Pro Manager.sln


3. Install **SAP Crystal Reports for Visual Studio 2019**

4. Add Crystal Report references:

   * Right-click **References**
   * Add references related to **Crystal Reports**

5. Update connection strings in:

   * `Sales.cs`
   * `Items.cs`
   * `ViewBills.cs`
   * `Customers.cs`
   * `Billing.cs`

6. Update report paths:

   * `CrystalReport1.rpt`
   * `CrystalReport4.rpt`
   * Related `.xml` data files

7. Build and run the project

---

## 👤 User Role

* **Shop Owner**

  * Login access
  * Manage customers and sales
  * Generate bills and reports

> Note: This is a **low-level academic project**, not a commercial product.

---

## 📚 Learning Outcomes

* WinForms UI development
* ADO.NET database connectivity
* LocalDB usage
* 2-Tier architecture understanding
* Report generation using Crystal Reports
* Real-world desktop application workflow

---

## 🤝 Contributors

* **Hardik Dharaiya**
* **Mohit Ahir**

---

## ⚠ Disclaimer

This project is created **strictly for educational purposes** as part of academic coursework.
It is intended to demonstrate fundamental development concepts.

---

## ⭐ Support

If you find this project useful:

* Give it a ⭐ star
* Explore other repositories on my GitHub profile

---

## 🚀 Future Enhancements 

* Improved UI/UX
* Role-based authentication
* Input validation & exception handling
* Migration to Web or Client-Server architecture


