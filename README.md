This is a simple open source .NET CORE 10.0 Minimal API's application.  It is work in progress (more work pending) and new code will be checked in to this repo soon. 

Built using ASP.NET Core Minimal APIs (WebApplication / route handlers).

Designed as a learning project to demonstrate routing, request handling, and CRUD patterns in a minimal API style.

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


Learn more / References

Microsoft Learn tutorial: Tutorial: Create a Minimal API with ASP.NET Core

Minimal APIs quick reference

ASP.NET Core APIs overview (Minimal APIs vs controller-based)
