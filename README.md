# Anomaly Detection ACE: Credit Card Fraud Detection

## Project Overview

This repository documents my progress on the 'Anomaly Detection ACE' project, specifically focusing on Credit Card Fraud Detection. The project aims to develop a robust, real-time anomaly detection system using a variety of machine learning and deep learning techniques.

---

## Project Phases & Progress

This project is broken down into several key phases. Each phase will have its own dedicated folder and documentation.

### Phase 1: Data Preparation & Exploration
- [ ] **Data Acquisition:** Find and download a suitable dataset (e.g., from Kaggle).
- [ ] **Initial Exploration:** Analyze the dataset for distribution, missing values, and the number of fraudulent vs. non-fraudulent transactions.
- [ ] **Handling Imbalance:** Implement and compare techniques like SMOTE, Undersampling, or Cost-Sensitive Learning to address the highly imbalanced nature of the data.

### Phase 2: Feature Engineering
- [ ] **Behavioral Feature Creation:** Generate new features based on user behavior over time (e.g., average transaction amount in the last 24 hours, number of transactions per week).
- [ ] **Time-Based Features:** Extract features from the transaction timestamp (e.g., day of the week, hour of the day).
- [ ] **Data Normalization:** Scale numerical features to ensure all models perform optimally.

### Phase 3: Model Development & Training
- [ ] **Supervised Models:** Train and evaluate traditional classifiers like Logistic Regression, Random Forest, or XGBoost.
- [ ] **Unsupervised Anomaly Detection:** Implement and test unsupervised models such as Isolation Forest and Autoencoders to identify transactions that deviate from the norm.
- [ ] **Graph-Based Models:** Explore and build a Graph Neural Network (GNN) to detect fraud by analyzing the relationships between transactions and accounts.

### Phase 4: Model Evaluation
- [ ] **Choose the Right Metrics:** Do NOT use Accuracy. Use metrics like Precision, Recall, F1-Score, and AUC-ROC to properly evaluate model performance on the imbalanced dataset.
- [ ] **Comparative Analysis:** Compare the performance of the supervised, unsupervised, and graph-based models to determine which approach is most effective.

### Phase 5: System Design & Deployment
- [ ] **Real-Time Pipeline:** Outline a real-time system architecture, including data ingestion and model serving.
- [ ] **Feature Store:** Research and document the role of a Feature Store for providing low-latency features to the model.
- [ ] **Model Persistence:** Save the final trained model for future use.

---

## Future Work & Improvements
- [ ] Explore hybrid models (e.g., GNN + XGBoost).
- [ ] Implement a feedback loop to retrain the model on new fraud patterns (Concept Drift).
- [ ] Deploy the final model as a simple API for real-time inference.
