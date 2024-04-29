Overview
The problem aims early detection of employee who is likely to leave the organization.
Employee churn, represents the phenomenon in which employees leave a company either voluntarily or involuntarily. 
High employee churn rates can have detrimental effects on an organization.
For that, employee retention is a critical concern for organizations, as high employee turnover can lead to increased recruitment costs, loss of institutional knowledge, and a negative impact on overall productivity.

Dataset
Satisfaction Level: A measure of employee job satisfaction.
Last Evaluation: The most recent performance evaluation score.
Number of Projects: The number of projects each employee has been involved in.
Average Monthly Hours: The average number of hours worked per month.
Time Spent in the Company: The duration an employee has worked in the organization.
Promotion in the Last 5 Years: Whether an employee has been promoted in the last five years (binary feature).
Work Accident: Whether an employee involved in any work accident or not (binary feature).
Department: The department in which the employee is employed.
Salary: The salary level of the employee(High, Medium & Low).
Left: A binary variable indicating whether the employee left the company (our target variable).

Data Preprocessing
Salary Categorization: The "Salary" column was transformed into a categorical variable and encoded into numerical values (e.g., low, medium, high) to facilitate machine learning algorithms' utilization.
Department One-Hot Encoding: To make the "Department" feature suitable for machine learning models, it was one-hot encoded into binary columns representing each department.

Usage
Navigate to the notebooks directory and run the Jupyter notebooks to explore the data and train the models.
Use the trained models to make predictions on new data or evaluate their performance using the provided notebooks.

Results
The project achieves an accuracy of 95% in predicting employee churn, with the following key insights:
Feature importance analysis
Prediction performance metrics (precision, recall, F1-score)

Contributors
Harshil Vekaria (@01441789)
Bala Krishna Mundru (@01449014)
Phani Madhav Addanki (@01443682)
