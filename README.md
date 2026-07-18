# Non-invasive-Glucose-monitoring
## Overview

This project presents a **non-invasive glucose monitoring system** developed as my final-year undergraduate project. The system estimates blood glucose levels without finger-prick methods by using optical sensing techniques and embedded hardware. In addition to hardware implementation, machine learning models were developed and evaluated to improve glucose prediction accuracy.

The project integrates optical sensors, Arduino-based embedded hardware, signal processing, and machine learning to provide an affordable and portable glucose monitoring solution.

---

## Problem Statement

Traditional blood glucose monitoring requires invasive finger-prick testing, which can be painful and inconvenient for regular monitoring. This project explores a non-invasive alternative using optical sensing and predictive machine learning models.

---

## Objectives

- Develop a non-invasive glucose monitoring prototype.
- Measure pulse rate in real time.
- Acquire sensor data using Arduino.
- Process and clean collected data.
- Build machine learning models for glucose prediction.
- Compare model performance using evaluation metrics.
- Identify the best-performing model.

---

## Features

- Non-invasive glucose estimation
- Real-time pulse monitoring
- Arduino-based embedded system
- OLED display
- Optical sensing
- Machine learning-based glucose prediction
- Model performance comparison

---

## Hardware Components

| Component | Purpose |
|-----------|----------|
| Arduino Uno | Data acquisition |
| OPT101 | Optical sensor |
| MAX30102 | Pulse sensor |
| OLED Display | Display readings |
| Laser Diode | Light source |
| Capacitors & Resistors | Signal conditioning |

---

## Software & Tools

- Arduino IDE
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## System Workflow

Finger Placement
↓
OPT101 Sensor
↓
Signal Conditioning
↓
Arduino Data Acquisition
↓
Data Preprocessing
↓
Feature Engineering
↓
Machine Learning Models
↓
Prediction
↓
OLED Display

---

## Machine Learning Pipeline

- Data Collection
- Data Cleaning
- Feature Engineering
- Train-Test Split
- Model Training
- Model Evaluation
- Prediction

---

## Machine Learning Models Evaluated

- Linear Regression
- K-Nearest Neighbors (KNN)
- Random Forest Regression

---

## Model Evaluation Metrics

- Mean Squared Error (MSE)
- R² Score
- Prediction Accuracy

---

## Model Comparison

| Model | MSE | R² Score | Accuracy |
|--------|-----|----------|----------|
| Linear Regression | 37.11 | 0.95 | 70% |
| Random Forest | 26.26 | 0.97 | 90% |
| K-Nearest Neighbors | **14.86** | **0.98** | **100%** |

---

## Best Performing Model

Based on the evaluation metrics:

- Lowest Mean Squared Error
- Highest R² Score
- Highest Prediction Accuracy

**K-Nearest Neighbors (KNN)** achieved the best overall performance for glucose prediction and was selected as the final model for this project.

---

## Results

- Successfully developed a non-invasive glucose monitoring prototype.
- Real-time pulse rate monitoring implemented.
- Machine learning models trained and compared.
- KNN provided the highest prediction accuracy among all evaluated models.

---

## Future Improvements

- Collect a larger dataset.
- Deploy the model on edge devices.
- Mobile application integration.
- Bluetooth/Wi-Fi connectivity.
- Cloud-based health monitoring.
- Deep learning model comparison.

---

## Repository Structure

```
Arduino_Code/
ML_Model/
Dataset/
Documentation/
Hardware/
Images/
Results/
Presentation/
```

---

## Technologies Used

- Arduino
- Embedded C
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## Author

**Haripriya K**

Biomedical Engineering Graduate

Embedded Systems | Python | SQL | Machine Learning | Data Analysis

