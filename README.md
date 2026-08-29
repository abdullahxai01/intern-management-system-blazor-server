# Intern Management System

A web-based Intern Management System developed using Blazor Server,
C#, .NET, Entity Framework Core, SQL Server, and Bootstrap.

The system is designed to provide a centralized platform for managing
intern records, internship-related information, and user access.

## 📌 Overview

The Intern Management System is a web application developed to simplify
and organize the management of interns within an organization.

Instead of maintaining intern information manually, the system provides
a centralized application where authorized users can manage intern
records and perform different operations through a web-based interface.

The project demonstrates full-stack application development using the
Microsoft .NET ecosystem and Blazor Server.

## 🎯 Objectives

The main objectives of this project are:

- Develop a web-based intern management system
- Centralize intern information
- Implement CRUD operations
- Store and manage data using SQL Server
- Use Entity Framework Core for database operations
- Build a responsive user interface
- Implement user authentication and authorization
- Provide role-based access to system functionality
- Practice C# and .NET development
- Develop a maintainable web application

## ✨ Features

### 👨‍💼 Intern Management

The system provides functionality for managing intern records.

Users can perform operations such as:

- Add new interns
- View intern information
- Update intern records
- Delete intern records
- Manage internship-related information

### 🔐 Authentication & Authorization

The application can restrict access to different areas of the system
based on authenticated users and their permissions.

This helps protect intern information and administrative functionality.

### 👥 Role-Based Access

Different users can be assigned different roles and permissions.

For example:

```text
Administrator
     │
     ├── Manage Interns
     ├── Manage Users
     └── Manage System Data

Staff / Supervisor
     │
     ├── View Interns
     └── Manage Assigned Information
