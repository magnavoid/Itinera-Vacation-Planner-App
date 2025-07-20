# Itinera – Vacation Planning App

Itinera is a full-stack vacation planning app developed as part of the WGU Software Engineering Capstone. The Android client allows users to plan vacations, manage excursions, generate PDF reports, and securely authenticate with a custom backend.

Android Frontend  
Go + PostgreSQL Backend  
JWT Authentication + Expired Token Handling  
PDF Report Generation  
Cloud-hosted API, GitHub Pages for documentation

## Features

- Secure user registration and login
- Vacation and excursion management with full CRUD
- PDF report generation with title, timestamp, and multiple rows
- Search functionality in vacation list
- Input validation and backend sanitization
- Expired token detection and redirect handling

## Architecture

- Android app written in Java using Retrofit 2
- Backend written in Go using Gin and GORM
- PostgreSQL database with schema auto-migration
- PDF reports rendered on-device using `PdfDocument`
- JWT-based auth with protected routes

## Getting Started

To install the app, download the latest release:

[**Download Itinera**](https://github.com/magnavoid/Itinera-Vacation-Planner-App/releases/latest/download/app-release.apk)
