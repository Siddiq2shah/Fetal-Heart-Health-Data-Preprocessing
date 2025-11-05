
# 🧠 ECE 443 – Data Preprocessing and Exploratory Data Analysis on Fetal & Heart Health Datasets  

This project explores data cleaning, preprocessing, and feature analysis on two biomedical datasets — the Fetal Health Classification Dataset and the Heart Failure Prediction Dataset.  
It demonstrates expertise in data analytics, data wrangling, and statistical validation using Python and Pandas, forming the foundation for predictive machine learning modeling.

---

## 🎯 Project Overview  

The objective of this exercise was to perform comprehensive exploratory data analysis (EDA) and data preprocessing on real-world clinical datasets.  
The workflow included detecting missing values, validating data consistency, normalizing continuous variables, encoding categorical data, and preparing final cleaned CSVs for downstream ML pipelines.

The notebook also emphasizes data integrity, feature transformation, and the connection between empirical risk minimization (ERM) and the Law of Large Numbers (LLN) — reinforcing fundamental statistical principles in data science.

---

## 📊 Key Data Analytics Contributions  

### 🩺 Fetal Health Classification Dataset
- Conducted EDA using Pandas to identify dataset dimensions, variable types, and data distributions.  
- Detected and replaced missing or logically inconsistent values using NaN handling and validation rules.  
- Standardized continuous features to zero mean and unit variance and replaced missing entries with category-specific medians.  
- Applied one-hot encoding to categorical variables for machine learning readiness.  
- Exported the cleaned and preprocessed data into fetal_health_dataset_processed.csv for modeling.

### ❤️ Heart Failure Prediction Dataset
- Performed data inspection to assess variable correlations and logical consistency.  
- Normalized clinical indicators (e.g., serum sodium, creatinine, ejection fraction) using z-score scaling.  
- Encoded the target variable (DEATH_EVENT) using one-hot encoding for classification models.  
- Analyzed pairwise feature correlations to identify statistically significant predictors of mortality.  
- Discussed the clinical intuition behind positive and negative correlations with health outcomes.

---

## 🧰 Tools & Technologies  

- Languages: Python (Jupyter Notebook)  
- Libraries: Pandas, NumPy, SciPy, IPython.display  
- Techniques: Data Cleaning, Normalization, Feature Engineering, One-Hot Encoding, Correlation Analysis  
- Statistical Concepts: Law of Large Numbers (LLN), Empirical Risk Minimization (ERM)

---

## 🗂️ File Structure  

```
ECE443-Data-Preprocessing-and-Analytics/
├── Exercise#1_SubmissionTemplate.ipynb     # Jupyter Notebook with all tasks and analysis
├── fetal_health_dataset_clean.csv          # Clean version of fetal dataset
├── fetal_health_dataset_dirty.csv          # Dirty version with missing/inconsistent entries
├── fetal_health_dataset_processed.csv      # Final preprocessed fetal dataset
├── heart_failure_dataset.csv               # Original heart failure dataset
├── heart_failure_dataset_processed.csv     # Final processed and encoded heart failure dataset
└── README.md                               # Documentation
```

---

## ⚙️ How to Run  

1. Open Exercise#1_SubmissionTemplate.ipynb in Jupyter Notebook or Google Colab.  
2. Run all cells sequentially to execute:
   - Data loading and exploration  
   - Cleaning and normalization  
   - Feature transformation and encoding  
   - Correlation analysis and visualization  
3. The notebook will output two cleaned CSV files ready for modeling:
   - fetal_health_dataset_processed.csv  
   - heart_failure_dataset_processed.csv  

---

## 📈 Analytical Insights  

- Normalization ensures all numerical features contribute equally to model training.  
- One-hot encoding preserves categorical structure for ML algorithms.  
- Correlation analysis reveals which physiological features most strongly influence health outcomes.  
- Demonstrates the bridge between statistical theory (LLN, ERM) and its practical implications in data analytics.

---

## 🧾 Learning Outcomes  

Through this project, the following data analytics skills were developed and reinforced:
- Applied data wrangling and statistical preprocessing techniques.  
- Connected mathematical concepts like LLN and ERM to model generalization.  
- Built reproducible data pipelines aligned with best practices in healthcare data science.  
- Prepared multiple datasets for supervised learning applications.

---

Author: Mohammad Shaheer Siddiqi  
Course: ECE 443 / 539 – Machine Learning Foundations  
Institution: Rutgers University  
Year: Fall 2025  

---

Tags: Data Analytics · Python · Pandas · Feature Engineering · Data Cleaning · Healthcare Data
