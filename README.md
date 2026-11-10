content = """# M115 Lab 1 – Phishing URL Detection

## Project Overview
This project focuses on phishing URL detection using Machine Learning and the PhiUSIIL dataset. It includes data analysis, Logistic Regression, feature selection, and SHAP explainability.

## Academic Information
- **University:** ENSIASD Taroudant – Ibn Zohr University
- **Module:** M115 – AI & Intelligent Systems
- **Instructor:** Prof. Sara EL-ATEIF
- **Academic Year:** 2026–2027
- **Student:** Mohamed Es-saih

## Dataset
**PhiUSIIL Phishing URL Dataset**
- 235,795 URLs
- 56 features
- Target: Phishing (1) / Legitimate (0)

[Dataset on Kaggle](https://www.kaggle.com/datasets/kaggleprollc/phishing-url-websites-dataset-phiusiil)

## Tools & Technologies
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SHAP
- Kaggle Notebooks

## Lab Exercises
1. Data Quality Inspection
2. Exploratory Data Analysis (EDA)
3. Feature Correlation
4. Data Splitting and Scaling
5. Logistic Regression Model Comparison
6. L1 Regularization
7. Coefficients and Odds Ratios
8. Global SHAP Explanations
9. Local SHAP Waterfall Plots
10. SOC Decision Threshold Analysis

## Kaggle Submission
Add your Kaggle notebook link here when it is published.

## Project Structure
```text
Lab-01-Phishing-Detection/
├── M115_Lab1_Mohamed_Essaih.ipynb
├── Dataset/
│   └── PhiUSIIL_Phishing_URL_Dataset.csv
└── README.md
```

## Author
**Mohamed Es-saih**

*Master in Intelligent Systems and Cyber Defense – ENSIASD Taroudant*
"""
output_path = "/mnt/data/README.md"
with open(output_path, "w", encoding="utf-8") as f:
    f.write(content)
print(output_path)
