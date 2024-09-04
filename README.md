# Loan-lending-system
Angular Project:- Loan lending system

# Loan Lending System

## Project Overview

This Angular project implements a **Loan Lending System** designed to manage and display loan details for users. The application includes several screens for viewing loan types, managing user loans, and handling loan details through an intuitive and user-friendly interface.

## Features

- **Screen 1: Loan Types**
  - Displays a scrollable list of loan types in a simple table.
  - Default loan types include: Personal Loans, Home Loans, Student Loans, Auto Loans.
  - No functionality to add or edit loan types.

- **Screen 2: Lending a Loan**
  - **User Detail Section**: Captures user details including Full Name, Date of Birth (DOB), Comments, and Mobile Number with specific validation rules.
  - **Loan Type Section**: Allows selection of a loan type from a dropdown list.
  - **Loan Detail Section**: Captures Principal Amount, Rate, and Time in months for calculating Simple Interest (SI) and Total Amount (A). Includes fields for displaying calculated values in readonly mode.
  - Buttons: **Cancel**, **Calculate**, and **Save** for handling form actions.

- **Screen 3: User List with Loan Details**
  - Displays a list of users with their loan details in a table format.
  - Utilizes two custom Angular pipes:
    - `dateFormat`: Transforms dates from `dd-mm-yyyy` to `dd Month, YYYY`.
    - `formatText`: Converts loan types to title case.
  - Displays a formula view in the "Calculation" column.

- **Screen 4: Loan Detail View**
  - Similar to the lending form but in readonly mode, pre-filled with values.
  - Includes **Back** and **Delete** buttons for navigation and record deletion.

- **Screen 5: Edit User Loan**
  - Similar to the lending form but pre-filled with existing values for editing.
  - Includes **Back** and **Update** buttons for navigation and record updating.

## Installation

To get started with the project, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/loan-lending-system.git
   cd loan-lending-system



