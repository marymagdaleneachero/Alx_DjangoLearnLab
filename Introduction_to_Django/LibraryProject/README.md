# 0: Introduction to Django Development Environment Setup

## Overview
This exercise introduces the basics of Django by guiding the setup of a Django development environment and the creation of a simple Django project. The goal is to understand the standard workflow involved in starting a Django project and running the development server.

---

## Objective
- Install Django using pip
- Create a Django project named **LibraryProject**
- Run the Django development server
- Explore the default Django project structure and core files

---

## Requirements
- Python installed on the system
- pip package manager

---

## Setup and Installation

### 1. Install Django
Django was installed in a virtual environment in the folder I intended to work with using pip:

```powershell
py -m pip install django

2. Create the Django Project

A new Django project named LibraryProject was created using:

django-admin startproject LibraryProject

3. Run the Development Server

The development server was started by navigating into the project directory and running:

cd LibraryProject
python manage.py runserver


The default Django welcome page was successfully displayed in the browser at:

http://127.0.0.1:8000/

Project Structure Exploration

The Django project comes with a default structure. Key files explored include:

manage.py
A command-line utility that allows interaction with the Django project, such as running the server and executing management commands.

settings.py
Contains configuration settings for the Django project, including installed applications, middleware, and database settings.

urls.py
Defines URL patterns and acts as the routing configuration for the project.

Repository Information

Repository: Alx_DjangoLearnLab

Directory: Introduction_to_Django

Status

✅ Django installed
✅ Project created successfully
✅ Development server running
✅ Project structure explored
