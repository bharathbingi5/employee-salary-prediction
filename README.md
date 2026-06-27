# employee-salary-prediction
employee salary prediction
1 Project Overview

This project predicts an employee’s salary using Machine Learning based on employee details such as age, gender, job title, years of experience, and education level.

The main objective is to build a salary prediction system that helps estimate salary using historical employee data. A Random Forest Regressor model was used because it provides high accuracy for regression problems.

This project was developed in Google Colab using Python.

2.Dataset Generation / Loading Process
Dataset source: Kaggle
File used: Employers_data.csv
Total records: 10,000
Total columns: 10
Dataset Features
Employee_ID
Name
Age
Gender
Department
Job_Title
Experience_Years
Education_Level
Location
Salary (Target Variable)
Data Preprocessing

3.Steps performed:

Loaded dataset using Pandas
Checked dataset shape and column names
Checked missing values
Removed duplicate records
Converted categorical values into numerical values using Label Encoding
Performed data visualization for analysis
Libraries Used
pandas
numpy
matplotlib
seaborn
scikit-learn
IPython
Purpose of Libraries
Pandas → Data loading & manipulation
NumPy → Numerical calculations
Matplotlib → Graph plotting
Seaborn → Advanced visualization
Scikit-learn → Machine learning model building
IPython → Display outputs in Colab
Steps to Run the Project
Step 1: Install Required Libraries
pip install pandas numpy matplotlib seaborn scikit-learn
Step 2: Open Google Colab / Jupyter Notebook
Step 3: Upload Dataset

4.Upload:

Employers_data.csv
Step 4: Run Data Preprocessing
Handle missing values
Remove duplicates
Encode categorical columns
Step 5: Train Model

Split dataset:

80% Training Data
20% Testing Data

5.Train using:

RandomForestRegressor()
Step 6: Evaluate Model

Check:

MAE
RMSE
R² Score
Step 7: Predict Salary

Run interactive salary prediction system and provide employee details.

Key Insights from Analysis
Experience strongly affects salary
Employees with more years of experience earn higher salaries.
Job Title impacts salary significantly
Managers and senior roles receive higher salaries than interns or analysts.
Education level matters
Higher education generally leads to better salary.
Strong positive correlation found between:
Salary & Experience
Salary & Age
Salary & Education Level
Gender and location showed relatively lower impact on salary prediction.
Model Performance Summary

6.Model Used:

Random Forest Regressor

Performance Metrics:

MAE (Mean Absolute Error): 3607.975
RMSE (Root Mean Square Error): 4517.26
R² Score: 0.9903
Interpretation
Low MAE and RMSE indicate small prediction errors.
R² = 0.9903 (~99%) means the model predicts salary with very high accuracy.
7.Conclusion

The Employee Salary Prediction system successfully predicts salaries with high accuracy using machine learning. The Random Forest model performed extremely well and can be used for salary estimation based on employee details.

8.Future Improvements
Deploy as a web app using Flask/Streamlit
Use larger real-world datasets
Add more features like:
Skills Score
Certifications
Company Type
Performance Rating

