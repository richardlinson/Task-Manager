# Task Manager

A lightweight task manager built with Flask, Flask-SQLAlchemy, and SQLite. Add
tasks, mark them complete or incomplete, and delete them from a simple web
interface.

## Requirements

- Python 3.8 or later
- pip

## Setup

From the project directory, create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

Install the dependencies:

```powershell
python -m pip install -r requirements.txt
```

## Run

```powershell
python app.py
```

Open the local address printed by Flask in your browser. The SQLite database is
created automatically when the app starts. Local database files are not tracked
by Git.
