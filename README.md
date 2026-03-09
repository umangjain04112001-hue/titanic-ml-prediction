# 🚢 Titanic Survival Prediction

![Python](https://img.shields.io/badge/Python-3.9-blue) ![ML](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

A machine learning project that predicts whether a passenger survived the Titanic disaster based on features like age, gender, class, and more.

---

## 📌 Project Overview

| | |
|---|---|
| **Type** | Binary Classification |
| **Algorithm** | Random Forest Classifier |
| **Dataset** | Titanic (via Seaborn) |
| **Accuracy** | ~82% |

---

## 🎯 Objective

Build a supervised ML model that predicts passenger survival (1 = Survived, 0 = Did Not Survive) using historical Titanic passenger data.

---

## 📊 Features Used

| Feature | Description |
|---------|-------------|
| `pclass` | Passenger class (1st, 2nd, 3rd) |
| `sex` | Gender (encoded: male=1, female=0) |
| `age` | Age in years |
| `sibsp` | # of siblings/spouses aboard |
| `parch` | # of parents/children aboard |
| `fare` | Ticket fare |
| `embarked` | Port of embarkation |
| `family_size` | Total family members (engineered) |
| `is_alone` | Traveling alone? (engineered) |

---

## 🔧 Tech Stack

- **Python 3.9**
- **Pandas** — Data manipulation
- **NumPy** — Numerical operations
- **Matplotlib / Seaborn** — Data visualization
- **Scikit-learn** — Machine learning

---

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/umangjain04112001-hue/titanic-ml-prediction.git
cd titanic-ml-prediction
```

2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook titanic_survival_prediction.ipynb
```

4. Run all cells top to bottom ✅

---

## 📈 Results

- **Model Accuracy:** ~82%
- **Top Features:** Gender, Fare, Age, Passenger Class
- **Key Finding:** Women and 1st class passengers had significantly higher survival rates

---

## 📁 Project Structure

```
titanic-ml-prediction/
│
├── titanic_survival_prediction.ipynb   # Main notebook
├── titanic_analysis.png                # EDA visualizations
├── model_results.png                   # Model evaluation charts
└── README.md                           # Project documentation
```

---

## 🧠 What I Learned

- Exploratory Data Analysis (EDA)
- Handling missing values
- Feature engineering
- Training and evaluating a Random Forest model
- Interpreting feature importance

---

## 👤 Author

**Umang Jain**  
GitHub: [@umangjain04112001-hue](https://github.com/umangjain04112001-hue)

---
*First ML project as part of my data science learning journey.*
