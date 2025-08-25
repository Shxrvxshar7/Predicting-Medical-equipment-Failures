
# 🏥 Predicting Medical Device Failure

Ensuring the safety and reliability of medical devices is critical for patient care.  
This project uses **machine learning** to predict the risk of device failure based on recall notices, device logs, and historical data.  
It provides a **risk score** along with a simple **UI interface** for easy usage manufacturers to plan interventions, generate reports for Medical Device Regulatory Authorities like FDA/CDSCO
It helps to create a FDA regulatory compliance report.

---
📊 Dataset Information

For this project, we utilized the Faulty Medical Devices - Global Dataset, which contains detailed information on device-related failures and recalls worldwide. To better understand the dataset and its context, we also referred to the[ICIJ Medical Devices Database](https://medicaldevices.icij.org/p/about) 
. This resource provides insights into device safety issues, reported failures, and regulatory actions, helping us validate and enhance our understanding of the data used in our analysis.
---
## 🚀 Features
- Data preprocessing and feature engineering for device attributes  
- Risk scoring for each device based on severity & likelihood of failure  
- Machine learning models (Logistic Regression, XGBoost, Random Forest,etc.)  
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
