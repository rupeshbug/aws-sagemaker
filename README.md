# AWS SageMaker Mobile Price Prediction 📱

This project demonstrates an **end-to-end machine learning pipeline** on **AWS SageMaker** — from data preprocessing to model deployment.

The goal is to build and deploy a **Random Forest classifier** that predicts the **price range of mobile phones** based on hardware specifications such as battery power, RAM, and screen resolution.

---

## 🚀 Project Overview

**Problem:** Predict the price range (0–3) of mobile phones using provided features.  
**Algorithm:** Random Forest Classifier  
**Cloud Platform:** AWS SageMaker  
**Language:** Python  

---

## ⚙️ Setup Virtual Environment

It is recommended to use a virtual environment to manage dependencies.

```bash
# Create a new conda environment with Python 3.9
conda create -p myvenv python=3.11

# Activate the environment
conda activate ./myvenv

# Install dependencies
pip install -r requirements.txt
```

---

## 🧩 AWS Services Used
- **S3** — Store dataset and trained model artifacts  
- **SageMaker Notebook** — Data preprocessing and model training  
- **SageMaker Training Job** — Model training at scale  
- **SageMaker Endpoint** — Real-time inference  
- **IAM** — Secure permissions between services  

---