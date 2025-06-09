# ELEVATE_LAB-TASK5
# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs an in-depth exploratory data analysis (EDA) on the Titanic dataset to uncover patterns, relationships, and insights related to passenger survival.

## 📁 Files Included

- `train.csv`: Titanic dataset used for analysis
- `titanic_eda.py`: Python script with all the EDA code
- `Titanic_EDA_Summary.pdf`: PDF summary of visual and statistical findings (optional)
- `README.md`: Project overview

## 📌 Objectives

- Explore and visualize the distribution of key features
- Identify relationships between features and survival
- Use visualizations like histograms, boxplots, scatterplots, heatmaps, and pairplots
- Generate actionable insights and summarize them in a report

## 🧪 Tools & Libraries

- `Python 3.x`
- `pandas`
- `matplotlib`
- `seaborn`
- `fpdf` (for PDF report generation)

## 📊 Visualizations

The analysis includes:
- Age distribution (histogram)
- Fare distribution (boxplot)
- Survival by gender (countplot)
- Feature correlation (heatmap)
- Pairwise relationships (pairplot)
- Scatterplots between Age, Fare, Pclass, Sex, and Survival

## 🧾 Summary of Insights

- Women had higher survival rates than men.
- Higher passenger classes (1st class) had better survival chances.
- Younger passengers and those who paid higher fares were more likely to survive.
- Strong correlations exist between `Fare`, `Pclass`, and `Survived`.

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:

```bash
pip install pandas matplotlib seaborn fpdf
Run the analysis:
python titanic_eda.py

