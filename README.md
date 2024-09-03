# WebSocket_FastApi_Chatbot
This is a chatbot which streams outputs to all users through broadcasting via sockets. 
# FastAPI Chat Application Setup Guide

## Prerequisites

- Python 3.8 or higher
- MySQL Server
- pip (Python package installer)

## Database Setup

### Start MySQL Server
Ensure that your MySQL server is running.

### Create a Database
1. Log into your MySQL shell.
2. Execute the following SQL command to create a new database:

   ```sql
   CREATE DATABASE gainzai;

### Create and Activate a Virtual Environment

#### For Windows:
```bash
python -m venv venv
.\venv\Scripts\activate
```

#### For MacOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### Install Dependencies
Install all required Python packages using:

```bash
pip install -r requirements.txt
```

## Configuration

### Environment Variables
1. Copy the provided `.env.txt` file to a new `.env` file using:

   ```bash
   cp .env.txt .env
   ```

2. Open the `.env` file and update it with your MySQL credentials and any other required settings.

## Running the Application

### Run Your Application (`main.py`)

Start the FastAPI server with:

```bash
uvicorn main:app --reload
```

This command starts the server with live reloading enabled, which is suitable for development.

### Access the Application

Open a web browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to view the application.

---

These detailed instructions should guide you smoothly through setting up and running your FastAPI Chat Application.
```

This Markdown format should help you keep your setup instructions well-organized and easy to follow.
