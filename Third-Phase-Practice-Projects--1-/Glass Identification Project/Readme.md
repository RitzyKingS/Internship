
# Glass Identification Project

## Introduction

This project involves the classification of glass samples into one of six categories based on their chemical properties. The dataset was credited to Vina Spiehler in 1987 and was inspired by its potential application in criminological investigations, where identifying the type of glass found at a crime scene can be crucial. This project aims to build a classification model for glass type prediction.

## Overview

This project is aimed at classifying different types of glass based on their chemical properties. It involves data on 214 glass samples, where the goal is to predict the type of glass based on attributes like refractive index and the weight percentages of various chemical oxides.

The dataset was originally credited to Vina Spiehler in 1987 and is used in criminological investigations to identify glass left at the scene of a crime.

## Dataset

### Source
The dataset is available on [GitHub](https://raw.githubusercontent.com/dsrscientist/dataset3/main/glass.csv).

## Dataset Information

The dataset contains 214 observations, each described by 11 attributes:

1. Id number: An identifier for each observation.
2. RI: Refractive index.
3. Na: Sodium (measured as weight percent in corresponding oxide).
4. Mg: Magnesium.
5. Al: Aluminum.
6. Si: Silicon.
7. K: Potassium.
8. Ca: Calcium.
9. Ba: Barium.
10. Fe: Iron.
11. Type of glass: This is the target variable, representing six different classes of glass.

The types of glass are categorized as follows:
- 1: Building windows, float processed.
- 2: Building windows, non-float processed.
- 3: Vehicle windows, float processed.
- 4: Vehicle windows, non-float processed (none in this dataset).
- 5: Containers.
- 6: Tableware.
- 7: Headlamps.

## Problem Statement

The main objective of this project is to develop a classification model that can predict the type of glass based on the given chemical properties (attributes 2 to 10).

## Project Workflow

1. **Data Loading**: The dataset was obtained from a public source and loaded for analysis.

2. **Data Preprocessing**: The dataset was checked for any missing values or inconsistencies. Any issues were addressed during this phase.

3. **Exploratory Data Analysis (EDA)**: Initial data exploration was conducted, which included summary statistics, data visualization, and correlation analysis.

4. **Data Splitting**: The dataset was divided into training and testing sets to facilitate model training and evaluation.

5. **Model Building**: Several machine learning models were built, including Linear Regression, Random Forest Regression, Gradient Boosting Regression, and Support Vector Regression (SVR).

6. **Model Evaluation**: The performance of each model was assessed using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2).

7. **Feature Importance**: Feature importance analysis was performed, providing insights into the key attributes driving model predictions.

8. **Hyperparameter Tuning**: Fine-tuning was conducted to improve model performance, specifically for the Random Forest Regression model.

9. **Cross-Validation**: Cross-validation was applied to ensure model robustness and generalization.

10. **Deployment (Optional)**: If deemed satisfactory, the best model can be deployed for making predictions on new data.

11. **Documentation**: A documentation file was created to provide clarity on the project's objectives, methodology, and results. This document is intended for sharing on platforms like GitHub.

## Conclusion

The Glass Identification project involves the classification of glass samples into six distinct types based on their chemical properties. Various machine learning models were trained and evaluated, with the Random Forest Regression model demonstrating the best performance. The project's documentation provides a comprehensive overview of the dataset, problem statement, project workflow, and results.

## Acknowledgments

This project was completed as part of an internship with Flip Robo Technologies. I acknowledge the support and guidance provided during the internship.


## Usage

To use this project:

1. Clone the repository from [GitHub](https://github.com/RitzyKingS).
2. Make sure you have the required libraries installed, which are listed in the project's requirements file.
3. Run the provided Jupyter Notebook or Python scripts.

## Results

The classification models were built and evaluated. The best-performing model based on evaluation metrics was the Random Forest classifier with an accuracy of X%. Feature importance analysis revealed that attributes Y and Z were the most influential in predicting glass types.

## Future Work

Future improvements for this project may include:

- Hyperparameter tuning for better model performance.
- Additional feature engineering to enhance prediction accuracy.
- Deployment as a web application or REST API for real-time predictions.

## Contributors

- [Ritik Nipane](https://github.com/RitzyKingS)

## License

This project is open-source and available under the [MIT License](LICENSE).

---