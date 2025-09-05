# Cat API Prototype
## Decription
Service built with **FastAPI** for managing information about cats.  
Implements basic CRUD operations with validation via **Pydantic**.  
---
## API Endpoints

| Method | Endpoint     | Description       |
|--------|-------------|-------------------|
| POST   | /cats/      | Create a new cat  |
| GET    | /cats/      | Get all cats      |
| GET    | /cats/{id}  | Get cat by ID     |
| PATCH  | /cats/{id}  | Update cat by ID  |
| DELETE | /cats/{id}  | Delete cat by ID  |
--- 
## Installing
1. Clone the repository
```
git clone https://github.com/Kushon/cat-api-prototype.git
cd project_cats
```
2. Install the dependency
```
uv sync
```
---
## Run the application
```
uv run uvicorn main:app
```

