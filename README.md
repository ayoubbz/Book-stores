## BookStores

BookStores is a Blazor Server app using ASP.NET Core as back-end service and MSSQL for database. 

It has code samples for Authentication, Authorization, DataGrid, Database operations....and much more. 

![Demo_App]

## Installation

### Prerequisites

- IDE - Visual Studio or VS Code
- Framework - .NET Core 3.0 or Greater
- Database - SQL Express/Server

### Clone

- Clone this repo to your local machine using `[https://github.com/ayoubbz/Book-stores]`

### Setup

> BookStores Database
- Create database `BookStoresDB` in SQL Express/Server
- To create the data run SQL query from `BookStores/Database/GenerateData.sql` 

> BookStores Web API
- Open project `BookStores/BookStoresWebAPI/BookStoresWebAPI.sln`
- Run Project through Visual Studio/Terminal
- Go to `https://localhost:5001/swagger` or `https://localhost:44315/swagger`

> Blazor Server App
- Open Project ` BookStores/BlazorServerApp/BlazorServerApp.sln`
- Run Project through Visual Studio/Terminal
- Go to `https://localhost:6001/` or `https://localhost:44391/`
- Click on login. You should get logged in as like `exemple@gmail.com`
