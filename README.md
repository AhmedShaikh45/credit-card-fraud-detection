# 💳 Credit Card Fraud Detection

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using data analysis and machine learning techniques. The dataset is highly imbalanced, so special handling is applied to correctly identify fraud cases.

The notebook demonstrates a complete workflow including data exploration, preprocessing, handling class imbalance, model training, and evaluation.

---

## 📂 Dataset Description
- The dataset contains credit card transaction records
- Target column: `Class`
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction
- Features include anonymized numerical variables and the `Amount` field

> Fraudulent transactions are extremely rare, making this a class imbalance problem.

---

## 🧪 Steps Performed

### 1️⃣ Importing Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

### 2️⃣ Data Loading & Inspection
- Load the dataset
- Check shape, columns, and summary statistics
- Separate legitimate and fraudulent transactions

---

### 3️⃣ Exploratory Data Analysis (EDA)
- Compare transaction amounts for fraud and legitimate cases
- Analyze feature distributions based on transaction class

---

### 4️⃣ Handling Class Imbalance
- Fraud cases are very limited compared to legitimate ones
- Under-sampling technique is applied:
  - Randomly sample legitimate transactions
  - Combine them with all fraud transactions
- Creates a balanced dataset for model training

---

### 5️⃣ Data Preparation
- Separate features (`X`) and target (`y`)
- Split data into training and testing sets

---

### 6️⃣ Model Training
- Train a machine learning model on the balanced dataset
- Model learns patterns to classify transactions as fraud or legitimate

---

### 7️⃣ Model Evaluation
- Accuracy score
- Classification report
- Performance analysis on test data

---

## 📊 Results
- The model successfully identifies fraudulent transactions
- Balancing the dataset improves fraud detection performance
- Demonstrates real-world challenges of imbalanced classification problems

---

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 📁 Project Structure
Credit-Card-Fraud-Detection/
│
├── CREDIT CARD FRAUD DETECTION.ipynb
└── README.md


---

## 🚀 How to Run
1. Clone the repository
2. Open the notebook using Jupyter Notebook
3. Run all cells sequentially

---

## 📌 Key Learnings
- Handling imbalanced datasets
- Under-sampling techniques
- Fraud detection workflow
- Machine learning model evaluation

---


## 👤 Author
Ahmed  
Data Science Enthusiast | Aspiring Data Scientist
