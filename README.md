# Hall Management System

This repository contains a full-stack Hall Management System with a Django backend and a Next.js frontend.

Quick start (development)

1. Backend (Python / Django)

   - Create and activate a virtual environment:

     python -m venv .venv
     .\.venv\Scripts\Activate.ps1

   - Install dependencies and run migrations:

     pip install -r backend/requirements.txt
     cd backend
     python manage.py migrate
     python manage.py runserver

2. Frontend (Next.js / TypeScript)

   - From project root:

     cd frontend
     npm install
     npm run dev

Notes

- This README is intentionally minimal. Add environment variables and deployment instructions as needed.
- Large media files may already be committed — consider removing them and storing uploads externally for production.
