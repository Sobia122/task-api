# Task API

A simple CRUD API built with FastAPI.

## Features

- Create Task
- Read Tasks
- Update Task
- Delete Task
- Swagger UI Documentation

## Installation

```bash
pip install -r requirements.txt
```

## Run

```bash
uvicorn main:app --reload
```

Open:

- API: http://127.0.0.1:8000
- Swagger: http://127.0.0.1:8000/docs

## Endpoints

| Method | Endpoint |
|--------|----------|
| GET | / |
| GET | /health |
| GET | /tasks |
| GET | /tasks/{task_id} |
| POST | /tasks |
| PUT | /tasks/{task_id} |
| DELETE | /tasks/{task_id} |
