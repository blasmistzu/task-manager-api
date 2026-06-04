# Task Manager API

A REST API built with FastAPI, SQLAlchemy and SQLite for managing users and tasks.

## Features

- Create users
- Get all users
- Create tasks
- Get all tasks
- Update task status
- Delete tasks
- SQLite database integration
- Automatic API documentation with Swagger

## Technologies

- Python
- FastAPI
- SQLAlchemy
- SQLite
- Uvicorn

## Project Structure

```
task-manager-api/
│
├── main.py
├── database.py
├── models.py
├── schemas.py
├── tasks.db
├── requirements.txt
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/blasmistzu/task-manager-api.git
```

Move into the project directory:

```bash
cd task-manager-api
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the API:

```bash
python -m uvicorn main:app --reload
```

## API Documentation

After starting the server, open:

```txt
http://127.0.0.1:8000/docs
```

Swagger UI will be available for testing all endpoints.

## Endpoints

### Users

- POST `/users`
- GET `/users`

### Tasks

- POST `/tasks`
- GET `/tasks`
- PUT `/tasks/{task_id}`
- DELETE `/tasks/{task_id}`

## Author

Lucas (blasmistzu)