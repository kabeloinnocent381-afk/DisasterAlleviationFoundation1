DisasterAlleviationFoundation
Project Overview

DisasterAlleviationFoundation is a web application built with ASP.NET Core MVC that allows users to:

Register and login securely

Submit disaster reports

Track donations

Manage volunteer tasks

View a dashboard summarizing activities

This project is designed to demonstrate user authentication, CRUD operations, SQL database integration, and session management.

Features

User Registration & Login

Secure user authentication with hashed passwords

Role-based access (Volunteer, Admin)

Dashboard

Total users, reports, donations, and volunteers

Recent disaster reports displayed

Disaster Reporting

Users can submit new disaster reports

Status tracking for reports

Donations

Users can donate resources

Donation history tracked per user

Volunteering

Volunteers can view assigned tasks (if implemented)

Technologies Used

ASP.NET Core MVC

C#

Entity Framework Core

SQL Server / Azure SQL

Bootstrap / HTML / CSS

Visual Studio 2022

Azure DevOps (Git repository and CI/CD Pipelines)

Setup & Installation

Clone the repository

git clone https://dev.azure.com/yourname/DisasterAlleviationFoundation/_git/DisasterAlleviationFoundation


Open in Visual Studio 2022

Open the .sln file

Configure Database

Update the connection string in appsettings.json:

"ConnectionStrings": {
    "DefaultConnection": "Server=tcp:YOUR_SERVER.database.windows.net,1433;Initial Catalog=DisasterDB;User ID=YOUR_USERNAME;Password=YOUR_PASSWORD;Encrypt=True;TrustServerCertificate=False;Connection Timeout=30;"
}


Apply Migrations

Open Package Manager Console

Run:

Update-Database


Run the Application

Press F5 in Visual Studio

The app will start in your browser
