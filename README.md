# 🎓 Campus Recruitment System (PHP + Flask Hybrid)

![PHP](https://img.shields.io/badge/PHP-8.0+-777BB4.svg)
![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Flask](https://img.shields.io/badge/Flask-2.3-green.svg)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange.svg)
![Machine Learning](https://img.shields.io/badge/ML-Predictions-ff69b4.svg)

## 📌 Overview
A hybrid web platform combining PHP for frontend and Python Flask for backend services to streamline campus recruitment with job prediction capabilities.

## ✨ Key Features

### 🌐 PHP Frontend Components
- User authentication system
- Dynamic form processing
- Session management
- Responsive UI templates

### 🐍 Python Backend Services
- Machine learning predictions
- PDF resume processing
- Data analytics
- REST API endpoints

## 🖥️ Technology Stack

| Component       | Technology           |
|----------------|---------------------|
| Frontend       | PHP 8, HTML5, Bootstrap 5 |
| Backend        | Python Flask        |
| Database       | MySQL 8.0           |
| ML Prediction  | Scikit-learn        |
| API Communication | cURL, JSON       |

## 🏗️ System Architecture

```mermaid
graph LR
    A[PHP Frontend] -->|AJAX/JSON| B[Flask API]
    B --> C[MySQL Database]
    B --> D[ML Prediction Model]
    A --> E[PHP Sessions]

