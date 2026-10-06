# Locker Reservation System

A Minimum Viable Product (MVP) that gives students a simple, functional platform for reserving lockers in academic institutions. A React frontend talks to a FastAPI backend, which stores its data in MongoDB.

## Features

**Students**
- View available lockers
- Reserve a locker

**Admin**
- View available lockers
- See reserved lockers
- See lockers currently in use

## Repo Structure

### `locker-reservation-app/`

- The frontend, built with React.js. The interface that students and admins use to interact with the system.

### `locker-reservation-api/`

- The backend API, built with FastAPI (Python). It handles requests from the frontend and manages the connection to the MongoDB database.

## System Architecture

```
React frontend  <-->  FastAPI backend  <-->  MongoDB
(locker-reservation-app)  (locker-reservation-api)
```

## Tools

- **Frontend:** React.js, JavaScript, HTML
- **Backend:** Python, FastAPI
- **Database:** MongoDB
- **Version control:** Git, GitHub

## Purpose

This project demonstrates how a full-stack application is put together from separate services, including:

- Building a frontend and backend as independent services
- Connecting a REST API to a MongoDB database
- Integrating the frontend with the backend

## Author

Hamza Adam Aliyu: [LinkedIn](https://linkedin.com/in/hamza-adam-aliyu)
