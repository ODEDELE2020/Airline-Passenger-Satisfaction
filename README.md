---

# ✅ **Final README.md – Project 2: Airline Passenger Satisfaction Analysis**

````markdown
# Project 2: Airline Passenger Satisfaction Analysis

This project analyzes airline passenger satisfaction using **data analysis and machine learning** to uncover key factors affecting customer experiences and build predictive models for airlines.

---

## 📹 Visuals & Demo

- **Project Diagram:**  
  ![Diagram](assets/diagram.png)

- **Demo Video:**  
  [▶️ Watch Demo](assets/demo.mp4)

- **Full Documentation:**  
  [📄 Download PDF](assets/documentation.pdf)

---

## 🚀 Features

- Comprehensive **Exploratory Data Analysis (EDA)** to identify trends and insights  
- **Data cleaning, preprocessing, and feature engineering**  
- **Handling missing values and outliers**  
- Machine learning models: **LightGBM, CatBoost, XGBoost**  
- **Hyperparameter tuning** using Optuna  
- **SHAP** for feature importance interpretation  
- End-to-end pipeline for prediction and performance evaluation  

---

## 📊 Dataset

Dataset used: **Airline Passenger Satisfaction**  
Available on Kaggle:  
https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction

It contains passenger feedback on service, comfort, on-board experience, and other satisfaction-related attributes.

---

## 📁 Folder Structure

```plaintext
Project-02-Airline-Passenger-Satisfaction-Analysis/
│
├── README.md                       # Project documentation
├── requirements.txt                # Python dependencies
│
├── data/
│   ├── raw_data.csv                # Original dataset
│   └── preprocessed_data.csv       # Cleaned/preprocessed dataset
│
├── notebooks/
│   ├── 01_EDA_Preprocessing.ipynb  # EDA + preprocessing workflow
│   └── 02_Modeling_Evaluation.ipynb # Model building + evaluation
│
├── src/
│   ├── data_preprocessing.py       # Cleaning, scaling, encoding functions
│   ├── feature_engineering.py      # Custom feature creation
│   └── model_training.py           # Model training + metrics
│
├── reports/
│   ├── figures/                    # Plots and visualizations
│   └── evaluation_metrics.md       # Model performance summary
│
├── assets/
│   ├── diagram.png                 # Overview diagram
│   ├── demo.mp4                    # Video demonstration
│   └── documentation.pdf           # Project documentation
│
└── models/
    └── final_model.pkl             # Saved trained model
````

---

## 🧪 How to Run the Project

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Add Dataset

Place the raw dataset in the `data/` folder:

```
data/raw_data.csv
```

### 3. Run Notebooks or Scripts

* **EDA & preprocessing:**
  `notebooks/01_EDA_Preprocessing.ipynb`

* **Modeling & evaluation:**
  `notebooks/02_Modeling_Evaluation.ipynb`

### 4. Make Predictions Using the Trained Model

Use:

```
models/final_model.pkl
```

Load it in your script to generate predictions on new passenger data.

---

## 🛠 Tech Stack

**Languages:**

* Python

**Libraries:**

* Pandas
* NumPy
* Matplotlib
* Seaborn

**Machine Learning Models:**

* LightGBM
* CatBoost
* XGBoost

**Additional Tools:**

* Optuna (hyperparameter optimization)
* SHAP (feature importance explainability)

---

## 📌 Summary

This project provides insights into **which factors most strongly influence airline passenger satisfaction**, enabling airlines to:

* Improve service quality
* Enhance customer experience
* Optimize operations
* Predict satisfaction levels using ML models

The analysis combines **EDA**, **feature engineering**, and **advanced machine learning techniques** for a complete end-to-end workflow.

```

---
```
