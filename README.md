# Simple Docker Compose Setup

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Usage](#usage)
- [Directory Hierarchy](#directory)

## Description <a name = "description"></a>
This repository contains a simple Docker Compose setup for quickly deploying a multi-container application. The Docker Compose file included here orchestrates the deployment of three services: a web server, a MongoDB database, and a backend server. Project from "Docker: Ferramenta essencial para Desenvolvedores".

## Features <a name = "features"></a>
- **Dockerized environment:** Utilizes Docker Compose to define and manage the containerized application environment.
- **Frontend:** HTML with AJAX for dynamic content rendering.
- **Backend:** JavaScript-based server for handling business logic and communication with the database.
- **Database:** MongoDB service for storing application data.

## Usage <a name = "usage"></a>
1. Clone this repository to your local machine.
2. Install Docker and Docker Compose if you haven't already.
3. Navigate to the project directory.
4. Run `docker-compose up` to start the containers.
5. Access the web server at `http://localhost`.

## Directory Hierarchy <a name = "directory"></a>
```
|—— backend
|    |—— app.js|   
|    |—— package.json
|—— frontend
|    |—— index.html
|—— docker-compose.yml