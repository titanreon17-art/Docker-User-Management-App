# Dockerized User Management Web Application

A containerized web application built using **Node.js**, **Express.js**, **MongoDB**, and **Docker**. This project demonstrates how to build, containerize, and run a backend application that stores and retrieves user information from a MongoDB database.

---

## Features

- Add new users
- Retrieve all users
- MongoDB database integration
- Dockerized application
- RESTful APIs
- Static frontend
- Easy deployment using Docker

---

## Technologies Used

- Docker
- Node.js
- Express.js
- MongoDB
- JavaScript
- HTML
- CSS

---

## Project Structure

```
docker-user-management-app/
│
├── public/
├── node_modules/
├── Dockerfile
├── package.json
├── package-lock.json
├── server.js
├── mongodb.yaml
└── README.md
```

---

## Architecture

```
User
   │
   ▼
Browser
   │
   ▼
Express Server
   │
   ▼
MongoDB Database
```

---

## REST APIs

### Add User

```
POST /addUser
```

Adds a new user to the MongoDB database.

---

### Get Users

```
GET /getUsers
```

Returns all stored users.

---

## Installation

### Clone Repository

```bash
git clone https://github.com/titanreon17-art/docker-user-management-app.git
```

Move inside the project

```bash
cd docker-user-management-app
```

---

## Install Dependencies

```bash
npm install
```

---

## Run Application

```bash
node server.js
```

---

## Build Docker Image

```bash
docker build -t user-management-app .
```

---

## Run Docker Container

```bash
docker run -d -p 3000:3000 user-management-app
```

---

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Docker
- REST APIs

---

## Learning Outcomes

- Docker Image Creation
- Docker Containers
- Backend API Development
- MongoDB Integration
- RESTful API Design
- Environment Variables
- Containerized Deployment

---

## Future Improvements

- User Authentication
- JWT Security
- CRUD Operations (Update/Delete)
- Docker Compose
- Kubernetes Deployment
- CI/CD Pipeline
- Nginx Reverse Proxy
- HTTPS Support

---

## Author

Mehboob Siddiqui

