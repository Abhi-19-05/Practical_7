# 🚀 Zenith Store – Static Website Deployment

## 📌 Overview

Zenith Store is a responsive single-page static website showcasing premium technology products with a modern, Apple-inspired UI. The website is built using **HTML, CSS, and JavaScript** and is deployed on an **AWS EC2 instance** using **GitHub Actions** for automatic deployment.

Whenever changes are pushed to the `main` branch, GitHub Actions securely connects to the EC2 instance via SSH and updates the live website.

---

## ✨ Features

- Modern and responsive UI
- Sticky navigation bar
- Hero section with promotional offers
- Dynamic product cards generated using JavaScript
- Interactive "Add to Bag" modal
- Trade-in promotional section
- Clean footer with policy information
- Automatic deployment using GitHub Actions

---

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- AWS EC2
- GitHub Actions
- Git
- SSH

---

## 📁 Project Structure

```
.
├── .github/
│   └── workflows/
│       └── deploy.yml
├── index.html
└── README.md
```

---

## ⚙️ Deployment Workflow

The deployment is fully automated through GitHub Actions.

1. Push changes to the `main` branch.
2. GitHub Actions workflow is triggered.
3. The workflow connects to the AWS EC2 instance using SSH.
4. The latest code is pulled into `/var/www/html`.
5. The website is updated automatically.

---

## 🔐 GitHub Secrets

The following secrets are configured in the GitHub repository:

- `EC2_HOST`
- `EC2_USER`
- `EC2_SSH_KEY`

---


## 👨‍💻 Author

**Abhinandan Pakhare**

B.Tech Student | Data Analyst | Cloud & DevOps Enthusiast

---

## 📄 License

This project is created for educational and portfolio purposes.
