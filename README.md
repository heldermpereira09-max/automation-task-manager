# Automation Task Manager

A Flask web application for creating, tracking, updating and deleting automation tasks through a simple web interface and REST API.

## Features

- Create automation tasks
- Add task descriptions
- View all tasks
- Mark tasks as completed
- Reopen completed tasks
- Delete tasks
- REST API endpoints
- SQLite database persistence
- Responsive web interface

## Technologies

- Python
- Flask
- Flask-SQLAlchemy
- SQLAlchemy
- SQLite
- HTML
- CSS
- JavaScript
- REST API

## API Endpoints

### Get all tasks

```text
GET /tasks
```

### Create a task

```text
POST /tasks
```

Example JSON:

```json
{
  "title": "Automate weekly report",
  "description": "Generate and process a weekly automation report."
}
```

### Update a task

```text
PUT /tasks/<task_id>
```

Example JSON:

```json
{
  "status": "completed"
}
```

### Delete a task

```text
DELETE /tasks/<task_id>
```

## Installation

Clone the repository:

```bash
git clone https://github.com/heldermpereira09-max/automation-task-manager.git
cd automation-task-manager
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
.\venv\Scripts\Activate.ps1
```

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open in your browser:

```text
http://127.0.0.1:5000
```

## Project Purpose

This project was created as a practical demonstration of Python automation, Flask development, database integration, REST APIs and web application development.

## Author

Helder Pereira

