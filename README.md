# 🚀 End-to-End DevOps CI/CD Pipeline

This project demonstrates a complete DevOps pipeline using modern tools and cloud infrastructure.

The project automates the process of building, containerizing, and deploying a Flask application using Jenkins, Docker, Kubernetes, Terraform, and AWS.

---

# 🧩 Architecture

Developer → GitHub → Jenkins CI/CD → Docker Build → DockerHub → Terraform → AWS EC2 → Docker Container → Flask Application

---

# ⚙️ Technologies Used

- GitHub – Source code management
- Docker – Containerization
- Kubernetes – Container orchestration
- Jenkins – CI/CD automation
- DockerHub – Container registry
- Terraform – Infrastructure as Code
- AWS EC2 – Cloud deployment
- Flask – Web application framework

---

# 📂 Project Structure
devops-cicd-project
│
├── app
│ └── app.py
│
├── docker
│ └── Dockerfile
│
├── kubernetes
│ ├── deployment.yaml
│ └── service.yaml
│
├── jenkins
│ └── Jenkinsfile
│
├── terraform
│ ├── provider.tf
│ ├── ec2.tf
│ └── outputs.tf
│
└── README.md

---

# 🔄 CI/CD Pipeline

1. Developer pushes code to GitHub
2. Jenkins pipeline automatically triggers
3. Docker image is built
4. Image is pushed to DockerHub
5. Terraform provisions AWS infrastructure
6. EC2 instance runs Docker container
7. Application becomes accessible via public IP

---

# ☁️ Deployment

Application is deployed on **AWS EC2** using Docker containers and Terraform infrastructure provisioning.

---

# 📸 Screenshots

- Jenkins Pipeline
- DockerHub Repository
- AWS Deployment
- Running Application

---

# 🎯 Learning Outcomes

- Containerization with Docker
- Kubernetes deployment
- CI/CD automation with Jenkins
- Infrastructure as Code using Terraform
- Cloud deployment on AWS
- End-to-end DevOps workflow

---

# 👨‍💻 Author

**Siddhesh Nikumb**