
# 🏥 Predicting Medical Device Failure

Ensuring the safety and reliability of medical devices is critical for patient care.  
This project uses **machine learning** to predict the risk of device failure based on recall notices, device logs, and historical data.  
It provides a **risk score** along with a simple **UI interface** for easy usage manufacturers to plan interventions, generate reports for Medical Device Regulatory Authorities like FDA/CDSCO
It helps to create a FDA regulatory compliance report.

---

## 🚀 Features
- Data preprocessing and feature engineering for device attributes  
- Risk scoring for each device based on severity & likelihood of failure  
- Machine learning models (Logistic Regression, XGBoost, etc.)  
- Model validation and performance analysis (precision, recall, F1-score)  
- Interactive UI / Dashboard to input device details and get predictions 

## Repository Structure

```
Predicting-Medical-equipment-Failures/
│
├── notebooks/           # Jupyter notebooks for analysis and visualization
├── dataset/             # Data files
│   ├── raw/             # Original, immutable data
│   ├── processed/       # Cleaned and processed data
│   └── final/           # Data used for modeling
├── models/              # Trained models
├── src/                 # Source code
│
├── docs/                # Documentation
├── model_artifacts/     # Model checkpoints and logs
│   ├── checkpoints/     # Model checkpoints
│   └── logs/            # Training logs
├── .gitignore
└── README.md
```
