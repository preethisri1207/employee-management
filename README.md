# Enterprise Java CRUD Application

A production-style Spring Boot CRUD application with layered architecture.

## Features
- Spring Boot 3
- REST API
- CRUD Operations
- JPA + H2 Database
- DTO Layer
- Exception Handling
- Validation
- Maven Project Structure

## Run the Application

```bash
mvn spring-boot:run
```

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/employees | Create employee |
| GET | /api/employees | Get all employees |
| GET | /api/employees/{id} | Get employee by ID |
| PUT | /api/employees/{id} | Update employee |
| DELETE | /api/employees/{id} | Delete employee |

## Sample JSON

```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "department": "Engineering"
}
```

## H2 Console
Visit:
http://localhost:8080/h2-console