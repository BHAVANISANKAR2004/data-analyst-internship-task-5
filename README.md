TASk 5: Exploratory Data Analysis - Titanic Dataset

Overview

This repository contains my submission for **Task 5** of the Data Analyst Internship Program. The objective was to perform Exploratory Data Analysis (EDA) on the Titanic dataset using Python, with a focus on data understanding, cleaning, and visualization.



About the Dataset

The Titanic dataset contains information about passengers aboard the Titanic, including their age, gender, class, fare, survival status, and more. It is a popular dataset used for introductory machine learning and data analysis tasks.

Tools and Libraries Used

- Python 3
- pandas
- matplotlib
- seaborn
- Jupyter Notebook / Google Colab

---

## Steps Performed

1. **Loading the Data**
   - Loaded the dataset using pandas.
   - Displayed initial rows using `.head()` to understand the structure.

2. **Data Cleaning**
   - Checked for null values using `.isnull().sum()`.
   - Dropped or filled missing values in columns like Age, Cabin, and Embarked.
   - Verified data types and converted if needed.

3. **Univariate Analysis**
   - Analyzed individual variables such as Age, Sex, Fare, Pclass using histograms and count plots.

4. **Bivariate Analysis**
   - Explored relationships between variables such as Sex vs Survival, Pclass vs Survival.

5. **Multivariate Analysis**
   - Used heatmaps and pairplots to analyze relationships between three or more variables.

6. **Correlation Analysis**
   - Generated a correlation matrix to identify relationships between numerical variables.

---

## Key Insights

- Female passengers had a higher survival rate compared to male passengers.
- Passengers in first class had better chances of survival.
- Age and Fare had some outliers and missing values.
- The dataset had several null values, especially in the Cabin column.

---

## Files Included

- `Titanic_EDA.ipynb`: Jupyter Notebook with full analysis.
- `Titanic_EDA_Report.pdf`: PDF version of the notebook.
- `Titanic-Dataset.csv`: Dataset used for the analysis.
- `README.md`: Description and overview of the project.

---
Conclusion

This task was a valuable hands-on opportunity to practice data cleaning, visualization, and extracting meaningful insights from real-world data. It forms a strong foundation for further machine learning and data-driven decision making.
