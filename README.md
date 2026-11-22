# 🏥 Clinical Management System

A web-based Clinical Management System developed as part of my Bachelor's degree academic project. The application is designed to simplify everyday clinic operations by bringing patient management, appointment booking, prescription handling, pharmacy inventory, and billing into one system.

## 📌 Project Overview

The Clinical Management System provides different functionalities for administrators, patients, and pharmacy staff. Each user area supports specific tasks, helping organize clinic workflows and reduce the need for manual record management.

## ✨ Features

### 👨‍💼 Administration
- Manage staff information
- View and manage patient records
- View appointment bookings
- Manage prescriptions
- Access administrative pages

### 🧑‍⚕️ Patient Management
- Patient registration and login
- Book clinic appointments
- Generate appointment tokens
- View appointment history
- View prescribed medicines and prescriptions
- Change account password

### 💊 Pharmacy Management
- Add and manage medicines
- Update medicine information and stock
- View prescriptions
- Calculate medicine bills
- Check medicine availability
- Automatically update stock after billing

### 🔐 User Access
- Separate login flow for different user types
- Session-based user navigation
- Dedicated pages for administration, patients, and pharmacy operations

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| ASP.NET Web Forms | Web application development |
| C# | Server-side programming |
| ADO.NET | Database connectivity and operations |
| SQL Server Express | Database management |
| HTML5 | Web page structure |
| CSS3 | Styling and layout |
| JavaScript | Client-side functionality |

## 🏗️ Application Structure

The project follows an ASP.NET Web Forms structure, with separate pages and code-behind files for different application modules.

```text
clinical-management/
│
├── App_Data/
│   └── logintb.mdf
│
├── Scripts/
├── Styles/
├── images/
├── js/
│
├── Admin Pages
│   ├── adhome.aspx
│   ├── adstaff.aspx
│   ├── adpatient.aspx
│   ├── adbooking.aspx
│   └── adprescription.aspx
│
├── Patient Pages
│   ├── pthome.aspx
│   ├── ptbooking.aspx
│   ├── pthistory.aspx
│   └── ptprescription.aspx
│
├── Pharmacy Pages
│   ├── phhome.aspx
│   ├── phmedicine.aspx
│   ├── phmedupdate.aspx
│   ├── phprescription.aspx
│   └── phbillcalcu.aspx
│
├── Web.config
├── Global.asax
└── style.css
```

## 🚀 Getting Started

### Prerequisites

- Microsoft Visual Studio
- .NET Framework 4.0 compatible development environment
- SQL Server Express
- IIS Express or IIS

### Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/sukreth116/clinical-management.git
   ```

2. Open the project in Visual Studio.

3. Ensure SQL Server Express is installed and the database file inside `App_Data` is available.

4. Check the database connection strings in `Web.config` and update them according to your SQL Server configuration.

5. Build the application.

6. Run the project using Visual Studio or IIS Express.

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Developing database-driven web applications
- Working with ASP.NET Web Forms and C#
- Connecting applications to SQL Server using ADO.NET
- Performing database CRUD operations
- Implementing session-based login and user navigation
- Handling appointment booking and token generation
- Managing medicine inventory and billing workflows
- Understanding client-server application architecture

## 📚 Project Information

- **Project Type:** Bachelor's Degree Academic Project
- **Domain:** Healthcare / Clinic Management
- **Platform:** Web Application
- **Developer:** Sukreth O M

## 🔗 Repository

[View Source Code on GitHub](https://github.com/sukreth116/clinical-management)

---

*Developed for academic and learning purposes.*
