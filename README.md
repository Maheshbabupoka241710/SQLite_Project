# SQLite_Project
# Hospital Management Database (SQLite + Python)

This project implements a complete Hospital Management System using SQLite and Python. The goal of the system is to simulate real-world healthcare data and create a structured, normalized relational database suitable for SQL queries, analytics, and academic assessment.

The database was generated programmatically using Python, ensuring realistic values, consistent foreign keys, and clean table relationships. All tables include appropriate data types, constraints, and synthetic healthcare records such as patient profiles, clinical encounters, diagnostic events, procedure records, medication orders, and financial statements.

## Project Overview
The project models key hospital operations through multiple interconnected tables, representing the lifecycle of a patient’s journey in a healthcare environment. The database captures:
- Patient demographic details
- Clinical visit and encounter information
- Diagnostic test results
- Medical procedures
- Medication orders and prescriptions
- Billing and financial records

All data was created using Python and exported into SQLite for further inspection and analysis.

## Technologies Used
- SQLite
- Python (sqlite3, random, datetime, numpy)
- DB Browser for SQLite (used for validation and verification)

## Key Features
- Six fully normalized tables with primary and foreign key relationships
- Realistic synthetic hospital data designed for analytics and SQL practice
- Inclusion of nominal, ordinal, interval, and ratio data types
- Clean Python notebook with structured cells and comments
- Consistent data generation with validation using row counts
- Database suitable for academic submission and practical database learning

## Final Table Row Counts
The final row counts after successful data generation are listed below:

client_profiles          -> 310  
clinical_encounters      -> 1015  
diagnostic_events        -> 1411  
procedure_catalogue      -> 829  
medication_orders        -> 1303  
financial_statements     -> 1015  

These values confirm that the data was generated successfully and all foreign key constraints were preserved.

## Files Included
- Hosiptal_DataBase_Maheshbabu_poka.ipynb   (complete Python notebook)
- hospital.db                               (final SQLite database)
- appendix/                                  (screenshots from DB Browser)
- README.md                                  (project documentation)

## Appendix
A separate appendix folder contains screenshots taken from DB Browser to verify table creation, record counts, and schema correctness.

## Author
Mahesh Babu Poka
MSc Data Science
