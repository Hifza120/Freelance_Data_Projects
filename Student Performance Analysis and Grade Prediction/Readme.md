# Student Performance Analysis & Grade Prediction

Project Overview
This project focuses on analyzing student academic performance to identify the key factors that influence final grades. The analysis includes data cleaning, exploratory data analysis (EDA), visualization, correlation analysis, outlier detection, and simple linear regression modeling.

The goal of this project is to understand how study behavior, subject-wise scores, and attendance impact overall student performance.

---

Dataset Description
The dataset contains student-related academic and behavioral information, including:
- Age
- Study time per week
- Number of failures
- Absences
- Math, Reading, and Writing scores
- Final grade (out of 100)

The raw dataset was cleaned by removing irrelevant columns and handling missing values to ensure data quality.

---

 Tools & Technologies Used
- Python
- Pandas & NumPy (Data manipulation)
- Matplotlib & Seaborn (Data visualization)
- Scikit-learn (Linear Regression)
- Jupyter Notebook
- VS Code

---

Project Workflow
1. Data Understanding & Inspection  
2. Data Cleaning and Noise Reduction  
3. Handling Missing Values  
4. Statistical Analysis (Mean, Median, Mode, Variance, Std)  
5. Outlier Detection using IQR and Boxplots  
6. Exploratory Data Analysis (Histograms & Countplots)  
7. Correlation Analysis  
8. Linear Regression Model for Grade Prediction  



 Key Findings
- Subject-wise scores (Math, Reading, Writing) have a strong positive correlation with final grades.
- Study time shows a weak positive relationship with final grades.
- Absences have a negative correlation with academic performance.
- Math score was found to be the most influential predictor of final grades.



 Visualizations
The project includes:
- Histograms for score distributions
- Count plots for age, failures, and absences
- Box plots for outlier detection
- Scatter plot showing Math Score vs Final Grade

All visual outputs are saved in the `Graphs/` directory.


 Machine Learning Model
A Simple Linear Regression model was implemented to predict final grades based on math scores.
- Train-test split: 70% / 30%
- Model evaluation using R² score and Mean Squared Error

