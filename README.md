# Clinical Diabetes Dataset Cleaning & Visualization Pipeline (Palestine)

A reproducible Python data preprocessing and **exploratory data analysis (EDA) & visualization pipeline** designed to clean, validate, and analyze a real-world clinical diabetes dataset collected in Palestine (`Raw_Data.csv`).

---

## 📋 Project Overview

Real-world clinical datasets from healthcare facilities in Palestine often contain manual entry variations, formatting inconsistencies, and corrupted records. This project not only cleans and standardizes electronic health records into `NRaw_Data.csv` but also builds **professional clinical visualizations** using **Matplotlib** and **Seaborn** to uncover health trends, biomarker correlations, and diagnostic breakdowns.

---

## 📊 Visualization Highlights in the Notebook

1. **HbA1c Distribution & Clinical Thresholds:** Histogram with KDE curves marking established prediabetes (5.7%) and diabetes (6.5%) clinical cutoff lines.
2. **Biomarker Correlation Scatter Plot:** Scatter plot analyzing the relationship between Fasting Blood Sugar (`FastingBloodSugarResult`) and HbA1c levels (`HBA1CResult`), color-coded by diagnostic category.
3. **Demographic Breakdown:** Grouped bar charts comparing diabetes diagnostic categories across patient gender demographics.

---

## 📂 Repository Structure

```text
diabetes-data-cleaning-pipeline/
│
├── data/
│   ├── Raw_Data.csv                 # Original raw clinical dataset (Palestine)
│   └── NRaw_Data.csv                # Cleaned & standardized output dataset
│
├── notebooks/
│   └── diabetes_preprocessing.ipynb # Data cleaning & EDA visualization pipeline
│
├── .gitignore                       # Git ignore rules for Python & Jupyter
├── README.md                        # Project documentation
└── requirements.txt                 # Python package dependencies
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/diabetes-data-cleaning-pipeline.git
cd diabetes-data-cleaning-pipeline
```

### 2. Install Dependencies
```bash
pip import -r requirements.txt
```
*(Note: requires `pandas`, `numpy`, `matplotlib`, `seaborn`, and `jupyter`)*

### 3. Run the Pipeline & Visualizations
Launch Jupyter Notebook or VS Code and run all cells in `notebooks/diabetes_preprocessing.ipynb`:
```bash
jupyter notebook notebooks/diabetes_preprocessing.ipynb
```

---

## 🧰 Tech Stack

- **Language:** Python 3.10+
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / VS Code
