# vue.js Setup Guide

A veu.js application deploy using docker


## Project Structure
```
.
├── Dockerfile              # docker file with Nginx
└── README.md              # This file
```

## Setup Instructions

### Method 1: Clone the Repository and Build Locally

### 1. Clone the Repository
```bash
git clone "https://github.com/lovesainju-7/VUE_APPLICATION.git"
cd Laravel-Application
```
### 2. Build the Docker Image
```bash
docker build -t my-vue-app .
```
### 3. Run the Docker Container
```bash
docker run -p 8080:80 my-vue-app
```
### 4. Access the Application
```bash
http://localhost:8080
```

###  Method 2: Run Using Docker Hub Image
This method does not require cloning the repository.

### 1. Pull the Image from Docker Hub
```bash
docker pull lovesainju/my-vue-app:latest
```
### 2. Run the Container
```bash
docker run -p 8080:80 lovesainju/my-vue-app:latest
```
### 3. Access the Application
```bash
# Open your browser and visit:
http://localhost:8080
```
