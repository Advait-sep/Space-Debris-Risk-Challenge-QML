Space_Debris_Risk
🛰️ Space Debris Risk Prediction
This project addresses the growing challenge of space debris collision risk. Using machine learning and quantum machine learning (QML) models, we classify orbital scenarios into three categories of collision risk: Low (0), Moderate (1), and High (2).

🚀 Project Objective
Predict the risk level of a collision involving space debris based on 40 high-dimensional orbital and telemetry features. Compare the performance of classical models (e.g., SVM) and hybrid quantum-classical models (e.g., QSVM).

📁 Dataset
The dataset contains the following:

40 features including material, position, velocity, size, and sensor-derived metrics.
A target variable with 3 classes: 0 (Low), 1 (Moderate), 2 (High)
The dataset is split into training (train.csv) and test (test.csv) sets.

Preprocessing: Standard scaling, class weight adjustment
Metric: Balanced Accuracy, Macro F1-score
🧪 Model Overview
1. Classical ML Model: Support Vector Machine (SVM)
2. Quantum ML Model: Quantum Support Vector Machine (QSVM)
Feature Map: ZZFeatureMap
simulator: Pennylane's 'lightning.qubit'
At the end, a CSV file named (predictions.csv) is created, which contains a comparison between the predictions made by the Classical SVM and the Quantum SVM models.
