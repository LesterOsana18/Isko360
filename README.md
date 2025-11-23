# Isko360: DOST-SEI Scholar Management and Tracking System

Isko360 is a centralized, database-driven platform designed to modernize the management, monitoring, and tracking of DOST-SEI scholars at PUP Main Campus. It addresses the current problems of fragmented data, manual processes, and delayed communication between scholars and administrators.

---

## 📌 Project Overview

The DOST-SEI Scholarship Program supports thousands of scholars nationwide, yet its management at the university level remains largely manual and disconnected.  
**Isko360** aims to solve this by providing:

- A unified database system for scholar records  
- Real-time allowance and compliance tracking  
- Secure document verification and storage  
- Automated notifications and monitoring  
- Role-based access control for administrators and scholars  

This system will help reduce administrative delays, prevent data inconsistencies, and improve transparency in scholarship management.

---

## 🎯 Objectives

The main goal of Isko360 is to develop a **centralized scholarship management system** that:

1. Centralizes scholar information into a single normalized database  
2. Automates allowance monitoring and disbursement tracking  
3. Improves academic compliance and report verification  
4. Enhances communication through database-driven notifications  
5. Ensures data security through RBAC and audit trails  
6. Supports scalable growth for future batches of scholars  
7. Provides a user-friendly web interface connected to real-time data  

---

## 📂 Key Features

- **Scholar Management Module**  
  Stores personal profiles, academic standing, scholarship details, and department information.

- **Allowance Tracking System**  
  Tracks stipend release, allowance status, and transaction history.

- **Academic Compliance Monitoring**  
  Handles submission of periodic reports, certified grades, and compliance checks.

- **Document Management**  
  Upload, review, and track supporting documents (COR, grades, etc.).

- **Notification System**  
  Sends alerts for allowance releases, missing documents, and compliance status.

- **Admin & Role-Based Access**  
  Ensures system security and data privacy using role-based permissions.

---

## 🗄️ Database Design

The system follows relational database design principles with proper normalization, entity relationships, and integrity enforcement.

### Core Entities:
- USER
- USER_PROFILE
- ADMIN
- SCHOLAR
- SCHOLARSHIP
- COLLEGE
- DEPARTMENT
- PERIODIC_REPORT
- DOCUMENT
- SUBMISSION_COMPLIANCE
- ALLOWANCE
- ACADEMIC_STANDING
- NOTIFICATION

Each entity has defined primary and foreign keys to ensure data consistency.  
Audit fields, role-based access, and constraints are implemented to maintain integrity and security.

---

## 🔐 Data Security Features

- Role-Based Access Control (RBAC)
- Secure authentication and password hashing
- Audit trail for administrative actions
- Compliance with Data Privacy Act of 2012 principles
- Encrypted sensitive information

---

## 🛠️ Technologies (Planned / Suggested)

- **Database:** MySQL / PostgreSQL  
- **Backend:** Node.js / PHP  
- **Frontend:** React / HTML-CSS-JS  
- **Server:** Cloud-based / Local SQL Server  
- **Version Control:** Git & GitHub  

---

## 👥 Target Users

- DOST-SEI Scholars (PUP Main Campus)
- Scholarship Administrators
- Coordinators and Reviewers

---

## 📊 System Scope

The system focuses on **DOST-SEI scholars of PUP A. Mabini Campus only**, with future scalability for other campuses.

---

## 📑 Documentation Included

- Business Rules  
- Entity Relationship Diagram (ERD)  
- Data Dictionary  
- Database Schema  
- DBA Management Tasks  
- Use Case Scenarios  

---

## 👨‍💻 Contributors

Group 2 – BSCS 4-3  
- Juliana Caedo  
- Novelle Lyn Estrella  
- Lester Osana  
- Jeremias Pablo  
- John Paul Viado  

---

## 📜 License

This project is developed for academic purposes under  
**COMP 018: Database Administration**  
Polytechnic University of the Philippines  
First Semester, A.Y. 2025–2026

---

## 🚀 Future Enhancements

- Mobile application integration  
- Multi-campus deployment  
- API integration with DOST-SEI system  
- Advanced analytics dashboard  
