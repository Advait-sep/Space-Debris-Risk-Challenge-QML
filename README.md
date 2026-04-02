# 🛰️ Space Debris Risk Prediction

This project addresses the growing challenge of **space debris collision risk**. Using **machine learning** and **quantum machine learning (QML)** models, we classify orbital scenarios into three categories of collision risk:

- **Low Risk** → `0`
- **Moderate Risk** → `1`
- **High Risk** → `2`

The project compares the performance of **classical ML models** and **hybrid quantum-classical models**.

---

## 🚀 Project Objective

Predict the **collision risk level** of space debris using **40 high-dimensional orbital and telemetry features**.

The main goal is to compare the performance of:

- **Classical Machine Learning Model:** Support Vector Machine (**SVM**)
- **Quantum Machine Learning Model:** Quantum Support Vector Machine (**QSVM**)

---

## 📁 Dataset

The dataset consists of:

- **40 features**, including:
  - Material properties
  - Orbital position
  - Velocity parameters
  - Object size
  - Sensor-derived metrics

- **Target variable (3 classes):**
  - `0` → Low Risk  
  - `1` → Moderate Risk  
  - `2` → High Risk  

Dataset files:
'train.csv' and 
'test.csv'

---

## ⚙️ Data Preprocessing

The following preprocessing steps are applied:

- **Standard Scaling** for feature normalization
- **Class Weight Adjustment** to handle class imbalance

---

## 📊 Evaluation Metrics

Model performance is evaluated using:

- **Balanced Accuracy**
- **Macro F1-score**

These metrics ensure fair evaluation across all classes.

---

## 🧪 Model Overview

### Classical Machine Learning Model
- **Algorithm:** Support Vector Machine (**SVM**)

### Quantum Machine Learning Model
- **Algorithm:** Quantum Support Vector Machine (**QSVM**)

**Quantum Components:**

- **Feature Map:** `ZZFeatureMap`
- **Quantum Simulator:** `PennyLane lightning.qubit`

---

## 📄 Output

At the end of the experiment, a file named:
'predictions.csv'
is generated.

This file contains a **comparison between predictions** from:

- Classical **SVM**
- Quantum **QSVM**

---

## 📌 Summary

This project demonstrates how **quantum-enhanced machine learning** can be applied to **space situational awareness problems**, specifically the **prediction of space debris collision risk**, and compares its performance against classical ML approaches.
