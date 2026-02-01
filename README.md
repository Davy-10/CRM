# Django CRM Web Application

A Customer Relationship Management (CRM) web application built using Django, focused on managing agents and their leads through database-driven workflows.


## Getting Started

To run this project you will need to set your environment variables.

1. Create a new file named `.env` inside the `djcrm` folder
2. Copy all of the variables inside `djcrm/.template.env` and assign your own values to them
3. Run the following command so the environment variables file is read:
     `export READ_DOT_ENV_FILE=True` 

## Features

- User authentication and role-based access
- Lead creation, assignment, and status tracking
- Agent–lead relationship management
- Database-backed CRUD operations
- Django templates and static file integration


## Project Note:

This project was customized and analyzed to understand real-world Django CRM architecture, including authentication flows, relational data modeling, and production-style project structure.


## Tech Stack

- Backend: Python, Django
- Frontend: HTML, CSS, JavaScript
- Database: SQLite (development)
- Tools: Git, Virtual Environment, python-dotenv

