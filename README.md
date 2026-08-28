# RJ 147 – Smart Waste Segregation and Sanitation System

## 📌 Project Overview

The **Smart Waste Segregation and Sanitation System** is an AI and Cloud Computing-based software solution designed to automate waste classification and provide intelligent segregation recommendations.

The system allows users to upload waste images, classify the waste using AI, store prediction records in the cloud, and visualize waste-related analytics through a web dashboard.

## 🎯 Objectives

* Automate waste classification using Artificial Intelligence.
* Provide appropriate waste segregation and disposal recommendations.
* Store waste classification records securely using cloud computing.
* Provide analytics and sanitation insights from recorded waste data.
* Develop an easy-to-use web application for users and administrators.

## 🤖 AI Methodology

The project uses two main approaches:

* **Custom CNN** – Used as a baseline classification model.
* **Transfer Learning** – Used as the main practical classification approach using a pretrained vision model.

The models are trained and evaluated using **Google Colab**.

Evaluation includes:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Training/Validation Accuracy
* Training/Validation Loss

Actual model results will be added after training and evaluation.

## 🌐 Web Application

The web application provides:

* User Registration and Login
* Waste Image Upload
* AI Waste Classification
* Confidence Score
* Segregation Recommendation
* Classification History
* Waste Analytics
* Sanitation Insights
* Admin Dashboard
* AI Waste Assistant

## ☁️ Cloud Computing

**Firebase** is used for cloud services, including:

* Firebase Authentication
* Cloud Firestore
* Firebase Storage

The cloud layer stores user information, waste classification records, images and analytics data.

## 🏗️ System Architecture

```text
User
 ↓
Web Application
 ↓
Flask Backend
 ↓
AI Model
 ↓
Waste Classification
 ↓
Segregation Recommendation
 ↓
Firebase Cloud
 ↓
Analytics
 ↓
Admin Dashboard
 ↓
Sanitation Insights
```

## 📚 Research Papers

The `Research-Papers` folder contains the research papers reviewed for this project.

The literature covers:

* AI-powered waste segregation
* CNN-based waste classification
* Computer vision for waste management
* Smart waste management systems
* Sanitation monitoring
* Intelligent waste classification

## 📂 Repository Structure

```text
Smart-Waste-Segregation-System/
│
├── Research-Papers/
├── References/
├── AI-Model/
├── Web-Application/
├── Dataset/
├── Documentation/
└── README.md
```

## 🔐 Security

The system is designed to use:

* Authentication
* Role-based access
* Protected admin functions
* Input validation
* File validation
* Environment variables for sensitive credentials
* Secure Firebase rules

No passwords, API keys or Firebase credentials are stored directly in the repository.

## ⚙️ Technologies Used

**Frontend:** HTML, CSS, JavaScript, Bootstrap

**Backend:** Python, Flask

**AI/ML:** CNN, Transfer Learning, Computer Vision

**Training:** Google Colab

**Cloud:** Firebase Authentication, Firestore, Firebase Storage

**Visualization:** Chart.js

## 🚧 Project Status

**Current Progress:** Research and system design completed; dataset preparation and AI model development are in progress.

## 🔮 Future Scope

* Real-time waste object detection
* Advanced waste segmentation
* Predictive waste collection
* Mobile application
* IoT-based smart-bin integration
* Advanced sanitation monitoring

IoT and physical smart-bin features are considered **future scope** and are not part of the current software-only implementation.

## 👩‍💻 Project

**Project ID:** RJ 147
**Project Title:** Smart Waste Segregation and Sanitation System
**Domain:** Artificial Intelligence + Cloud Computing
**Project Type:** Final-Year Engineering Project
