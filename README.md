📌 CredWise – Loan Management System

CredWise is a web-based Loan Management Application built with ASP.NET Core MVC and Entity Framework Core.
It provides a seamless platform for customers to apply for loans, track repayments, and download statements, while enabling admins to manage customers, KYC, loan approvals, and categories.

🚀 Features
👤 Customer

Register and sign in securely.

Complete KYC verification for account activation.

Apply for loans once KYC is approved.

View all loans and detailed repayment history.

Make loan repayments until completion.

Download loan statements.

👨‍💼 Admin

Approve or reject customer KYC requests.

Review and manage loan applications.

View all customers and their loan details.

Create, modify, or delete loan categories.

Generate and download bank statements.

🛠️ Tech Stack

Backend: ASP.NET Core MVC (C#)

Database: Entity Framework Core (Code-First Migrations)

Frontend: Razor Views (HTML, CSS, JavaScript)

Configuration: appsettings.json for DB & environment configs

⚙️ Installation & Setup

1) Clone the repository

git clone https://github.com/YOUR-USERNAME/CredWise.git
cd CredWise


2) Restore dependencies

dotnet restore


3) Update database (apply migrations)

dotnet ef database update


4) Run the application

dotnet run
