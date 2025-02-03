# Basic Static Website with Docker and Nginx 🚀

This project provides a ***simple static website** deployed using **Docker and Nginx**. The website consists of a single **HTML file with embedded CSS**, served by an Nginx container.

## 📦 Features
- **Lightweight and fast:** Uses Nginx to efficiently serve static files.
- **Containerized deployment:** Runs in a Docker container for easy portability and scalability.
- **Simple setup:** Requires minimal configuration to get started.

## 🔧 Tech Stack
- **Docker** - Containerization
- **Nginx** - Reverse Proxy
- **HTML + CSS** - Static file

## 🚀 Getting Started

### 📥 **Cloning the Repository**
To get started, first **clone the repository**:

```sh
git clone https://github.com/caaiobomfim/docker-website-nginx-html-basic.git
```

### 🔥 Build and start the container
Run the following command to build and start the containers:

```sh
cd docker-website-nginx-html-basic
docker-compose up -d --build
```

### 🌍 Testing the Application
Once the containers are running, access:

```sh
http://localhost:8080
```

Or use curl:

```sh
curl http://localhost:8080
```