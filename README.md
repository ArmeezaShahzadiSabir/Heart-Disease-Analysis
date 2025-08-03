# Heart Disease Indicators Analysis

![GitHub last commit](https://img.shields.io/github/last-commit/ArmeezaShahzadiSabir/heart-disease-analysis) 
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)

Statistical analysis of CDC BRFSS 2020 data to identify heart disease risk factors.

## 📌 Project Overview
- **Objective**: Identify key indicators of heart disease using statistical methods
- **Dataset**: [CDC BRFSS 2020](https://www.kaggle.com/datasets/bhaveshmisra/heart-disease-indicators)
- **Techniques Used**:
  - Descriptive statistics (mean, median, IQR)
  - Hypothesis testing (t-tests, chi-square, ANOVA)
  - Data visualization (Seaborn/Matplotlib)

## 🛠️ Installation
```bash
git clone https://github.com/yourusername/heart-disease-analysis.git
cd heart-disease-analysis
pip install -r requirements.txt
```

## 📊 Key Findings
- Smokers have 2.3x higher odds of heart disease (χ² p<0.001)
- BMI is significantly higher in heart disease patients (t-test p=0.02)
- Age group 65+ shows highest prevalence (ANOVA p<0.001)

## 🧑‍💻 How to Run
- Open ```notebooks/Heart_Disease_Analysis.ipynb in Jupyter```
- Run cells sequentially

## 📂 File Structure

Heart-Disease-Analysis/
│
├── data/                    # Raw and processed data

│   ├── heart_disease_indicators.csv   # Original dataset

│   └── cleaned_data.csv     # Cleaned dataset (optional)

│

├── notebooks/               # Jupyter notebooks

│   └── Heart_Disease_Analysis.ipynb   # Main analysis notebook

│

├── reports/                 # Generated reports/insights

│   ├── EDA_Summary.md       # Key exploratory findings

│   └── Statistical_Report.md # Hypothesis test results

│

├── visuals/                 # Saved visualizations

│   ├── bmi_vs_heart_disease.png

│   ├── physical_activity_vs_heart_disease.png

│   ├── correlation_heatmap.png

│   └── smoking_vs_heartdisease.png

│

├── README.md                # Project overview

└── requirements.txt         # Python dependencies

## 🤝 Contributing
- Pull requests welcome! For major changes, please open an issue first.
