# 🧠 Earthquake Magnitude Prediction & Analysis (Türkiye - 1914 to 2023)

This repository contains a complete workflow for analyzing historical earthquake data in Türkiye and reconstructing missing `Mw` (Moment Magnitude) values using machine learning.

Over 76% of `Mw` values were missing in the dataset, making traditional analysis difficult. This project uses `ML`, `xM`, and other features to predict missing values and validate them statistically and visually.

---

## 📂 Dataset

- Source: [Turkish Earthquake Records (1914–2023)](https://www.kaggle.com/datasets/ozgecinko/turkey-earthquake-data-1914-2023)
- Total records: ~50,000+
- Missing `Mw`: ~76%

---

## 🔍 Problem Statement

The dataset contains severe missing values in the `Mw` column, which is the most critical metric for evaluating earthquake strength. This project aims to:

- Predict missing `Mw` values using machine learning
- Validate predicted values using statistical methods (t-test, ANOVA)
- Perform geophysical and temporal analysis post-reconstruction

---

## ⚙️ Workflow

1. **Data Cleaning & Preprocessing**
2. **Exploratory Data Analysis**
3. **Model Training** (XGBoost Regressor)
4. **Prediction of Missing `Mw`**
5. **Statistical Validation**
6. **Visualization & Reporting**

---

## ✅ Model Performance

- **RMSE**: 0.0216  
- **R² Score**: 0.9976  
- **Estimated Accuracy**: 99.76%

---

## 📊 Key Analyses

- Earthquake frequency by year
- Strong earthquakes (Mw ≥ 5) over time
- Correlation matrix of magnitude types
- Depth vs Mw analysis
- Regional magnitude variation
- T-test & ANOVA for statistical soundness

---

## 📦 Requirements

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn xgboost scikit-learn folium
```
📌 Tools & Libraries
Python (Pandas, NumPy)

XGBoost

Scikit-learn

Seaborn, Matplotlib

SciPy

Folium (for mapping)

🤝 Contributing
This research is open and ongoing. Contributions, suggestions, or alternative modeling approaches are welcome. Feel free to fork the repo and submit a pull request!

📬 Contact
Author: Mohammed Geabel
📧 mohammed.geabel@ogr.sakarya.edu.tr
🔗 LinkedIn (optional)

📜 License
This project is licensed under the MIT License.


Let me know if you want this customized for Jupyter Notebook use, or want to include image previews and sample outputs!
