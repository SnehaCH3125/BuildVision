# 🏗️ BuildVision: AI-Powered Construction Efficiency Platform

**BuildVision** is a comprehensive AI-driven platform that enhances construction project performance through smart analytics, safety compliance monitoring, and generative design. Developed using state-of-the-art Machine Learning and Computer Vision models, BuildVision empowers stakeholders with predictive insights and intelligent automation to reduce delays, ensure worker safety, and optimize supplier choices.

---

## 🔍 Overview

Construction projects often suffer from delays, safety violations, and inefficient supplier decisions. BuildVision addresses these challenges through:

- 🔮 **Delay Prediction**
- 🦺 **Real-time PPE Detection**
- 🔎 **Supplier Recommendation Engine**
- 🏢 **Floor Plan Generation with GANs**

By integrating all components into a single unified Streamlit interface, BuildVision offers an intuitive and scalable solution tailored for the construction industry.

---

## 🚀 Core Modules

### 🕒 1. Project Delay Prediction  
Predicts potential delays using construction site data and ML models (XGBoost, Random Forest, Gradient Boosting). Enables proactive risk mitigation.

### 🦺 2. PPE Detection (Safety Compliance)  
Real-time computer vision model (YOLOv11) detects whether workers wear helmets, safety vests, and boots. Helps ensure regulatory compliance.

### 🤝 3. Supplier Recommendation System  
Uses K-Nearest Neighbors (KNN) to suggest reliable and cost-efficient suppliers based on historical data and performance.

### 🏗️ 4. Floor Plan Generation with GANs  
Converts sketch-style floor plan blueprints into architectural-quality outputs using Pix2Pix GAN architecture.

---

## 🛠️ Tech Stack

| Domain         | Tools & Frameworks                                      |
|----------------|----------------------------------------------------------|
| ML Models      | XGBoost, Random Forest, Gradient Boosting, KNN           |
| Deep Learning  | YOLOv11 (PPE Detection), Pix2Pix GAN (Floor Plans)       |
| Backend & UI   | Python, Streamlit                                        |
| Libraries      | OpenCV, PyTorch, NumPy, Pandas                           |

---

## 📁 Project Structure

BuildVision/
├── delay_prediction/
├── ppe_detection/
├── supplier_recommendation/
├── floorplan_generation/
├── assets/
├── app.py
└── README.md

## ⚙️ Getting Started

#### 1. Clone the Repository

    git clone https://github.com/SnehaCH3125/BuildVision.git
    cd BuildVision

