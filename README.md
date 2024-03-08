# Real-Time Parking Space Detection & Management (Research Summary)

## 📌 Project Overview

This repository contains the presentation materials delivered for the graduate course **Introduction to Artificial Intelligence (COMP8700)** at the University of Windsor.

The project focuses on summarizing and critically reviewing the research paper: _"Real-Time Parking Space Detection and Management with Artificial Intelligence and Deep Learning System"_, which proposes a vision-based solution for smart city infrastructure.

> **Note:** This repository serves as a record of my academic presentation and technical review. I am the analyst and presenter; the original research and system implementation belong to the authors listed below.

## 📄 Original Research Reference

- **Paper Title:** Real-Time Parking Space Detection and Management with Artificial Intelligence and Deep Learning System
- **Authors:** Shweta Shukla, Rishabh Gupta, Sarthik Garg, Samarpan Harit, Rijwan Khan
- **Publication:** Transforming Management with AI, Big-Data, and IoT (Springer, 2022)
- **DOI/Link:** [Springer Link](https://link.springer.com/)

## 🔍 Key Concepts Analyzed

The presentation dissects a hybrid deep learning architecture designed to solve urban parking congestion. Key technical components reviewed include:

### 1. Parking Occupancy Detection (CNN)

- **Technology:** Sequential Convolutional Neural Networks (CNN)
- **Function:** Processes live video feeds to classify parking slots as "Free" or "Occupied"
- **Performance:** Achieves ~97.5% accuracy across sunny, cloudy, and rainy conditions

### 2. Availability Prediction (LSTM)

- **Technology:** Long Short-Term Memory (LSTM) Recurrent Neural Networks
- **Function:** Analyzes time-series data (weather, time of day) to forecast future parking availability

### 3. Anomaly Detection (Deep Learning)

- **Technology:** Multiple Instance Learning (MIL) & C3D Networks
- **Function:** Automatically detects 13 types of anomalies (e.g., theft, accidents, fighting) to enhance public safety

### 4. System Integration

- **Frontend:** Android Application
- **Backend:** Google Firebase for real-time database synchronization
- **Features:** Integrated booking system and Google Maps visualization

## 📂 Repository Contents

| File                      | Description                                       |
| ------------------------- | ------------------------------------------------- |
| `Presentation_Slides.pdf` | The slide deck used for the academic presentation |

## 🛠️ Technologies & Skills Explored

Through this project, I gained deep theoretical knowledge and analytical experience in:

- **Deep Learning Architectures:** CNNs, LSTMs, C3D
- **Computer Vision:** Object detection pipelines and video segmentation
- **Smart City IoT:** Feasibility of vision-based sensors vs. hardware ground sensors
- **Mobile Ecosystems:** Architecture of Android apps backed by real-time cloud databases (Firebase)

## 📬 Contact

**Harshkumar Sabhaya**  
University of Windsor  
📧 Email: [Sabhayah@uwindsor.ca](mailto:Sabhayah@uwindsor.ca)

---

_This project was completed as part of the Master's curriculum in Applied Computing/Computer Science._
