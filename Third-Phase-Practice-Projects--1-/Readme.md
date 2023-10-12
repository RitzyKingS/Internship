# Machine Learning Projects Portfolio Documentation

## Introduction

This portfolio showcases three distinct machine learning projects, each with its own unique business context, dataset, and objectives. These projects are the result of extensive data analysis, predictive modeling, and evaluation. This documentation provides an overview of each project's purpose, dataset, and methodology.

### Projects Overview

1. **Glass Identification** - Classification Project
   - Project Description: This project involves classifying different types of glass based on their chemical properties. The dataset is divided into window glass and non-window glass. The objective is to predict the type of glass.
   - Dataset Link: [Glass Identification Dataset](https://raw.githubusercontent.com/dsrscientist/dataset3/main/glass.csv)

#### Dataset Attributes
- ID number
- Refractive index (RI)
- Chemical composition attributes (Sodium, Magnesium, Aluminum, Silicon, Potassium, Calcium, Barium, Iron)
- Type of glass (class attribute)

[More Details](#)

2. **Student Grades Prediction** - Regression Project
   - Project Description: In this project, student grades from various courses and the cumulative GPA (CGPA) were predicted based on their grades over four years of study. The focus is on regression analysis.
   - Dataset Link: [Student Grades Dataset](https://github.com/dsrscientist/dataset4/blob/main/Grades.csv)

#### Dataset Attributes
- Seat Number
- CGPA
- Course codes with corresponding grades

[More Details](#)

3. **Bank Marketing** - Classification Project
   - Project Description: The project involves predicting whether a client will subscribe to a term deposit (fixed deposit) in a Portuguese bank. This is a binary classification problem with a focus on marketing optimization.
   - Dataset Link: [Bank Marketing Dataset](https://github.com/dsrscientist/dataset5)

#### Dataset Attributes
- Client attributes (age, job, marital status, education)
- Marketing details (contact type, month, day of the week, duration, campaign)
- Historical data (pdays, previous contacts, previous campaign outcome)
- Target variable (term deposit subscription)

[More Details](#)

## Glass Identification Project Documentation

### Business Use Case

The Glass Identification project aims to assist in criminal investigations by correctly classifying glass samples based on their chemical properties. The project addresses the classification of glass into window and non-window types, aiding in forensic analysis.

### Dataset Attributes

The dataset includes information about chemical compositions and identifies the type of glass. Key attributes include refractive index, sodium, magnesium, aluminum, and more. The target variable is the type of glass (class attribute).

### Workflow

1. **Data Loading**: The dataset was loaded into a pandas DataFrame.
2. **Data Preprocessing**: Data quality issues, such as missing values, were addressed.
3. **Exploratory Data Analysis (EDA)**: Initial insights into the dataset were gained through data visualization.
4. **Model Building**: Several machine learning models, including linear regression and random forest, were built for classification.
5. **Model Evaluation**: Model performance metrics, such as accuracy and F1 score, were calculated.

### Conclusion

The Glass Identification project successfully classifies glass types based on chemical properties, potentially aiding in criminal investigations. Machine learning models demonstrated strong performance in predicting the type of glass, as evidenced by evaluation metrics.

## Student Grades Prediction Project Documentation

### Business Use Case

This project aims to predict student grades and cumulative GPAs based on their grades over four years of study. The CGPA serves as a final mark provided to students. The project can help educational institutions monitor student performance.

### Dataset Attributes

The dataset consists of course codes, grades, and CGPA for each student. The challenge is to predict the CGPA based on course grades.

### Workflow

1. **Data Loading**: The dataset was loaded into a pandas DataFrame.
2. **Data Preprocessing**: Missing values were replaced, and grades were converted to numerical values.
3. **Exploratory Data Analysis (EDA)**: Initial insights into the dataset were gained through data visualization.
4. **Model Building**: Regression models were constructed to predict CGPA.
5. **Model Evaluation**: Model performance was assessed using metrics such as mean absolute error and R-squared.

### Conclusion

The Student Grades Prediction project successfully predicts CGPA based on student grades. The regression models offer a valuable tool for monitoring and evaluating student performance.

## Bank Marketing Project Documentation

### Business Use Case

The Bank Marketing project addresses the challenge of predicting whether a client will subscribe to a term deposit in a Portuguese bank. The objective is to optimize marketing efforts by identifying potential subscribers in advance.

### Dataset Attributes

The dataset includes client information and details of the marketing campaign, such as age, job, communication type, and the outcome of the previous campaign. The target variable is whether the client subscribed to the term deposit.

### Workflow

1. **Data Loading**: Both training and testing datasets were retrieved from provided links.
2. **Data Preprocessing**: Data quality issues were addressed, and categorical variables were encoded.
3. **Exploratory Data Analysis (EDA)**: Initial insights into the dataset were gained through data visualization.
4. **Data Splitting**: The training dataset was divided for model development and evaluation.
5. **Model Building**: Classification models were constructed to predict client subscription.
6. **Model Evaluation**: Model performance was assessed using metrics such as accuracy and F1 score.

### Conclusion

The Bank Marketing project successfully predicts client subscription to term deposits, enabling the bank to optimize marketing efforts. Classification models provide valuable insights for targeting potential subscribers.

## Acknowledgments

These projects were completed as part of a portfolio during an internship with Flip Robo Technologies.

---
