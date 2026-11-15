
# Dormitory Management System

**Course:** C# Programming  
**University:** Astana IT University  
**Group:** 2501  
**Student:** Zainab

## 1. Project Description

The Dormitory Management System is a web-based application developed to simplify and organize dormitory operations. It provides a centralized platform for managing residents, rooms, room allocations, payments, maintenance requests, and reports.

The system is designed to reduce manual work, improve data organization, and make dormitory management more efficient.

## 2. Project Objectives

- Manage resident information.
- Organize dormitory rooms and their capacity.
- Assign residents to available rooms.
- Record and manage payments.
- Submit and track maintenance requests.
- Generate reports and display important statistics.

## 3. Main Features

- **Dashboard:** Displays an overview of dormitory activities and statistics.
- **Residents Management:** Add, search, and manage resident records.
- **Rooms Management:** Create rooms, define capacity, and monitor available beds.
- **Allocations Management:** Assign residents to rooms and manage check-outs.
- **Payments Management:** Record and track resident payments.
- **Maintenance Management:** Create, search, and update maintenance requests.
- **Reports & Statistics:** Display occupancy information, collected payments, monthly payment reports, and maintenance statistics.

## 4. Technologies Used

- C#
- .NET 10
- Blazor Web App
- Razor Components
- Entity Framework Core
- SQLite
- HTML
- CSS

## 5. Database

The application uses SQLite as its database and Entity Framework Core for database operations.

The database contains the following main entities:

- Resident
- Room
- Allocation
- Payment
- MaintenanceRequest

## 6. Individual Contribution

This project was developed individually by Zainab.

My responsibilities included:
- Designing and developing the application interface.
- Creating the database and data models.
- Implementing database operations using Entity Framework Core.
- Developing all management sections.
- Implementing search, filtering, validation, and reporting features.
- Testing the application's main functionality.

## 7. How to Run the Project

1. Open the project folder in Visual Studio Code.
2. Open the terminal in the project directory.
3. Run the following command:

   ```bash
   dotnet restore
   ```

4. Update the database:

   ```bash
   dotnet ef database update
   ```

5. Start the application:

   ```bash
   dotnet run
   ```

6. Open the localhost URL displayed in the terminal.

## 8. Project Status

The Dormitory Management System is an individual academic project developed as part of the C# Programming course at Astana IT University.
