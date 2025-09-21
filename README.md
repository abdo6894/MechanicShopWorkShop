
# MechanicShopWorkShop 🛠️🚗

**MechanicShopWorkShop** is a full-featured car repair workshop management system built with **.NET 9**, following **Clean Architecture** principles. The project leverages **Blazor (WASM/Server)** for the frontend and **Docker** for easy containerized deployment.  

---

## 📂 Project Structure (Clean Architecture)

The solution is organized into layers for better separation of concerns and maintainability:

##

- **Domain** → Core entities (Customer, Vehicle, Order, etc.) and domain rules.  
- **Application** → Business rules, CQRS commands/queries, validation, MediatR pipelines.  
- **Infrastructure** → Database access (EF Core), logging, email, external services.  
- **API** → ASP.NET Core Web API exposing endpoints to clients.  
- **BlazorUI** → Frontend implemented with Blazor (Server/WASM).  

---

## ⚡ Features

- ✅ **Clean Architecture** with clear separation of concerns.  
- ✅ **CQRS + MediatR** for request/response handling.  
- ✅ **Entity Framework Core** for data persistence.  
- ✅ **Blazor** frontend (Server or WebAssembly).  
- ✅ **Dockerized deployment** using Docker Compose.  
- ✅ **Unit & Integration Tests** for maintainability.  

---

## 🐳 Run with Docker

1. Make sure **Docker** is installed on your machine.  
2. From the root directory, run:  

```bash
docker-compose up --build
