# EN3150 Assignment 01  

Learning from Data and Linear Models for Regression  
B.Sc. Engineering, Semester 05  
Department of Electronic & Telecommunication Engineering  
University of Moratuwa  

---

## 📌 Overview
This repository contains the work for **EN3150 Assignment 01**, which covers:
- Linear regression and the effect of outliers  
- Robust loss functions and model comparison  
- Loss function selection for regression vs classification  
- Feature preprocessing and scaling  

The assignment is implemented in **Jupyter notebooks**, with plots and results saved into structured folders, and a final **LaTeX report**.

---

## 📂 Repository Structure
```text
EN3150-ASSIGNMENT-01/
│
├── assignment_01/
│   ├── data/                  # (Optional) any raw input data
│   ├── notebooks/             # Jupyter notebooks for each part
│   │   ├── linear_regression.ipynb
│   │   ├── losses.ipynb
│   │   └── pre_processing.ipynb
│   └── report/                # Final LaTeX report + compiled PDF
│       ├── report.tex
│       └── report.pdf
│
├── results/                   # Generated plots & CSVs
│   ├── q1/ 
│   ├── q2/
│   │   ├── mse_vs_predictions.png
│   │   ├── bce_vs_predictions.png
│   │   └── losses.csv
│   └── q3/
│
├── src/                       # (Optional) reusable Python scripts
│
├── .gitignore                 # Ignored files (outputs, cache, etc.)
├── requirements.txt           # Python dependencies
├── LICENSE
└── README.md                  # This file
