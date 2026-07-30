# Placement Management System

## Project Overview

This project automates a Placement Management System using Salesforce Flow Builder and Validation Rules.

---

## Requirements Solved Using Flow

1. Automatically populated Application Date.
2. Sent email notification to the Placement Officer.
3. Automatically created an Offer Letter when Status changed to Selected.

---

## Requirements Solved Using Validation Rules

1. Prevented students with CGPA below the required minimum.
2. Prevented Application Date from being after the Job Closing Date.
3. Made Student and Job mandatory.

---

## Requirements That Needed Apex

None.

All project requirements were completed using Salesforce Flow and Validation Rules.

Apex would only be required for:
- External REST API integrations
- Complex calculations
- Bulk data processing

---

## Why These Solutions Were Chosen

### Flow

Used because it is declarative, easy to maintain, and requires no code.

### Validation Rules

Used to maintain data quality and prevent invalid records.

### Apex

Not used because Flow was sufficient for the project.

---

## Features

- Student Management
- Job Management
- Application Management
- Offer Letter Management
- Automatic Application Date
- Email Notification
- Offer Letter Creation
