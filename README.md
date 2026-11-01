<div align="center">

# ⚾ Baseball Player Performance and Salary Analysis

### Exploring Baseball Performance Metrics and Salary Prediction Using Machine Learning

A data science project that analyzes baseball player performance statistics and predicts salaries using Exploratory Data Analysis (EDA) and Multiple Linear Regression.

</div>

---

## 📖 Project Overview

This project investigates the relationship between baseball player performance metrics and salary outcomes. Using historical baseball player statistics, the analysis explores how offensive, defensive, and career performance indicators contribute to player compensation.

The project follows a complete data science workflow, including data cleaning, visualization, statistical exploration, feature engineering, machine learning, and model evaluation.

---

## 🎯 Objectives

- Explore and understand the baseball player dataset
- Perform data quality assessment and cleaning
- Analyze salary trends and player performance metrics
- Visualize relationships between features and salary
- Build a salary prediction model using Multiple Linear Regression
- Evaluate model performance using regression metrics
- Generate actionable insights from the data

---

## 📊 Dataset Summary

| Feature | Value |
|----------|--------:|
| Records | 263 |
| Variables | 21 |
| Missing Values | 0 |
| Target Variable | Salary |

### Included Features

- Batting Statistics
- Career Performance Statistics
- Defensive Statistics
- League Information
- Salary Information

---

## 🔍 Exploratory Data Analysis

The exploratory analysis included:

- Dataset structure inspection
- Summary statistical analysis
- Missing value verification
- Salary distribution analysis
- Feature relationship exploration
- Categorical variable analysis

### Key Findings

✅ The dataset contains **263 complete observations**

✅ No missing values were found

✅ Player salaries vary significantly across the dataset

✅ Career performance metrics show stronger relationships with salary than individual season statistics

✅ Salary distribution is positively skewed, indicating a small number of very highly paid players

---

## 🤖 Machine Learning Model

### Multiple Linear Regression

A Multiple Linear Regression model was developed to predict player salaries based on performance statistics.

### Data Preparation

- Removed player names
- Encoded categorical variables using one-hot encoding
- Split data into training and testing datasets
- Trained a regression model using Scikit-Learn

---

## 📈 Model Results

### Performance Metrics

| Metric | Score |
|----------|----------:|
| Mean Absolute Error (MAE) | 211.12 |
| Root Mean Squared Error (RMSE) | 358.17 |
| R² Score | 0.2907 |

### Interpretation

- The model explains approximately **29.1% of the variation in player salaries**.
- Player performance statistics provide useful predictive information.
- Additional factors not included in the dataset likely influence salary decisions, including:
  - Contract negotiations
  - Team budgets
  - Market value
  - Awards and recognition
  - Player popularity

Although the model has moderate predictive power, it demonstrates that baseball performance metrics contribute meaningfully to salary estimation.

---

## 📊 Visualizations

The project includes:

- Salary Distribution Histogram
- Descriptive Statistical Analysis
- Actual vs Predicted Salary Scatter Plot
- Feature Exploration and Analysis

These visualizations provide insight into salary patterns and model performance.

---

## 🛠 Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Environment

- Kaggle Notebooks
- Google Colab
- GitHub

---

## 📂 Repository Structure

```text
baseball-player-performance-and-salary-analysis/
│
├── README.md
├── LICENSE
├── .gitignore
├── Baseball_Player_Performance_and_Salary_Dataset.ipynb
├── Baseball.xlsx
└── multiple-regression.pdf
```

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/Bilalabdulkadir/baseball-player-performance-and-salary-analysis.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

### Run Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## 📌 Conclusion

This project demonstrates how machine learning can be applied to sports analytics by modeling the relationship between player performance and salary. Through exploratory data analysis and multiple linear regression, the study identified meaningful relationships between performance metrics and compensation.

The model achieved an R² score of **0.2907**, showing that performance metrics explain part of salary variation while highlighting opportunities for future improvement using more advanced machine learning techniques such as Random Forests, Gradient Boosting, and XGBoost.

---

## 🔮 Future Improvements

- Random Forest Regression
- XGBoost Regression
- Feature Importance Analysis
- Cross-Validation
- Hyperparameter Tuning
- Advanced Statistical Modeling

---

## 👨‍💻 Author

**Bilal Abdulkadir Muhammed**

- GitHub: https://github.com/Bilalabdulkadir
- Kaggle: https://www.kaggle.com/bilalabdulkadir1
- LinkedIn: https://www.linkedin.com/in/bilalabdulkadirmuhammed/

---

## 📜 License

This project is licensed under the MIT License.

