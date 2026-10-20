# Tic Tac Toe — DevOps Mini Project

A browser-based Tic Tac Toe game packaged with Docker and hosted using Nginx. This project demonstrates practical DevOps skills, including containerization, version control, and application deployment.

## 🚀 Live Demo

**Play the game:** https://noorsk4800-bit.github.io/tic-tac-toe-devops/

## 🛠️ Tech Stack

- **HTML, CSS, JavaScript** — Game interface and logic
- **Docker** — Containerization
- **Nginx** — Web server
- **Git & GitHub** — Version control and source code hosting
- **AWS EC2** — Application deployment and testing
- **GitHub Pages** — Static website hosting

## ✨ Features

- Interactive two-player Tic Tac Toe game
- Win and draw detection
- Restart and replay functionality
- Responsive user interface
- Docker-based deployment using Nginx

## 🏗️ Architecture

Developer → GitHub Repository → Docker Image → Nginx Container → Web Browser

## 🐳 Run Locally with Docker

Clone the repository:

```bash
git clone https://github.com/noorsk4800-bit/tic-tac-toe-devops.git
cd tic-tac-toe-devops
```

Build the Docker image:

```bash
docker build -t tic-tac-toe:v1 .
```

Run the container:

```bash
docker run -d --name tic-tac-toe -p 8080:80 tic-tac-toe:v1
```

Open http://localhost:8080 in your browser.

## 📚 What I Learned

- Building and packaging a web application with Docker
- Serving static content through Nginx
- Managing project code with Git and GitHub
- Deploying and testing an application on AWS EC2
- Understanding the foundation of a CI/CD workflow

## 👩‍💻 Author

**Norjahan**

Aspiring DevOps Engineer | Linux | Git | Docker | Jenkins | AWS | Kubernetes | Terraform

GitHub: https://github.com/noorsk4800-bit
