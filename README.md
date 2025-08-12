# EDA_Pima_Diabetic
🩺 Exploratory Data Analysis on Pima Indians Diabetes Dataset
This repository contains an exploratory data analysis (EDA) of the Pima Indians Diabetes dataset using Python. The goal is to understand the patterns, distributions, and relationships in the data that could affect the onset of diabetes in female Pima Indian patients.

📊 Dataset Description
The Pima Indians Diabetes dataset is sourced from the UCI Machine Learning Repository and consists of several medical predictor variables and one target variable (diabetes outcome).

Features:
Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Outcome (0: No diabetes, 1: Diabetes)

🛠️ Technologies Used
Python

Jupyter Notebook

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn

Scipy

📌 Project Workflow
1. Data Loading
Dataset imported using Pandas.

2. Initial Data Inspection
Checked for null values, datatypes, and descriptive statistics.

3. Data Cleaning
Replaced zeroes in columns like Glucose, BloodPressure, BMI etc., where 0 is not a valid measurement.

Handled missing or invalid data.

4. Univariate Analysis
Distribution plots and boxplots.

Identified outliers using IQR and boxplot visualizations.

5. Bivariate Analysis
Pairwise scatter plots.

Heatmaps for correlation.

6. Multivariate Analysis
PairGrid plots.

Distribution comparisons across outcome groups.

7. Skewness and Kurtosis
Computed to understand the shape of each variable’s distribution.

8. Outlier Detection and Handling
IQR method applied.

Boxplots created before and after outlier removal.

9. Gaussian Check
Visual methods (histogram, distplot)

Statistical tests (Shapiro/Anderson-Darling)

📈 Key Insights
Glucose, BMI, and Age show strong correlation with diabetes outcome.

Several features are right-skewed and require transformation for modeling.

Outliers are prominent in variables like Insulin and SkinThickness.

📁 Files in this Repository
File	Description
EDA on Pima diabetes.ipynb	Complete Jupyter notebook with EDA
README.md	Project overview and documentation

📌 How to Run
Clone this repo:

bash
Copy
Edit
git clone https://github.com/adarshunknown/EDA-on-Pima-Diabetic-Dataset.git
cd pima-diabetes-eda
Install dependencies:
Open the notebook:

bash
Copy
Edit
jupyter notebook "EDA on Pima diabetes.ipynb"
