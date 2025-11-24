# Hospital Data Analysis using Python, SQLite, Excel, Machine Learning, and Power BI

## 1. Project Overview
This project demonstrates a complete data analysis and machine learning workflow using real hospital data. It begins with raw data and progresses through cleaning, exploration, database creation, Excel analysis, modelling, and final visualization using Power BI. The entire process shows how multiple tools work together to generate meaningful insights from healthcare datasets.

## 2. Project Objectives
The objective of this project is to understand patient-related trends, improve data quality, predict patient status, and build a reporting dashboard. The project aims to combine analytics and machine learning techniques to support hospital decision-making through accurate insights and predictions.

## 3. Dataset Description
The dataset contains patient information such as ID, name, age, gender, department, bill amount, admission year, and current status. These fields help in analysing demographics, operational loads, financial patterns, and patient outcomes. Each column plays an important role in different stages of analysis.

## 4. Data Cleaning Process
The dataset goes through cleaning steps including removal of duplicates, handling missing values, correcting data types, and validating numeric values. Clean data ensures accurate SQL queries, reliable ML models, and clear reporting. This is an essential foundation step in the workflow.

## 5. Exploratory Data Analysis
EDA includes studying patterns such as department-wise patient distribution, age profiles, year-wise admissions, and bill amount variations. Visual plots and summaries reveal hidden trends and help understand how different factors influence hospital operations.

## 6. Excel Analysis Tasks
Several Excel tasks such as sorting, filtering, computing averages, highlighting high bill amounts, and counting specific categories are performed. These tasks help quickly validate the data, generate first-level insights, and cross-check information before loading into databases or models.

## 7. SQLite Database Integration
The cleaned dataset is stored in a SQLite database for structured data management. This integration simulates real-world healthcare data handling, making it easier to organize, retrieve, and analyse information. SQLite supports the analytical workflow with consistent and reliable storage.

1. Show all records from the hospital table
<img src="https://github.com/omkarshinde25/Hospital-Data-Analysis/blob/main/Photos/Hospital%20Data%20Analysis%20Dashboard.png" width="800"> <br>
   
2. Show all patients whose Gender = 'Male'.
<img src="https://github.com/omkarshinde25/Hospital-Data-Analysis/blob/main/Photos/Hospital%20Data%20Analysis%20Dashboard.png" width="800"> <br>

3. Show all patients with NULL BillAmount.
<img src="https://github.com/omkarshinde25/Hospital-Data-Analysis/blob/main/Photos/Hospital%20Data%20Analysis%20Dashboard.png" width="800"> <br>

4. Show patients whose Name starts with 'A'.
<img src="https://github.com/omkarshinde25/Hospital-Data-Analysis/blob/main/Photos/Hospital%20Data%20Analysis%20Dashboard.png" width="800"> <br>

5. Show all patients with BillAmount greater than 20000.
<img src="https://github.com/omkarshinde25/Hospital-Data-Analysis/blob/main/Photos/Hospital%20Data%20Analysis%20Dashboard.png" width="800"> <br>

6. 6. Count how many patients were treated by each doctor (group by Doctor).
<img src="https://github.com/omkarshinde25/Hospital-Data-Analysis/blob/main/Photos/Hospital%20Data%20Analysis%20Dashboard.png" width="800"> <br>

## 8. SQL Data Exploration
SQL operations are performed to understand key insights such as total patients, department counts, gender distribution, and financial totals. The database supports efficient extraction of insights and demonstrates how hospitals maintain and query structured data.

## 9. Machine Learning Problem Definition
The machine learning task focuses on predicting the patient status based on features like age, department, gender, and bill amount. Predictive analytics helps hospital administration anticipate outcomes and make informed decisions on staffing, bed management, and resource allocation.

## 10. Data Preprocessing for ML
Categorical fields are encoded, numerical fields processed, and the dataset is split into training and testing subsets. Preprocessing ensures that the machine learning models receive clean and standardised input for better learning and prediction accuracy.

## 11. Machine Learning Models Used
Two models are trained: Logistic Regression and Decision Tree Classifier. Logistic Regression provides a simple baseline, while Decision Tree handles non-linear relationships more effectively. Both models help evaluate and understand predictive performance.

## 12. Model Evaluation
Model performance is measured using metrics such as accuracy, precision, recall, and F1 score. Evaluation helps in identifying strengths and weaknesses of predictions. Confusion matrix insights support improving the model and understanding class-level performance.

## 13. Power BI Dashboard
<img src="https://github.com/omkarshinde25/Hospital-Data-Analysis/blob/main/Photos/Hospital%20Data%20Analysis%20Dashboard.png" width="800"> <br>

The Power BI dashboard visualises hospital data with charts and KPIs. It displays department-wise patient counts, gender distributions, year-wise trends, bill summaries, and patient status counts. The dashboard enhances understanding through interactive and user-friendly visuals.

## 14. Dashboard Insights
Key insights include identifying the busiest departments, understanding financial performance, analysing age and gender trends, and studying patient discharge patterns. These insights help hospital management in planning and decision-making.

## 15. Project Workflow Summary
The workflow moves from data cleaning to EDA, then to Excel analysis, database storage, machine learning modelling, and finally dashboard creation. Each step builds logically on the previous one, forming a complete end-to-end analytics pipeline.

## 16. Tools and Technologies Used
Python is used for cleaning, processing, and modelling. Excel is used for manual checks and quick insights. SQLite stores structured data. Power BI provides interactive dashboards. This combination covers all essential tools for analytics and machine learning.

## 17. Folder and File Structure
The project contains Python notebooks for EDA, SQL, and ML. It includes Excel files for analysis tasks, a SQLite database file, the Power BI dashboard, and this README. Each file is organised to make the project easy to navigate and understand.

## 18. Challenges and Solutions
The project faced challenges such as missing values, inconsistent formatting, and imbalanced categories. These issues were resolved through cleaning, preprocessing, and model tuning. This section reflects real-world data issues and practical solutions.

## 19. Final Outcomes
The project delivers a cleaned dataset, structured SQLite database, trained ML models, actionable insights, and a fully interactive dashboard. It showcases strong analytical, technical, and problem-solving skills across multiple tools and technologies.

## 20. Conclusion
This project demonstrates a complete analytical lifecycle suitable for a data analyst or machine learning portfolio. It highlights how data can support healthcare decisions and how multiple tools work together to produce reliable, meaningful results.

