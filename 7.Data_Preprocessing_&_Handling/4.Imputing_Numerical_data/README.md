# README

## Data Imputation & Visualization

This project focuses on handling missing data and performing various imputation strategies for numerical data. We explore the effects of different imputation methods on data distributions using **pandas**, **NumPy**, and **Matplotlib** in Python.

### Sections Covered:

1. Introduction to Imputation Strategies
2. Imputing Missing Values with Mean, Median, and Constant Values
3. Visualizing the Effects of Imputation with Boxplots
4. Analyzing the Impact on Variance and Distribution
5. Comparing Original and Imputed Data Distributions (KDE plots)
6. Handling Missing Data for Different Columns
7. Using ColumnTransformer for Automated Imputation
8. Evaluating Imputation Effects on Model Input

### Key Learnings So Far:
- **Imputation Strategies**: Using **mean**, **median**, and **constant values** for filling missing data in numerical columns
- **Variance and Distribution**: How imputation affects the variance and distribution of data
- **Data Visualization**: Using **Kernel Density Estimate (KDE)** and **boxplots** to visualize the effects of imputation strategies on the data
- **Boxplot Analysis**: Comparing distributions of original vs. imputed variables to assess the impact of imputation on spread, central tendency, and outliers
- **ColumnTransformer**: Automating the imputation process for multiple columns in a dataset
- **Handling Missing Data**: Understanding the impact of different imputation strategies on predictive modeling and data preprocessing

### Visualizations:
- **KDE Plots**: Visualizing the original vs. imputed distributions for `Age` and `Fare`
- **Boxplots**: Comparing the distributions of original and imputed `Age` and `Fare` variables
- **Variance Analysis**: Understanding how imputation with mean and median affects the variance of the data

### Useful Links:
- **Video Link**: https://youtu.be/mCL2xLBDw8M

### How to Run:
1. Install the necessary packages via `requirements.txt`
2. Follow the Jupyter notebook or Python scripts for step-by-step explanations and code

### Requirements:
- Python 3.x
- Pandas library
- NumPy library
- Matplotlib library
- Scikit-learn library (for imputation and data splitting)

---