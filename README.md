# 🚗 Road Accident Severity Prediction

A Machine Learning project that predicts the severity of road accidents using historical accident records. The project analyzes driver information, road conditions, weather, vehicle details, and accident-related factors to classify accidents into different severity levels.

---

## 📌 Project Overview

Road accidents are a major public safety concern worldwide. Predicting accident severity can help emergency services, traffic authorities, and city planners respond more effectively and improve road safety.

In this project, multiple Machine Learning classification models are trained and compared to predict accident severity based on historical accident data.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Handle missing values
- Engineer meaningful features
- Encode categorical variables
- Train multiple Machine Learning models
- Compare model performance
- Identify important factors affecting accident severity
- Predict accident severity for new samples

---

## 📂 Dataset

The dataset contains historical road accident records with information related to:

- Driver Details
- Vehicle Information
- Road Conditions
- Weather Conditions
- Light Conditions
- Junction Types
- Number of Vehicles
- Number of Casualties
- Cause of Accident
- Accident Severity (Target Variable)

### Target Classes

- Slight Injury
- Serious Injury
- Fatal Injury

---

# 🛠 Technologies Used

- Python
- Jupyter Notebook

### Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📊 Project Workflow

```
Dataset

↓

Data Loading

↓

Exploratory Data Analysis (EDA)

↓

Missing Value Handling

↓

Feature Engineering

↓

Feature Selection

↓

Categorical Encoding

↓

Train-Test Split

↓

Model Training

↓

Model Evaluation

↓

Feature Importance

↓

Prediction on New Data
```

---

# 📈 Exploratory Data Analysis

The project includes:

- Dataset overview
- Shape of dataset
- Missing value analysis
- Data type inspection
- Target class distribution
- Correlation analysis
- Visualizations using Matplotlib and Seaborn

---

# ⚙ Data Preprocessing

The preprocessing pipeline includes:

- Handling missing values
- Feature engineering from Time column
- Removal of unnecessary features
- Label Encoding of categorical variables
- Feature selection
- Train-test split

---

# 🤖 Machine Learning Models

The following classification algorithms were trained and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

# 📊 Evaluation Metrics

Model performance was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

---

# 📉 Feature Importance

Random Forest Feature Importance was used to identify the most influential features affecting accident severity.

---

# 🔮 Prediction

The trained model can predict the severity of a new accident based on the provided accident information.

---

# 📁 Project Structure

```
Road-Accident-Severity-Prediction/
│
├── Road_Accident.ipynb
├── README.md
├── RTA Dataset.csv

```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Lalita0008/Road-Accident-Severity-Prediction.git
```

Move into the project directory

```bash
cd Road-Accident-Severity-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 📷 Project Outputs

The notebook generates:

- Dataset Analysis
- Missing Value Summary
- Target Distribution Graph
- Model Comparison
- Confusion Matrix
- Feature Importance Plot
- Sample Prediction

---

# 💡 Future Improvements

- Hyperparameter Tuning (GridSearchCV)
- SMOTE for Class Imbalance
- XGBoost / LightGBM
- Cross Validation
- Model Deployment using Flask/FastAPI
- Interactive Web Dashboard

---

# 📚 Learning Outcomes

Through this project, I learned:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Label Encoding
- Machine Learning Classification
- Model Evaluation
- Feature Importance Analysis
- Building an End-to-End ML Pipeline

---

# 👩‍💻 Author

**Lalita Jhapate**

B.Tech Artificial Intelligence Student

GitHub: https://github.com/Lalita0008



---

## ⭐ Thank you for taking the time to explore this project!