# Placement Management System

## Project Overview

This project automates the Placement Management System using Salesforce Flows, Validation Rules, and Apex Trigger.

## Features

- Student Management
- Job Management
- Application Management
- Offer Letter Management
- Automatic Application Date
- Email Notification
- Validation Rules
- Apex Trigger for Duplicate Application Prevention

---

## Requirements Solved Using Flow

1. Automatically populated the Application Date when a new Application was created.
2. Sent an email notification to the Placement Officer when a new Application was submitted.
3. Automatically created an Offer Letter record when the Application Status changed to **Selected**.

---

## Requirements Solved Using Validation Rules

1. Prevented students with CGPA below the required minimum from applying.
2. Prevented the Application Date from being later than the Job Closing Date.
3. Ensured mandatory fields (Student and Job) were not left blank.

---

## Requirements Solved Using Apex

1. Prevented duplicate applications by checking whether the same student had already applied for the same job.
2. Displayed an error message if a duplicate application was detected.

---

## Why These Solutions Were Chosen

### Flow
Flow was used because it is a declarative (no-code) automation tool that is easy to maintain. It was used for:
- Auto-filling the Application Date
- Sending Email Notifications
- Creating Offer Letter records

### Validation Rules
Validation Rules were used to maintain data quality by preventing invalid records from being saved.

### Apex Trigger
Apex Trigger was used to implement duplicate application checking because it can query existing records and apply custom business logic before saving.

---

## Technologies Used

- Salesforce Developer Org
- Flow Builder
- Validation Rules
- Apex Trigger
- Custom Objects
- Lookup Relationships

---

## Project Outcome

The Placement Management System successfully automates:

- Application Date population
- Email notifications
- Duplicate application prevention
- Offer Letter creation
- Data validation

using Salesforce declarative tools and Apex.

---

## Screenshots

The **Screenshots** folder contains:

- Flow 1 – Application Date
- Flow 2 – Email Notification
- Flow 3 – Offer Letter Creation
- Apex Trigger
- Validation Rules
- Successful Application Record
- Email Notification
- Offer Letter Record
