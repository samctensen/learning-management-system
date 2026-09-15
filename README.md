# Learning Management System

A Django course-management application for assignment submissions, grading, and student and staff workflows.

Originally developed in late spring semester 2023. Uploaded to GitHub in January 2024.

Students can submit assignments, teaching assistants can grade work, and administrators have separate management views. The app uses Django, SQLite, HTML/CSS, and jQuery for asynchronous uploads.

## Run

Activate a Python environment with Django installed, then run from the repository root:

```sh
python manage.py check
python manage.py runserver
```

The checked-in settings identify Django 4.2.4 as the original framework version. There is no dependency lockfile; restoring the original environment may be necessary for this historical snapshot.

## Project

- `cs3550/` — Django project configuration.
- `grades/` — course, assignment, submission, and grading functionality.
- `static/` — styles and browser assets.
- `db.sqlite3`, `uploads/`, and sample text files — preserved course/demo data.

This repository preserves the original local course application and its sample data.
