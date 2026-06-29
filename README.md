# Task Manager

A simple Python project for managing tasks with a CLI and a REST API.

## Features

- Add, update, delete, and list tasks
- Mark tasks as completed
- User authentication
- Task storage with a database
- Email reminders
- API support with FastAPI

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the API:
   ```bash
   uvicorn task_manager_pro.api.main:app --reload
   ```

3. Or use the CLI:
   ```bash
   pip install -e .
   task-manager --help
   ```

## Project Structure

- `task_manager_pro/` - main application code
- `tests/` - test files
- `docs/` - documentation

## Notes

This project is a personal learning project built with Python, FastAPI, SQLAlchemy, and authentication features.
