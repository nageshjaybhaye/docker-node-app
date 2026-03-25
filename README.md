# 🚀 Docker Node.js App

A simple Node.js application containerized using Docker. This project demonstrates how to build a Docker image and run a container locally.

---

## 📌 Project Overview

This is a basic Node.js HTTP server that returns a simple message:

```
Hello , Docker is running 
```

The goal of this project is to understand:

* Docker basics
* Image creation
* Container execution
* Port mapping

---

## 🛠️ Tech Stack

* Node.js
* Docker

---

## 📂 Project Structure

```
docker-node-app/
│
├── app.js
├── package.json
├── Dockerfile
```

---

## ⚙️ How to Run Locally

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/docker-node-app.git
cd docker-node-app
```

---

### 2️⃣ Build Docker Image

```
docker build -t my-node-app .
```

---

### 3️⃣ Run Docker Container

```
docker run -d -p 3000:3000 my-node-app
```

---

### 4️⃣ Access Application

Open browser and visit:

```
http://localhost:3000
```

---

## 🐳 Docker Commands Used

* Build Image:

  ```
  docker build -t my-node-app .
  ```

* Run Container:

  ```
  docker run -d -p 3000:3000 my-node-app
  ```

* Stop Container:

  ```
  docker stop <container_id>
  ```

* Remove Container:

  ```
  docker rm <container_id>
  ```

---

## 🎯 Learning Outcome

* Understood Dockerfile creation
* Learned how to build and run containers
* Gained knowledge of port mapping and container lifecycle

---

## 📌 Future Improvements

* Push Docker image to Docker Hub
* Deploy application on AWS EC2
* Add CI/CD pipeline (GitHub Actions)

---

## 👨‍💻 Author

**Nagesh Jaybhaye**
CloudOps Engineer | AWS Certified

---

## ⭐ Give a Star

If you found this project helpful, please give it a ⭐ on GitHub!
