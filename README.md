# Hospital Management System (Database Backend)

This repository contains the backend architecture and a highly optimized relational database design for a comprehensive Hospital Management System. The system manages core healthcare workflows, including patient admissions, doctor schedules, appointments, and medical billing records.

## 🚀 Key Features

- **Optimized Relational Schema:** Engineered and deployed a structured 7-table relational database to manage complex hospital data integrity.
- **3NF Normalization:** Strictly applied Third Normal Form (3NF) standards to eliminate data redundancy, prevent anomalies, and minimize storage footprints.
- **Relational Integrity:** Utilizes strongly defined Primary Keys, Foreign Keys, and cascading constraints to ensure transactional stability and secure data relationships.
- **Advanced Querying:** Pre-configured with efficient SQL queries for complex data retrieval, including patient medical histories and real-time staff availability.

## 🛠️ Tech Stack

- **Database Engine:** SQL / Relational Database Management System (RDBMS)
- **Design Methodology:** 3NF Normalization, Entity-Relationship (ER) Modeling
---

## 🎯 Objectives of the Project
- Maintain information about doctors, nurses, departments, patients, and procedures.  
- Manage doctor affiliations with different departments.  
- Keep records of patient diagnoses, prescriptions, and medical history.  
- Provide efficient and quick retrieval of data for analysis and reporting.  
- Eliminate redundancy and ensure data integrity through **primary and foreign key constraints**.  

---

## 🗂️ Database Design

The database contains the following **7 tables**:

1. **Physician** – stores details of doctors working in the hospital.  
2. **Department** – stores all the departments and their heads.  
3. **Affiliated_with** – stores the relationship between physicians and departments.  
4. **Nurse** – stores details of nurses working in the hospital.  
5. **Patient** – stores patient personal details and their primary physician.  
6. **Patient_Diagnosis** – stores patient diagnosis information and prescriptions.  
7. **Procedures** – stores details of various hospital procedures/tests.  

---

## 🛠️ Technology Used
- **Database**: MySQL  
- **Language**: SQL  
- **Features**:  
  - Table creation with constraints (Primary Key, Foreign Key).  
  - Data insertion for realistic hospital scenarios.  
  - Queries to retrieve and analyze hospital data.  

---


