# 🐔 Poultry Farm Management System

**Status:** Active Development (Final Year Project)  
**Version:** 1.0.0

## 📖 Overview
The **Poultry Farm Management System** is a desktop-based software solution designed to address the challenges of manual record-keeping in the poultry industry. This system automates data entry for flock management, inventory control, and financial tracking, helping farmers reduce mortality rates through timely vaccination alerts and improve profitability through detailed financial analysis.

This project was developed in partial fulfillment of the requirements for the **BSc. in Computer Science** at Central University.

## 🚀 Key Features
*   **User Authentication:** Secure Role-Based Access Control (RBAC) for Admins and Farm Workers.
*   **Flock Management:** Track batches of birds (Broilers/Layers) from arrival to sale, including age and breed data.
*   **Daily Operations:** Log daily mortality, feed consumption, and water usage to calculate Feed Conversion Ratios (FCR).
*   **Health Module:** Automated scheduling and alerts for vaccinations and medication.
*   **Inventory Control:** Real-time tracking of feed bags and medicine with low-stock notifications.
*   **Financial Reporting:** Automated Profit & Loss statements, egg sales tracking, and expense management.
*   **Visualization:** Interactive dashboards and printable PDF reports using Crystal Reports.

## 🛠️ Technology Stack
*   **Language:** C# (Windows Forms / .NET Framework)
*   **Database:** MySQL (Relational Database Management)
*   **IDE:** Microsoft Visual Studio 2022
*   **Architecture:** Layered Architecture (UI, BLL, DAL) to ensure modularity and maintainability.
*   **Reporting:** SAP Crystal Reports / Microsoft RDLC.
*   **UI Framework:** WinForms (Customized for modern Look & Feel).

## ⚙️ Installation & Setup
1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/poultry-farm-management.git
    ```
2.  **Database Setup:**
    *   Open `MySQL Workbench` or `phpMyAdmin`.
    *   Import the `database_schema.sql` file located in the `Database` folder.
    *   Update the Connection String in `App.config` or the `DAL` class to match your local MySQL credentials.
3.  **Run the Application:**
    *   Open the solution file (`.sln`) in **Visual Studio 2022**.
    *   Restore NuGet Packages (specifically `MySql.Data`).
    *   Click **Start** to build and run.

## 👤 Author
**Frederick Sedem Fiagbedu**  
Department of Computer Science & IT  
Central University  
Index No: CSC/22/01/0653

---
*Disclaimer: This software is for academic purposes and demonstrates the application of Software Engineering principles in Agriculture.*
