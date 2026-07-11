# Banking Complaint Analysis & Product Classification

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![License](https://img.shields.io/badge/License-Educational-green)

A Machine Learning and Natural Language Processing (NLP) project that analyzes consumer banking complaints to uncover meaningful insights and automatically classify complaints into financial product categories using Logistic Regression.

---

## 📌 Project Overview

Financial institutions receive thousands of customer complaints regarding banking products and services. Analyzing these complaints helps organizations identify recurring issues, improve customer experience, and make data-driven decisions.

This project uses the **Consumer Financial Protection Bureau (CFPB)** Consumer Complaint Database to:

- Perform data cleaning and preprocessing
- Conduct Exploratory Data Analysis (EDA)
- Analyze complaint trends across products, companies, and states
- Preprocess complaint narratives using NLP techniques
- Convert text into numerical features using TF-IDF
- Train a Logistic Regression model for product classification
- Evaluate model performance using classification metrics

---

## 🎯 Objectives

- Clean and preprocess consumer complaint data.
- Explore complaint patterns using visualizations.
- Analyze complaints by product, company, state, and time.
- Transform complaint narratives into numerical features.
- Build a machine learning model to classify banking products.
- Evaluate model performance using standard metrics.

---

## 📂 Dataset

This project uses the **Consumer Complaint Database** published by the **Consumer Financial Protection Bureau (CFPB)**.

The dataset contains consumer complaints related to financial products and services, including complaint narratives, submission methods, company responses, and resolution status.

### Download Dataset

Download the latest dataset from the official CFPB website:

https://www.consumerfinance.gov/data-research/consumer-complaints/

### Dataset Features

The project uses the following important fields:

- Date received
- Product
- Sub-product
- Issue
- Sub-issue
- Consumer complaint narrative
- Company
- State
- Submitted via
- Company response
- Timely response?
- Consumer disputed?

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Project Workflow

```text
Consumer Complaint Dataset
            │
            ▼
Data Cleaning & Preprocessing
            │
            ▼
Exploratory Data Analysis (EDA)
            │
            ▼
Text Preprocessing (NLP)
            │
            ▼
TF-IDF Vectorization
            │
            ▼
Train-Test Split
            │
            ▼
Logistic Regression Model
            │
            ▼
Model Evaluation
            │
            ▼
Product Prediction
```

---

## 🧹 Data Preprocessing

The following preprocessing steps are performed:

- Remove duplicate records
- Handle missing values
- Convert date columns to datetime format
- Select relevant features
- Clean complaint narratives
- Convert text to lowercase
- Remove punctuation and numbers
- Remove stop words
- Lemmatize words

---

## 📊 Exploratory Data Analysis

The notebook includes visualizations and analyses such as:

- Complaint distribution by product
- Top complaint issues
- Company-wise complaint analysis
- State-wise complaint distribution
- Monthly complaint trends
- Quarterly complaint trends
- Yearly complaint growth
- Timely response analysis
- Product vs Timely Response comparison
- Complaint issue trends over time

---

## 🤖 Machine Learning

### Text Feature Extraction

- TF-IDF (Term Frequency–Inverse Document Frequency)

### Classification Algorithm

- Logistic Regression

### Data Split

- Training Data: 80%
- Testing Data: 20%
- Stratified Train-Test Split

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

---

## 📁 Project Structure

```text
Banking-Complaint-Analysis/
│
├── Banking_Complaint_Analysis.ipynb
|__ consumer_complaints.csv
├── README.md
├── requirements.txt
```

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/ajinkya029/Complaint-Analytics-Trend-Classification.git
```

### 2. Navigate to the project directory

```bash
cd Complaint-Analytics-Trend-Classification
```

### 3. Install the required dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

1. Download the latest Consumer Complaint Dataset from the CFPB website.

2. Place the downloaded CSV file in the project directory (or update the dataset path in the notebook).

3. Launch Jupyter Notebook:

```bash
jupyter notebook Banking_Complaint_Analysis.ipynb
```

4. Run all notebook cells sequentially to:
   - Preprocess the data
   - Perform exploratory data analysis
   - Train the machine learning model
   - Evaluate the model
   - Generate predictions

---

## 📌 Future Improvements

- Hyperparameter tuning
- Compare multiple ML algorithms
- Random Forest and XGBoost implementation
- Deep Learning models (LSTM/BERT)
- Sentiment Analysis
- Topic Modeling (LDA)
- Interactive dashboard using Streamlit
- Model deployment using Flask or FastAPI

---

## 🎓 Learning Outcomes

This project demonstrates practical skills in:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Natural Language Processing (NLP)
- Feature Engineering
- Text Classification
- Machine Learning
- Model Evaluation

---

## 📜 License

This project is intended for educational and research purposes.

---

## 👨‍💻 Author

**Ajinkya Dhatrak**

GitHub: https://github.com/ajinkya029

---

## ⭐ If you found this project useful, consider giving it a star!
