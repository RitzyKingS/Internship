
---

# Red Wine Quality Prediction Project

## Project Description
The Red Wine Quality Prediction Project focuses on predicting the quality of red wine based on physicochemical and sensory attributes. The dataset contains data for red and white variants of Portuguese "Vinho Verde" wine. It includes various physicochemical properties as input variables and the wine quality as the output variable, which is rated on a scale from 0 to 10.

### Dataset Information
- **Input Variables (Based on Physicochemical Tests):**
    1. Fixed Acidity
    2. Volatile Acidity
    3. Citric Acid
    4. Residual Sugar
    5. Chlorides
    6. Free Sulfur Dioxide
    7. Total Sulfur Dioxide
    8. Density
    9. pH
    10. Sulphates
    11. Alcohol

- **Output Variable (Based on Sensory Data):**
    12. Quality (Score between 0 and 10)

## Classification Task
This project involves a classification task to predict whether a wine is 'good' or 'not good' based on its quality score. A binary classification can be performed by setting a cutoff point (e.g., 7 or higher) for the quality score, where wines with scores above the cutoff are classified as 'good/1,' and the rest are classified as 'not good/0.'

## Inspiration
The project aims to leverage machine learning techniques to determine which physicochemical properties contribute to a wine being classified as 'good.' It provides an opportunity to explore feature selection methods and perform hyperparameter tuning, particularly with decision tree algorithms, while evaluating performance using metrics like the ROC curve and AUC value.

### Dataset Source
The dataset used in this project can be found [here](https://github.com/dsrscientist/DSData/blob/master/winequality-red.csv).

## Project Structure
The project includes the following main components:
1. Data Preprocessing
2. Exploratory Data Analysis (EDA)
3. Data Splitting
4. Model Building
5. Model Evaluation
6. Conclusion

## Dependencies
Make sure you have the following libraries installed:
- NumPy
- pandas
- Matplotlib
- Seaborn
- Scikit-Learn

## Acknowledgments
- This project was made possible with the support and resources provided by [Flip Robo Technologies](https://www.fliprobo.com/).

---