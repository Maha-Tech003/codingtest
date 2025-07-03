1. Problem Statement : Create a machine learning model that predicts whether a patient is likely to be readmitted to the hospital within 30 days after discharge, based on patient discharge data.

2. Project Overview : This tool uses classification models to identify patients at high risk of readmission. It analyzes patient demographic and clinical information such as age, diagnoses, medications, hospital stay duration, and more.

3. Dataset :
   a. Source: Diabetes 130-US hospitals dataset
   b. Features: 50+ attributes including age, weight, gender, race
   c. Target Variable: readmitted (encoded as 1 if <30 days, 0 otherwise)

4. Skills Demonstrated: 
   a. AI/ML: Built classification model using Decision Tree
   b. Data Cleaning: Replaced missing values and encoded categorical variables
   c. Feature Engineering: Selected key variables affecting readmission risk
   d. Problem Solving: Managed imbalanced data and categorical medical codes

5. Project Structure : 
   a. Data Loading and Cleaning
   b.  Feature Engineering
   c.  Model Training and Evaluation
   d. Prediction and Risk Scoring


6. Model Performance :
   a. Model Used: Decision Tree Classifier
   b. Accuracy: 79.85% (~80%)

7. How to Use : 
   a. Load the dataset (diabetic_data.csv)
   b. Run the preprocessing and model training steps
   c. Input new patient details to receive a readmission risk prediction:
