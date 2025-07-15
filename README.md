# 🗓️ Internal Resource Booking System

This is a simple web application developed in ASP.NET Core MVC that allows employees to view and book shared company resources such as meeting rooms, vehicles, and equipment. The system helps prevent double-bookings and improves resource management.

---

## 🚀 Features

- Add, edit, and delete resources (e.g., rooms, cars, etc.)
- Book resources for specific time slots
- Prevent overlapping bookings (conflict logic)
- View upcoming bookings per resource
- Responsive UI with Bootstrap styling
- Server-side and client-side form validation

---

## 🛠️ Technologies Used

- ASP.NET Core MVC
- C#
- Entity Framework Core (with SQL Server)
- Razor Views
- Bootstrap 5

---

## ⚙️ Getting Started

### 1. Clone the Repository

If you're using Git:

```bash
git clone (https://github.com/Granny14/InternalBookingSytem.git)

Due to system limitations, I was unable to generate a physical backup of the database (e.g., .sql or .bak file).  
However, the application can recreate the database automatically using Entity Framework Core Migrations.

To recreate the database:
1. Run `dotnet ef database update` in the terminal
2. Ensure `appsettings.json` is correctly configured for your local database
