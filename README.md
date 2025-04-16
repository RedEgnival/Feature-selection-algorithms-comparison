# 💳 Credit Card Fraud Detection with Feature Selection Optimization


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/credit-card-fraud-detection/blob/main/fraud_detection.ipynb)

An advanced fraud detection system comparing genetic algorithm feature selection against traditional methods, achieving optimal performance with XGBoost classifier.

## 📊 Key Features
- **Genetic Algorithm** for intelligent feature selection
- Comparison with SelectKBest and RFE methods
- SMOTE for handling class imbalance
- Comprehensive performance metrics (Accuracy, Precision, Recall, F1)
- Interactive visualizations of results

## 🧠 Methodology

graph TD
    A[Raw Data] --> B[Data Sampling]
    B --> C[Feature Scaling]
    C --> D[SMOTE Oversampling]
    D --> E[Genetic Algorithm FS]
    D --> F[SelectKBest FS]
    D --> G[RFE FS]
    E --> H[XGBoost Classifier]
    F --> H
    G --> H
    H --> I[Performance Evaluation]
