# Student Grades Prediction Project

## Introduction

This project focuses on predicting the Cumulative Grade Point Average (CGPA) of students based on their grades in various courses over four years of their university tenure. The dataset contains detailed information about students' performance in individual courses, enabling the development of a predictive model for CGPA.

## Dataset Information

The dataset comprises a total of 43 columns, each providing specific information about students and their grades. Key columns are as follows:

1. Seat No: A unique identifier for each student who took the exams.
2. CGPA: The cumulative GPA, which serves as the final marks provided to each student.
3. Course Codes: These columns are labeled in the format AB-XXX, where AB represents the department codes (alphabets), and XXX represents the year in which the candidate took the exam (numbers).

## Dataset

### Source
The dataset is available on [GitHub](https://github.com/dsrscientist/dataset4/blob/main/Grades.csv).

## Problem Statement

The primary objective of this project is to build a predictive model that can estimate a student's CGPA based on their grades across multiple courses over four years.

## Project Workflow

1. **Data Loading**: The dataset was retrieved from a public source and loaded for analysis.

2. **Data Preprocessing**: An initial data quality assessment was performed to identify and address any missing values or inconsistencies.

3. **Exploratory Data Analysis (EDA)**: Initial data exploration was conducted to provide summary statistics, visualize the data, and examine correlations.

4. **Data Splitting**: The dataset was divided into training and testing sets to facilitate model development and evaluation.

5. **Feature Engineering**: To assist in the model-building process, the grading system (A, B, C, D, F) was converted into numerical values (0 to 4) for analysis.

6. **Model Building**: Multiple machine learning models were constructed to predict CGPA, including Linear Regression, Random Forest Regression, Gradient Boosting Regression, and Support Vector Regression (SVR).

7. **Model Evaluation**: The performance of each model was assessed using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2).

8. **Feature Selection/Engineering**: Feature engineering techniques were applied to enhance the model's predictive capabilities.

9. **Hyperparameter Tuning**: Model hyperparameters were fine-tuned to optimize performance, primarily focusing on the Random Forest Regression model.

10. **Cross-Validation**: Cross-validation techniques were employed to ensure model robustness and generalization to new data.

11. **Deployment (Optional)**: If deemed successful, the best model can be deployed for predicting CGPA for new student data.

12. **Documentation**: A comprehensive documentation file was created to summarize the project, its objectives, methodology, and results. This documentation is suitable for sharing on platforms such as GitHub.

## Conclusion

The Student Grades Prediction project centers on forecasting students' CGPA based on their performance in various courses throughout their university journey. Multiple machine learning models were developed, with the Random Forest Regression model delivering the best performance. The project's documentation offers a comprehensive view of the dataset, problem statement, project flow, and outcomes.

## Acknowledgments

This project was completed as part of an internship with Flip Robo Technologies. I express our gratitude for the support and guidance provided during the internship.

## Usage

To use this project:

1. Clone the repository from [GitHub](https://github.com/RitzyKingS).
2. Make sure you have the required libraries installed, which are listed in the project's requirements file.
3. Run the provided Jupyter Notebook or Python scripts.

## Contributors

- [Ritik Nipane](https://github.com/RitzyKingS)

## License

This project is open-source and available under the [MIT License](LICENSE).

---
