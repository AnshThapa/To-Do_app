# Django To-Do List Application (Prototype)

A simple **To-Do List Application** built with Django and Django Rest Framework (DRF). This prototype allows users to register, log in, and manage their tasks using basic CRUD operations. The app is designed to be modular, extensible, and ready for future enhancements.
<sub> I am still new with django and git so I just made from what I understand, I will upload a better version soon</sub>
---

## Features

- **User Authentication:**
  - Register, Login, and Logout functionality.
  - User-specific task management.

- **Task Management:**
  - Add new tasks with optional descriptions, due dates, and tags.
  - Update task status (e.g., mark tasks as "Completed").
  - Delete tasks from the list.

- **Tags:**
  - Associate tags with tasks for better categorization.
  - Add multiple tags separated by commas.

- **REST API Integration:**
  - Expose CRUD APIs for tasks and tags.
  - Secure API endpoints using authentication.

---

## Prerequisites

To set up and run this project locally, ensure you have the following installed:

- Python (>=3.9)
- Django (>=4.0)
- SQLite (default database)
- Required Python packages (listed in `requirements.txt`)

---

## Installation and Setup

1. Unzip the main folder 
2. Install the requirements using
   >pip install -r requirements. txt
3. Run the app by running 'python manage.py runserver' on your cmd line.
