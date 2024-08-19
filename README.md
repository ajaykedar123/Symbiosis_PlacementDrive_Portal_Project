# PlacementDrive_Portal

## Overview
The PlacementDrive_Portal is a web application designed to streamline the placement process for colleges. The portal includes functionalities for students, companies, and college admins to manage placement activities effectively.

## Features
- **Student Module**: Students can register, update their profiles, and view upcoming placement drives.
- **Company Module**: Companies can register, post job drives, and view student applications.
- **Admin Module**: Admins can manage student records, company drives, and oversee the entire placement process.

## Models

### 1. Student Model
The Student model handles all the details related to students participating in the placement drive.

- **Fields:**
  - `Id`: Primary key, unique identifier for each student.
  - `FirstName`: Student's first name.
  - `LastName`: Student's last name.
  - `Email`: Student's email address (unique).
  - `MobileNo`: Student's contact number.
  - `Gender`: Gender of the student.
  - `CourseName`: The course the student is enrolled in.
  - `Year`: The academic year of the student.
  - `PRN`: Permanent Registration Number, unique to each student.
  - `Password`: Encrypted password for login.
  
- **Key Features:**
  - Registration and login.
  - Profile management.
  - View upcoming placement drives.
  - Apply for placement drives.

### 2. Company Model
The Company model handles details related to companies participating in the placement process.

- **Fields:**
  - `CompanyId`: Primary key, unique identifier for each company.
  - `CompanyName`: Name of the company.
  - `HRName`: Name of the HR representative.
  - `Address`: Address of the company.
  - `DriveDate`: Date of the placement drive.
  - `Location`: Location of the placement drive.
  - `Position`: Job position offered by the company.

- **Key Features:**
  - Company registration.
  - Post and manage placement drives.
  - View student applications.

### 3. Admin Model (College Admin Portal)
The Admin model manages the overall functionality of the portal, including student and company management.

- **Fields:**
  - `AdminId`: Primary key, unique identifier for each admin.
  - `AdminName`: Name of the admin.
  - `Email`: Admin's email address.
  - `Password`: Encrypted password for login.

- **Key Features:**
  - Manage student records.
  - Manage company details and placement drives.
  - Oversee the entire placement process.
  - Generate reports.

## Setup Instructions

### Prerequisites
- .NET Framework (version x.x)
- SQL Server or any other compatible database
- Visual Studio or any other .NET IDE

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ajaykedar123/Symbiosis_PlacementDrive_Portal_Project.git
