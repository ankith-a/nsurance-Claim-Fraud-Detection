# 🛡️ Insurance Claim Fraud Detection

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

An end-to-end Machine Learning project that predicts whether an insurance claim is **fraudulent or legitimate** using historical insurance claim data. This project demonstrates the complete ML lifecycle, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and performance comparison.

---

# 📌 Project Objective

Fraudulent insurance claims result in significant financial losses for insurance companies every year.

The objective of this project is to build a classification model capable of identifying suspicious insurance claims by analyzing customer, policy, and claim-related information. The developed model assists insurers in prioritizing high-risk claims for further investigation, improving operational efficiency and reducing fraud-related losses.

---

# 📊 Dataset

The dataset contains historical insurance claim records with customer, policy, and claim information.

### Dataset Includes

- Customer Information
- Policy Details
- Vehicle Information
- Incident Details
- Claim Amount
- Fraud Report Status (Target Variable)

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |
| Jupyter Notebook | Development Environment |

---

# 🔄 Project Workflow

### 1️⃣ Data Collection

- Import dataset
- Inspect structure
- Analyze feature types

### 2️⃣ Data Cleaning

- Handle missing values
- Remove duplicate records
- Encode categorical variables
- Convert data into ML-ready format

### 3️⃣ Exploratory Data Analysis

Performed analysis on:

- Fraud distribution
- Claim amount trends
- Customer demographics
- Policy characteristics
- Incident patterns

---

### 4️⃣ Feature Engineering

Applied preprocessing techniques including:

- Label Encoding
- One-Hot Encoding
- Feature Selection
- Numerical Scaling

---

### 5️⃣ Model Development

Implemented and compared multiple classification algorithms for fraud detection.

Typical models include:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost (if applicable)

---

### 6️⃣ Model Evaluation

Performance evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

# 📈 Key Insights

- Identified important features influencing fraudulent claims.
- Compared multiple machine learning algorithms.
- Evaluated classification performance using standard metrics.
- Built a predictive model capable of assisting insurance fraud investigation.

---

# 📁 Project Structure

```text
Insurance-Claim-Fraud-Detection/
│
├── notebook/
│   └── insurance_claim_fraud_detection.ipynb
│
├── data/
│   └── insurance_claims.csv
│
├── screenshots/
│   ├── fraud_distribution.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── model_comparison.png
│
├── models/
│   └── fraud_detection_model.pkl
│
├── requirements.txt
│
└── README.md
```

---

# 🚀 Future Improvements

- Deploy model using Streamlit
- Build REST API with Flask/FastAPI
- Real-time Fraud Detection Dashboard
- Hyperparameter Optimization
- Model Monitoring & Retraining
- Deep Learning-based Fraud Detection

---

# 💡 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Classification Modeling
- Model Evaluation
- Machine Learning Pipelines
- Fraud Analytics
- Data Visualization

---

# 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/Insurance-Claim-Fraud-Detection.git

# Navigate into the project directory
cd Insurance-Claim-Fraud-Detection

# Install required dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

---

# 📋 requirements.txt

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
imbalanced-learn
joblib
jupyter
```

---

# 👨‍💻 Author

**Ankith A**

BCA Graduate | Data Science & Artificial Intelligence Enthusiast

Passionate about Machine Learning, Data Analytics, AI, and Predictive Modeling.

⭐ If you found this project useful, consider giving it a Star!
