# CodeAlpha Web Server using Docker

## Overview

This project is developed as part of the **CodeAlpha DevOps Internship**.

The objective of this project is to demonstrate containerization using **Docker** by deploying a custom HTML webpage on an **Nginx Web Server**.

---

## Technologies Used

* Docker
* Docker Desktop
* Nginx
* HTML5
* CSS3
* Git
* GitHub

---

## Features

* Dockerized web application
* Custom responsive landing page
* Nginx web server
* Containerized deployment
* Local hosting on port 8080
* Easy deployment using Docker commands

---

## Project Structure

```
CodeAlpha_WebServerDocker
│
├── Dockerfile
├── index.html
└── README.md
```

---

## Docker Image Build

```
docker build -t codealpha-webserver .
```

---

## Run the Container

```
docker run -d -p 8080:80 --name codealpha-container codealpha-webserver
```

---

## View the Website

```
http://localhost:8080
```

---

## Docker Commands Used

### List Running Containers

```
docker ps
```

### Stop Container

```
docker stop codealpha-container
```

### Remove Container

```
docker rm codealpha-container
```

### Rebuild Image

```
docker build --no-cache -t codealpha-webserver .
```

---

## Learning Outcomes

* Docker Installation
* Docker Images
* Docker Containers
* Dockerfile Creation
* Nginx Deployment
* Container Lifecycle Management
* Web Server Deployment

---

## Future Enhancements

* HTTPS Support
* Docker Compose
* Multiple Containers
* Custom Domain
* Reverse Proxy
* Kubernetes Deployment

---

## Author

**Manohari M**

Artificial Intelligence & Data Science Student

CodeAlpha DevOps Internship Project
