# Task Manager REST API

A production-grade REST API built with Java Spring Boot and PostgreSQL.

## Tech Stack
- **Java 25** + **Spring Boot 3.5**
- **PostgreSQL** — persistent database
- **Maven** — build tool
- **Spring Data JPA** — database layer

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/tasks | Get all tasks |
| POST | /api/tasks | Create a task |
| PUT | /api/tasks/{id} | Update a task |
| DELETE | /api/tasks/{id} | Delete a task |

## How to Run

1. Clone the repo
```bash
git clone https://github.com/sbharaththota/task-manager-api.git
```
2. Create PostgreSQL database named `taskmanager`

3. Run the app
```bash
mvn spring-boot:run
```

4. Test it
```bash
curl http://localhost:8080/api/tasks
```

## Author
Sai Bharath Thota — [LinkedIn](https://linkedin.com/in/saibharaththota)