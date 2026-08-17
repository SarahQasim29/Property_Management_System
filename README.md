# Real Estate Property Management System

A web-based **Real Estate & Property Management System** developed to simplify the management of properties, tenants, leases, payments, maintenance requests, and property-related activities.

The system provides a centralized platform for property owners, agents, tenants, and administrators to manage real estate operations efficiently while maintaining structured and secure data through a SQL Server database.

## 🚀 Features

* 🏠 **Property Management**

  * Add, update, view, and delete property records
  * Manage property addresses, prices, owners, and availability status
  * Display properties available for sale or rent

* 👤 **User Management**

  * User registration and account management
  * Client and owner information management
  * Agent management

* 📝 **Lease Management**

  * Create and manage lease records
  * Track lease duration and payment information
  * Support lease renewal operations

* 💰 **Payment & Rent Management**

  * Record property payments and rent
  * Track financial transactions
  * Validate payment dates

* 🔧 **Maintenance Management**

  * Create and track maintenance requests
  * View maintenance request details
  * Manage property maintenance activities

* 💬 **Comments**

  * Users can create comments related to properties
  * View and manage property comments

* 📊 **Database Management**

  * Relational database design using SQL Server
  * Stored procedures
  * Database views
  * Primary and foreign key indexing
  * Unique indexes
  * Database triggers
  * Structured relationships between properties, owners, clients, leases, payments, and other entities

## 🛠️ Technologies Used

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* C#
* ASP.NET MVC

### Database

* Microsoft SQL Server
* SQL

The project uses ASP.NET MVC and C# for backend/server-side functionality, JavaScript for frontend interactivity, and SQL Server for storing and managing property, tenant, and financial information.

## 🗄️ Database

The database was designed as a relational database to maintain structured and consistent information across the system.

Major entities include:

* Property
* Owner
* Agent
* Client
* Register
* Lease
* Payment
* Rent
* Buy
* Supplier
* Comment
* Property Maintenance

The database handles information such as property details, ownership, lease agreements, payments, user registration, comments, and maintenance requests.

### SQL Features Implemented

The project demonstrates several SQL Server features, including:

* Stored Procedures
* Views
* Indexes
* Unique Indexes
* Clustered Indexes
* Non-Clustered Indexes
* Triggers

Example database operations include inserting owners and properties, retrieving available properties, joining property and lease information, and automatically updating property status after a sale.

## ⚙️ Database Automation

The system uses SQL Server triggers for automated database operations, including:

* Automatically marking a property as **Sold** after a purchase
* Automatically handling lease duration
* Preventing payments with future dates
* Automatically updating related property prices when required

## 📐 System Design

The project includes database and software design documentation covering:

* Workflow Diagram
* Use Case Diagram
* Sequence Diagram
* Entity Relationship Diagram (ERD)

The database design follows a relational approach with defined entities, attributes, primary keys, foreign keys, relationships, and constraints.

## 📸 System Screens

The system includes interfaces for:

* Home Page
* Creating Payments
* Creating Rent Records
* Deleting Records
* Creating Comments
* Viewing Comments
* Creating New Comments
* Viewing Maintenance Request Details
* Deleting Maintenance Requests

## 👩‍💻 My Contribution

I contributed to multiple areas of the project, including:

* Frontend development using HTML, CSS, and JavaScript
* Backend development using ASP.NET MVC and C#
* SQL Server database development
* Database design and implementation
* Database integration
* Testing and system functionality

The project report identifies my contributions across **frontend, backend, and database development**.

## 🎯 Project Scope

The system focuses on managing:

* Property listings
* Property ownership
* Tenants and clients
* Lease agreements
* Rent and payments
* Property purchases
* Maintenance requests
* Comments
* Financial information
* Property-related records

The database is designed with emphasis on **data integrity, efficiency, scalability, and security**.

## 📌 Project Objective

The main objective is to provide an online platform that reduces the complexity of traditional property management by bringing property-related information and operations into one centralized system.

The system aims to improve efficiency, reduce manual work, simplify property transactions, and provide a better experience for property owners, agents, tenants, and clients.

## 🎓 Academic Project

**Course:** Database Management System (CSL 220)
**University:** Bahria University Karachi Campus
**Department:** Software Engineering
**Class:** BSE – 4A
**Project:** Real Estate & Property Management System
