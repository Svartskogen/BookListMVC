# BookListMVC
Simple CRUD ASP.NET Core MVC App

[Take a look at the Razor pages implementation here](https://github.com/Svartskogen/BookListRazor)

## Stack
- .NET Core 3.1
- MSSQL Server and Entity Framework Core for database and mapping
- Bootstrap and Razor syntax for views
- Javascript for data table handling

## CRUD
WIP
- Create:
- Read:
- Update:
- Delete:

## Building and usage:
You need Visual Studio 2019, .Net Core 3.1 and a MS SQL Server 2019 instance running in your local machine.

For database setup you need to:
- Set the DefaultConnection Server in appsettings.json to your local instance (see: Server=DESKTOP-F19K3V3, change DESKTOP... with your local instance name)
- Create the database and book table using the Package Manager Console in Visual Studio:
  - ```PM> add-migration DatabaseInit```
  - ```PM> update-database```
