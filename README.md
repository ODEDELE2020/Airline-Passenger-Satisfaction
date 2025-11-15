---

```markdown
# Project 2: Airline Passenger Satisfaction Analysis

This project analyzes airline passenger satisfaction using **data analysis and machine learning** to uncover key factors affecting customer experiences and build predictive models for airlines.

---

## Visuals & Demo

* **Project Diagram:** ![Diagram](assets/diagram.png)
* **Documentation:** [Download PDF](assets/documentation.pdf)

---

## Features
- Comprehensive **Exploratory Data Analysis (EDA)** to identify patterns and insights
- **Data cleaning, preprocessing, and feature engineering**
- **Handling missing values and outliers**
- **Machine learning models**: LightGBM, CatBoost, XGBoost
- **Hyperparameter tuning** with Optuna
- **Feature importance** using SHAP values
- Prediction and evaluation of passenger satisfaction

---

## Dataset
The dataset is available on [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction) and contains passenger feedback on various aspects such as service quality, comfort, cleanliness, and amenities.

---

## Folder Structure

```

Project-02-Airline-Passenger-Satisfaction-Analysis/
├── README.md                       # This file
├── requirements.txt                # Python dependencies
├── data/
│   ├── raw_data.csv                # Original dataset
│   └── preprocessed_data.csv       # Cleaned and preprocessed dataset
├── notebooks/
│   ├── 01_EDA_Preprocessing.ipynb  # EDA, visualization, and preprocessing
│   └── 02_Modeling_Evaluation.ipynb # Modeling, tuning, and evaluation
├── src/
│   ├── data_preprocessing.py       # Scripts for cleaning, scaling, and encoding
│   ├── feature_engineering.py      # Scripts to create new features
│   └── model_training.py           # Scripts to train and evaluate ML models
├── reports/
│   ├── figures/                    # Plots and visualizations from EDA
│   └── evaluation_metrics.md       # Model performance metrics
├── assets/
│   ├── diagram.png                 # Project overview diagram ![Diagram](assets/diagram.png)
│   ├── demo.mp4                    # Video demonstration [Watch Demo](assets/demo.mp4)
│   └── documentation.pdf           # Project documentation [Download PDF](assets/documentation.pdf)
└── models/
└── final_model.pkl             # Saved trained model for predictions

````

---

## How to Run

1. **Install Dependencies:**
```bash
pip install -r requirements.txt
````

2. **Load Dataset:**
   Place the raw dataset in the `data/` folder as `raw_data.csv`.

3. **Run Notebooks or Scripts:**

* **EDA and preprocessing:** `notebooks/01_EDA_Preprocessing.ipynb`
* **Modeling and evaluation:** `notebooks/02_Modeling_Evaluation.ipynb`

4. **Predict using Trained Model:**
   Use `models/final_model.pkl` with your own dataset for predictions.

---

## Tech Stack

* **Programming Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning Models:** LightGBM, CatBoost, XGBoost
* **Other Tools:** Optuna (Hyperparameter tuning), SHAP (Feature importance)

--

## Summary

This project provides insights into the factors influencing airline passenger satisfaction and builds robust predictive models that can help airlines improve services and enhance customer experiences.

```
