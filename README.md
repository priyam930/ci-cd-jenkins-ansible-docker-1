# ci-cd-jenkins-ansible-docker
# 🔧 Building a CI/CD Pipeline from Scratch using Jenkins, Ansible, and Docker (Without DockerHub)

## LW_PROJECT_5

This project showcases how to build a complete **CI/CD pipeline from scratch** using **Jenkins**, **Ansible**, and **Docker**, without relying on **DockerHub** or any public container registry. Ideal for private enterprise environments where control over infrastructure is essential.

---

## 📖 Blog Post

📚 Read the full walkthrough on Medium:  
👉 [Building a CI/CD Pipeline from Scratch using Jenkins, Ansible, and Docker (without DockerHub)](https://medium.com/@priyamsanodiya340/building-a-ci-cd-pipeline-from-scratch-using-jenkins-ansible-and-docker-without-dockerhub-a3cfd99b77f4)

---

## 🧰 Tools & Technologies

- 🧪 Jenkins (Pipeline as Code)
- ⚙️ Ansible (Automation & Deployment)
- 🐳 Docker (Private Image Build & Run)
- 📡 Local Private Registry (Instead of DockerHub)
- 🐧 Linux (Shell Scripting)

---

## 🚀 Pipeline Flow

1. **Code Commit to Git**
2. **Jenkins triggers the build**
3. **Docker image built locally**
4. **Pushed to a private Docker Registry**
5. **Ansible pulls the image and deploys the container to the target machine**

---

## 📂 Project Structure

```bash
.
├── ansible/
│   └── deploy.yml
├── docker/
│   └── Dockerfile
├── jenkins/
│   └── Jenkinsfile
└── app/
    └── index.html / app.py / etc.
