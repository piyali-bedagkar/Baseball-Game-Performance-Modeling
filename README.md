# ⚾ UMD Baseball Game Analysis & Outcome Prediction

A comprehensive data-driven analysis of the University of Maryland Terrapins baseball team (1999–2023), featuring exploratory visualizations, statistical trends, and predictive modeling using Logistic Regression and Random Forest to forecast game outcomes.

---

### 📌 Project Overview

This project analyzes 25 years of UMD baseball data to uncover patterns in game results, location-based performance, and seasonal trends. It also builds machine learning models to predict outcomes of future games, providing insights for coaches, analysts, and fans.

---

### 🎯 Objectives

- Identify correlated features that impact win/loss outcomes
- Analyze location-based performance trends (Home, Away, Neutral)
- Forecast 2024 game results using logistic regression and random forest
- Visualize long-term trends in win rate and scoring

---

### 🧠 Key Highlights

- 📊 **Exploratory Data Analysis (EDA)**:  
  Visualized win/loss percentages by weekday, home vs. away stats, and scoring trends from 1999–2023.

- 📈 **Statistical Reports**:  
  Included year-wise average scores, win rates, and validation of data consistency between individual game logs and yearly summaries.

- 🤖 **Predictive Models**:  
  - **Model 1:** Logistic Regression  
  - **Model 2:** Random Forest Classifier  
  - Achieved up to **60% accuracy** in predicting early 2024 games

- 📉 **Performance Metrics**:  
  - Accuracy, precision, recall, ROC-AUC  
  - Random Forest had better predictive confidence  
  - Logistic Regression showed moderate AUC (~0.60)

---

### 🔍 Key Insights

- 📅 **Weekday Advantage**:  
  UMD had highest win rate on Wednesdays (70.8%) and lowest on Sundays (29.2%).

- 🏟️ **Location-Based Performance**:  
  Team performed best at **Neutral** locations, worst **Away**.

- 📊 **Stat Trends**:  
  - Gradual improvement in win rate from 1999 to 2023  
  - Highest win rate in **2022 (77.4%)**  
  - Consistency in recent years signals strong team development

- 📈 **2024 Prediction Accuracy**:  
  - Logistic Regression: 2/5 correct (40%)  
  - Random Forest: 3/5 correct (60%)

---

### 🛠️ Tools & Libraries

- `Python`
- `pandas`, `numpy` — data preprocessing
- `scikit-learn` — modeling & evaluation
- `matplotlib` — visualizations
