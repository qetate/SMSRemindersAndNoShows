# Impact of SMS Reminders on No-Shows

## Overview
This project seeks to answer the research question: Does sending SMS appointment reminders to patients reduce the number of no-show appointments? Using a dataset from over 100,000 medical appointments in Brazil, the analysis explores if SMS reminders are an effective tool in reducing no-shows, which cost healthcare providers valuable resources and revenue.

## Data
The dataset for this project comes from the <a href="https://www.kaggle.com/datasets/joniarroba/noshowappointments">Kaggle Medical Appointment No Shows Dataset</a> and includes patient demographics, appointment details, and information on whether or not patients received an SMS reminder and subsequently showed up for their appointments.

## Technologies Used
- **Python**: For data analysis and model building.
- **Jupyter Notebook**: The project was executed and documented using a Jupyter notebook.
- **Pandas and NumPy**: For data manipulation and analysis.
- **Matplotlib and Seaborn**: For data visualization.
- **Scikit-learn**: To build and evaluate a logistic regression model.

## Skills Demonstrated
- **Data Wrangling and Cleaning**: Handling real-world, raw data by cleaning, transforming, and preparing it for analysis.
- **Exploratory Data Analysis (EDA)**: Performed EDA to identify trends, patterns, and relationships between variables. Used tools such as Pandas, NumPy, Seaborn, and Matplotlib for visualizations, including correlation matrices, histograms, and boxplots.
- **Statistical Analysis**: Conducted hypothesis testing using a Chi-Square Test to determine the statistical significance of SMS reminders on no-show rates.
- **Machine Learning**: Built and trained a logistic regression model to predict patient no-shows, a binary classification task. Evaluated the model's performance using accuracy, precision, recall, and F1-score.
- **Model Evaluation and Interpretation**: Assessed the model's performance through confusion matrices and various performance metrics. Analyzed the model’s predictions to understand where it succeeded and where improvements could be made, specifically in reducing false positives.
- **Data Visualization**: Created meaningful and insightful visualizations to communicate findings, such as the correlation matrix and confusion matrix, using Seaborn and Matplotlib.

## Results
- **Exploratory Data Analysis (EDA)**: No strong correlations were found between no-shows and patient demographics, though receiving an SMS was related to improved attendance.
- **Chi-Square Test**: The test confirmed a statistically significant relationship between receiving an SMS reminder and reducing no-shows. However, due to the large sample size, this significance should be considered in conjunction with model performance and EDA findings.
- **Logistic Regression Model**: The model performed moderately well, achieving an overall accuracy of 65%. It was more effective at predicting attended appointments than no-shows, suggesting potential for further optimization. With more time, this model's performance could be improved.
