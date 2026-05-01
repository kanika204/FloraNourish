# 🌱 FloraNourish  
### AI Powered Smart Plant Monitoring System

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Flask](https://img.shields.io/badge/Flask-Backend-black)
![IoT](https://img.shields.io/badge/IoT-ESP32-green)
![Status](https://img.shields.io/badge/Status-Prototype-success)

---

## 🚀 Overview

FloraNourish is an AI-driven smart agriculture system that integrates IoT sensors, Machine Learning, and Computer Vision to monitor plant health, detect diseases, and provide intelligent recommendations.

It helps farmers and home gardeners make data-driven decisions, improving plant growth while reducing resource wastage.

---

## ✨ Features

- 🌿 Plant Identification using image classification  
- 🌡️ Real-time monitoring (Moisture, Temperature, Humidity, Light)  
- 📊 Plant Health Score (0–100)  
- 🌾 Crop Recommendation System  
- 🦠 Disease Detection using CNN (MobileNetV2)  
- 🔮 Predictive Analysis (future plant stress & watering needs)  
- 📱 Web Dashboard for insights and alerts  

---

## 🧠 Tech Stack

### 🔹 AI/ML
- TensorFlow (CNN / MobileNetV2)
- Scikit-learn (Random Forest)

### 🔹 Backend
- Flask (Python)

### 🔹 Database
- Firebase (Real-time)

### 🔹 Libraries
- OpenCV  
- NumPy  
- Pandas  

### 🔹 IoT
- ESP32 / ESP8266  

---

## 🔧 Hardware Components

- ESP32 / ESP8266  
- Soil Moisture Sensor  
- DHT11 Sensor (Temperature & Humidity)  
- LDR Sensor (Light Intensity)  
- NPK Sensor (optional)  
- Camera (Webcam / Mobile)  
- Intel Core Laptop (for training & deployment)  

---

## ⚙️ System Workflow

- Image → Plant Identification  
- Sensor Data → Condition Analysis → Health Score  
- Disease Detection (CNN)  
- Prediction → Recommendation  
##
---

## 📊 Dataset Used

- Crop Recommendation Dataset  
- PlantVillage Dataset  
- Real-time IoT Sensor Data  

---



## 🛠️ Installation

```bash
git clone https://github.com/your-username/floranourish.git
cd floranourish
pip install -r requirements.txt
