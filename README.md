# Placement Management System

## Project Overview

This project automates the Placement Management System using Salesforce Flow Builder and Validation Rules.

## Features

- Student Management
- Job Management
- Application Management
- Offer Letter Management
- Automatic Application Date
- Email Notification
- Offer Letter Creation
- Validation Rules

## Requirements Solved Using Flow

1. Automatically populated the Application Date when a new Application was created.
2. Sent an email notification to the Placement Officer when a new Application was submitted.
3. Automatically created an Offer Letter record when the Application Status changed to **Selected**.

## Requirements Solved Using Validation Rules

1. Prevented students with CGPA below the required minimum from applying.
2. Prevented the Application Date from being later than the Job Closing Date.
3. Ensured mandatory fields (Student and Job) were not left blank.

## Requirements That Needed Apex

None for this project.

All the required functionality was successfully implemented using Salesforce Flow and Validation Rules.

Apex would be useful for:
- Calling external REST APIs
- Complex business logic
- Large-scale data processing
- Advanced calculations across multiple objects

## Why These Solutions Were Chosen

### Flow
Flow was used because it is a declarative (no-code) automation tool. It is easy to build, maintain, and supports field updates, email notifications, and record creation.

### Validation Rules
Validation Rules were used to ensure data quality and prevent invalid records from being saved.

### Apex
Apex was not required because all project requirements were achieved using declarative Salesforce features.

## Screenshots

All screenshots are available in the **Screenshots** folder of this repository.
