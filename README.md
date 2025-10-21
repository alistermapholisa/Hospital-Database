# Mnene Hospital Database Project 🏥

This project demonstrates the development and implementation of a relational database system for **Mnene Hospital**. The primary goal was to transition the hospital from an inefficient, risk-prone **paper-based record-keeping** system to a streamlined **digital database** solution using **SQLite**.

This project was completed as part of the **ALX Academy** curriculum.

---

## 🎯 Problem Statement

Mnene Hospital faced significant operational challenges due to its reliance on a paper-based file system, including:
* **Slow Record Access:** Delays in retrieving patient data, slowing down treatment and diagnosis.
* **Administrative Inefficiency:** High time consumption for administrative staff in managing physical files.
* **Data Risk:** High probability of data loss, misplacement, or degradation of records.

## ✨ Solution

The solution was the design and implementation of a normalized **SQLite database** to centralize all hospital data—including **Patients**, **Doctors**, **Appointments**, and **Admissions**. This system is designed to:
* **Streamline Operations:** Enable quick and accurate data retrieval.
* **Improve Coordination:** Provide a single source of truth for all departments.
* **Enhance Data Integrity:** Reduce errors associated with manual data entry and storage.

---

## 🛠️ Technology Stack

| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Database** | **SQLite** | The core relational database engine used for its simplicity, efficiency, and embeddability. |
| **Tool** | **DB Browser for SQLite** | Used for database creation, running SQL queries, and visualizing the data structure. |
| **Language** | **SQL** (Structured Query Language) | Used for defining the schema, inserting data, and performing complex data retrieval and analysis. |

---

## 📂 Project Structure

This repository contains the essential files and documentation for the project:

| File/Folder | Purpose |
| :--- | :--- |
| `Mnene_Hospital_Database.db` | The **final SQLite database file** containing all tables and data (or the `.sql` script to create it). |
| `Tasks.png` | The **original project requirements/tasks** used to drive the data analysis. |
| `SQL_Queries_Documentation.md` | A file containing the **SQL scripts** used to solve the required tasks (like finding averages, counting patients, and joining tables). |
| `Screenshots/` | A folder containing images that **demonstrate the query execution and results** for the required tasks. |
| `README.md` | This file: providing an overview of the project. |

---

## 🔎 Key SQL Tasks Demonstrated

The project successfully executed several key data analysis tasks, showcasing the ability to query complex, real-world data:

| Category | Task Demonstrated | SQL Concept | Screenshot Example |
| :--- | :--- | :--- | :--- |
| **Admissions** | Finding the **average length of stay** for discharged patients. | Date functions (`JULIANDAY`), `AVG()`, `WHERE` clause, and Null checking. | `Screenshot 2025-10-17 133601.png` |
| **Appointments** | Counting the **number of appointments per doctor**. | `COUNT()` aggregate function and `GROUP BY` clause. | `Screenshot 2025-10-17 131733.png` |
| **Doctors** | Finding doctors based on a specific specialisation (e.g., "Cardiologist"). | `SELECT` and `WHERE` clauses for data filtering. | `Screenshot 2025-10-17 130712.png` |
| **Admissions** | Listing all **currently admitted patients**. | Simple `SELECT` and `WHERE` filtering based on status. | `Screenshot 2025-10-17 133005.png` |

---

## ▶️ Getting Started

To explore this project:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/Mnene-Hospital-Database.git](https://github.com/YourUsername/Mnene-Hospital-Database.git)
    ```
2.  **Download SQLite Browser:** Install a tool like **DB Browser for SQLite** to view and query the database file.
3.  **Open the Database:** Open the `Mnene_Hospital_Database.db` file in the SQLite browser.
4.  **Review the Queries:** Examine the `SQL_Queries_Documentation.md` file or run the queries yourself in the "Execute SQL" tab to replicate the results shown in the `Screenshots/` folder.
