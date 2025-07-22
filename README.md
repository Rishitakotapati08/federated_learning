## Federated Learning for Privacy-Preserving Mental Health Diagnosis

This project implements a **federated learning system** to predict the likelihood of mental health treatment needs using real-world survey data. It simulates multiple clients (countries), performs decentralized model training with **differential privacy**, and enhances transparency with **explainable AI (SHAP)** visualizations. The project demonstrates how user data can remain private while achieving effective, scalable, and interpretable predictive modeling.

---

##  Features

-  **Federated Learning Simulation** across multiple countries as clients
-  **Differential Privacy** applied via Gaussian noise to protect model weights
-  **Model Evaluation** using Accuracy, ROC-AUC, and Classification Reports
-  **Client vs Global Model Performance Comparison**
-  **Explainable AI with SHAP** for identifying key features influencing predictions
-  **Visualizations**:
  - Local vs Global model accuracy bar plots
  - Federated learning round performance trends
  - Calibration curve for confidence estimation
  - 3D surface plot of client accuracies
  - Sankey diagram for client contribution to the global model

---

##  Dataset

- Source: `survey.csv`
- Description: Mental health survey data including demographics, workplace policies, and mental health treatment status.
- Target: `treatment` (whether the respondent has sought mental health treatment)

---

## Tech Stack

- **Python**
- **scikit-learn**
- **imbalanced-learn (SMOTE)**
- **matplotlib & seaborn**
- **shap (SHapley Additive exPlanations)**

---



