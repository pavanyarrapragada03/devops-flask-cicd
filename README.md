# 🚀 Flask CI/CD Demo

![Build Status](https://img.shields.io/github/actions/workflow/status/your-username/devops-flask-cicd/ci.yml?branch=main&style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-Ready-blue?style=for-the-badge&logo=docker)
![Python](https://img.shields.io/badge/Python-3.9+-yellow?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A simple **Flask web application** integrated with a **CI/CD pipeline** using **GitHub Actions**.  
It includes automated **testing, Dockerization, and deployment** workflows.  

---

## 📂 Project Structure

devops-flask-cicd/
│── app.py # Main Flask application
│── requirements.txt # Python dependencies
│── Dockerfile # Docker build configuration
│── README.md # Project documentation
│
├── tests/ # Unit tests
│ └── test_app.py # Test cases for Flask app
│
├── .github/ # GitHub Actions workflows
│ └── workflows/
│ └── ci.yml # CI/CD pipeline config
