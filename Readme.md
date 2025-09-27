# Predict the Introverts from the Extroverts 🎭

This repository contains our solution for the [Kaggle Playground Series - Season 5, Episode 7](https://www.kaggle.com/competitions/playground-series-s5e7) competition.  

We participated as a team and achieved a **final rank of 525 out of 4329 teams**. 🚀  

---

## 📌 Competition Overview
The task was to build a machine learning model to predict whether a person is an **introvert** or an **extrovert** based on provided features.  
This was a **binary classification problem**, evaluated using **log loss**.

---

## 🛠️ Repository Structure
- `notebooks/` – Jupyter notebooks used for data exploration, feature engineering, and model training.
- `src/` – Scripts for preprocessing, model building, and evaluation.
- `requirements.txt` – Python dependencies required to run the code.
- `README.md` – Project documentation (this file).

---

## ⚙️ Approach
1. **Exploratory Data Analysis (EDA):**  
   - Inspected feature distributions and outliers.  
   - Checked correlations between variables.  

2. **Preprocessing & Feature Engineering:**  
   - **Feature Scaling:** Standardized numerical features for model stability.  
   - **Feature Engineering:** Created interaction features and transformed skewed variables.  
   - **Class Imbalance:** Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance introvert vs extrovert classes.  

3. **Modeling:**  
   - Tried multiple classifiers: Logistic Regression, Random Forest, XGBoost, LightGBM.  
   - Performed hyperparameter tuning with cross-validation.  

4. **Ensembling:**  
   - Combined top-performing models for final submission.  

---

## 📊 Results
- Achieved **Top 12%** of the leaderboard.  
- Final Rank: **525 / 4329**.  

---

## 🚀 How to Run
Clone this repository and install dependencies:

```bash
git clone https://github.com/RafinEazdan/Predict-Introverts-Extroverts-Kaggle-Competition.git
cd Predict-Introverts-Extroverts-Kaggle-Competition
pip install -r requirements.txt