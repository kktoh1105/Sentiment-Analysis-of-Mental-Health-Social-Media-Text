# Sentiment Analysis of Mental Health Social Media Text

This repository contains the complete files for my final year project, which focuses on sentiment analysis using machine learning, deep learning, and transformer-based models. The goal is to analyze mental health-related social media posts and classify them based on emotional and psychological states.

---

## 📁 Project Structure

.
├── code/ # All model training and prediction notebooks
└── dataset/ # Datasets used in this project (from Kaggle)


## 📂 `code/` Folder

This directory contains all experiment-related files, including model training and prediction generation notebooks. It is organized into three subfolders: `Dataset1`, `Dataset2`, and `Dataset3`.

### 📌 Contents

#### 1. **Model Training Notebooks**
- Format: `Model Name (Model Training).ipynb`
- Includes training code for traditional ML, CNN-BiLSTM, and BERT models.
- Notably, `D1.ML.ipynb` trains four classical machine learning models.

#### 2. **Prediction CSV Generation Notebooks**
- Format: `Model Name (Generate Prediction CSV).ipynb`
- These notebooks load trained models, perform inference, and export results to `.csv`.

#### 3. **Prediction Results**
Each output CSV contains:
- Input text
- Ground truth label
- Predicted label

Models evaluated:  
`Extra Trees Classifier`, `CNN-BiLSTM`, and `BERT`

---

## 📂 `dataset/` Folder

This folder includes all datasets used for model training and evaluation. All datasets were sourced from Kaggle and are provided in `.csv` format for convenience.

### 📌 Datasets

1. **Sentiment Analysis for Mental Health**  
   📎 https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health

2. **Mental Health [Sentiment Analysis] Data**  
   📎 https://www.kaggle.com/datasets/sujaykapadnis/mental-health-insights-data

3. **Mental Health Support Feature Analysis**  
   📎 https://www.kaggle.com/datasets/thedevastator/mental-health-support-feature-analysis  
   ⚠️ *Note: Only a subset of this dataset was used in the project.*

---

## 💻 Technologies Used

- Python
- Jupyter Notebook
- Scikit-learn
- Keras (TensorFlow)
- Hugging Face Transformers
- Pandas, NumPy, Matplotlib

---

## 📊 Task Overview

- **Text Preprocessing**
- **Model Training** (Traditional ML,CNN,BiLSTM, CNN-BiLSTM, BERT, BERT-BiLSTM)
- **Prediction & Evaluation**
- **CSV Output Generation**

---


## 📜 License

This project is for academic and research purposes only. Datasets belong to their respective Kaggle  contributors.
