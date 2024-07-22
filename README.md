# Medical Cooperative Information System

## Project Overview

This project involves developing a database system for a medical cooperative. The system is theoreticaly can be used by a group of doctors to manage patient information and track medical visits. The database includes:

- **Patient Information**: Name, gender, date of birth, and home address.
- **Medical Visits**: Records of visits including date, location, symptoms, diagnosis, and prescriptions.
- **Medications**: Details about medications, including name, administration method, expected effects, and side effects.

## Key Features

### 1. Query Functions
- **Count Visits on a Specific Date**:
  Retrieves the number of medical visits on a given date.
- **Count Patients with a Specific Disease**:
  Determines the number of patients diagnosed with a particular disease.
- **Retrieve Medication Side Effects**:
  Fetches the side effects of a specified medication.
- **Add New Medication**:
  Allows for the addition of new medications with their properties.

### 2. Database Design
- **Tables**:
  - `patients`: Stores patient information.
  - `visits`: Records details of medical visits.
  - `diagnoses`: Contains information about diagnoses.
  - `medications`: Manages medication details.
- **Relationships**:
  Establishes relationships between tables to maintain data integrity and support complex queries.

### 3. Triggers and Procedures
- **Triggers**:
  Implemented to ensure cascading changes in related tables.
- **Stored Procedures**:
  Includes procedures for performing common operations and queries.

## Technologies Used
- **Database Management System**: [Specify the DBMS used, e.g., MySQL, PostgreSQL]
- **SQL**: For writing queries, triggers, and stored procedures.

## Why This Project is Relevant
This project demonstrates essential skills in:
- **Database Design**: Creating and structuring tables to store and manage data effectively.
- **SQL Query Writing**: Crafting queries for data retrieval, manipulation, and reporting.
- **Automation**: Using triggers and stored procedures to automate and maintain data integrity.
  
These skills are crucial for a Data Scientist, as they involve handling real-world data, implementing complex database functionalities, and ensuring data accuracy and efficiency.

## Project Outcome
The database system provides a robust solution for managing medical data, supporting various operations and queries needed by healthcare professionals. This project reflects the ability to handle data at different levels and is a valuable addition to a portfolio. Detailed information is laid out in a word document, you can view it by following the [Link](MCIS.docx).
