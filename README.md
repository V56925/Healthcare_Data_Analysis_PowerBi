🔷 1. Project Title:
Pharmaceutical Management System Using SQL

🎯 2. Objective:
To design and analyze a comprehensive pharmaceutical system that manages:

Medicine inventory

Patient & doctor data

Prescriptions

Sales transactions

Supplier information
Also includes automation through triggers and stored procedures.

🧰 3. Tools & Technologies Used:
Database: MySQL

Tools: MySQL Workbench

Language: SQL

📊 4. Dataset & Tables:
Created multiple interrelated tables, such as:

Medicines, Patients, Doctors, Prescriptions, Sales, Suppliers

Helper tables: Prescription_Details, Medicine_Suppliers, Restock_Alerts, etc.

Key data handled:

Prices, stock levels, and expiry dates of medicines

Prescription and sales records

Patient demographics

Supplier and medicine relationships

📌 5. SQL Tasks & Business Queries:
Includes 19 SQL queries for insights like:

Low-stock or expired medicines

Top-selling medicines & revenue generation

Doctor-wise and city-wise analysis

Identifying unauthorized sales

Same-day prescription & purchase

Late purchases post-prescription

Prescribed but not sold medicines

Medicines sold without a prescription

Doctors with no activity

🔁 6. Triggers & Stored Procedures:
Triggers:

Reduce stock after a sale

Update Last_Prescribed_Date

Insert restock alert if stock drops below threshold

Stored Procedures:

Add prescription (with JSON logic)

Generate bill

List patients per doctor

Move expired medicines to another table

Sales summary by category

📈 7. Insights / Outcomes:
Automated alerts reduce manual inventory tracking

Improved business intelligence from sales & prescription data

Trigger-based automation ensures data consistency

Streamlined operations through reusable procedures
