# Flask REST API

A simple RESTful API built with Flask to manage users using SQLite and SQLAlchemy.

## Features
- `GET /api/users/` – List all users  
- `GET /api/users/<id>` – Get user by ID  
- `POST /api/users/` – Add a new user

## Setup

```bash
python -m venv .venv
source .venv/Scripts/activate
pip install -r requirement.txt
python create_db.py
python api.py