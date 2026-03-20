# 🚀 Ansible DevOps Automation Project

This project demonstrates **end-to-end DevOps automation** using Ansible, Docker, and Apache Web Server.

---

## 📌 Project Overview

This Ansible playbook automates the following tasks:

- 📦 Install Apache (httpd)
- 🌐 Deploy a static web page
- 🔥 Configure firewall rules
- 🐳 Install and configure Docker
- 📥 Pull Docker image (httpd)
- 📦 Run container with custom web content
- 🌍 Expose services on ports

---

## 🛠️ Technologies Used

- Ansible
- Docker
- Apache HTTP Server
- Linux (RHEL / CentOS)
- Git & GitHub

---

## 📂 Project Structure
```
ansible-devops-project/
├── ansi_docker.yml # Main Ansible Playbook
├── hosts # Inventory file
├── index.html # Web page content
└── README.md # Project documentation
```
---

## ⚙️ Prerequisites

Before running this project, ensure:

- Ansible installed
- SSH access between nodes
- Python installed on target machine
- Docker installed or installed via playbook

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone git@github.com:GSagar10/ansible-devops-project.git
cd ansible-devops-project

Check inventory file:

cat hosts

Run the playbook:

ansible-playbook -i hosts ansi_docker.yml

---

🌐 Access Application

After successful execution:

Open browser and visit:

http://<target-ip>:80

or

http://<target-ip>:7676

---
📌 Features

✔ Automated Apache setup
✔ Docker container deployment
✔ Firewall configuration
✔ Web content deployment
✔ Infrastructure as Code (IaC)

🔥 Learning Outcome

This project helps understand:

Ansible automation

Docker containerization

DevOps workflow

Configuration management

Infrastructure automation

👨‍💻 Author

Sagar Gharge

📧 Email: sagar.gharge10491@gmail.com

---
