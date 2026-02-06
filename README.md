This is a simple open source .NET CORE 10.0 Minimal API's application.   

Built using ASP.NET Core Minimal APIs (WebApplication / route handlers).

Designed and developed as proof of concept (POC) to demonstrate routing, request handling, and CRUD patterns in a minimal API style.

# TodoApi — ASP.NET Core Minimal API (Tutorial Project)

This repository contains a **Minimal API** built with **ASP.NET Core**, based on the Microsoft Learn tutorial **“Create a Minimal API with ASP.NET Core”**. Minimal APIs are designed to create HTTP APIs with minimal dependencies and boilerplate—great for microservices and lightweight services. 

## What this API does

This project implements a simple **To-Do** REST API with CRUD operations, exposing the following routes:

- `GET /todoitems` — Get all to-do items
- `GET /todoitems/complete` — Get completed items
- `GET /todoitems/{id}` — Get an item by ID
- `POST /todoitems` — Create a new item
- `PUT /todoitems/{id}` — Update an existing item
- `DELETE /todoitems/{id}` — Delete an item

This application is developed (and updated / changed in future) on Visual Studio 2026 Enterprise edition.

API Endpoints are below: 

| Method | Route                 | Description               |
| -----: | --------------------- | ------------------------- |
|    GET | `/todoitems`          | Get all to-do items       |
|    GET | `/todoitems/complete` | Get to-do items whose status is: completed |
|    GET | `/todoitems/{id}`     | Get an item by ID         |
|   POST | `/todoitems`          | Add a new item            |
|    PUT | `/todoitems/{id}`     | Update an existing item   |
| DELETE | `/todoitems/{id}`     | Delete an item            |


# Project Structure and Code files: 
# TodoApi/
    
            ├── obj/                         # Build artifacts (auto-generated)
                        
            ├── Properties/
            │   └── launchSettings.json      # Debug & launch configurations
            
            ├── Program.cs                   # Main application entry (minimal API endpoints)
            
            ├ ── Todo.cs                      # Domain model (Todo item)

            ├── TodoItemDTO.cs               # DTO file (Todo item)

            ├── TodoApi.http                 # File where HttpVerb requests are created/ generated when Endpoints explorer is clicked. 

            ├── TodoDb.cs                    # EF Core in-memory database context

            ├── appsettings.json             # Configuration settings (optional)

            ├── appsettings.Development.json # Development config overrides (optional)

            ├── TodoApi.csproj               # .NET project file

            ├── README.md                   # Project overview and setup instructions (this file) 

            └── .gitignore                   # Files/folders to ignore in git


Learn more / References

Microsoft Learn tutorial: Tutorial: Create a Minimal API with ASP.NET Core

Minimal APIs quick reference

ASP.NET Core APIs overview (Minimal APIs vs controller-based)
