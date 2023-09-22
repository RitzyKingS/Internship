
# Medical Cost Personal Insurance Project

## Introduction
In the realm of healthcare and financial planning, understanding and accurately predicting medical insurance costs are of paramount importance. This project delves into the world of health insurance, where the goal is to develop a predictive model that estimates individual medical insurance costs. Leveraging key input features such as age, BMI, number of dependents, smoking habits, gender, and residential region, this project aims to provide individuals and insurance providers with a reliable tool for forecasting healthcare expenses. By harnessing the power of machine learning, we seek to enhance financial preparedness and informed decision-making in the realm of medical insurance.

## Prerequisites
Before you begin, ensure you have met the following requirements:

- Python (version X.X)
- Jupyter Notebook (optional)
- Python libraries: NumPy, pandas, matplotlib, seaborn, scikit-learn

## Dataset
The dataset used for this project can be found [here](https://github.com/dsrscientist/dataset4/blob/main/medical_cost_insurance.csv). It contains the following columns:

- `age`: Age of the primary beneficiary.
- `sex`: Insurance contractor gender (female, male).
- `bmi`: Body mass index (BMI), providing an understanding of body weight relative to height.
- `children`: Number of children covered by health insurance/Number of dependents.
- `smoker`: Smoking status (yes, no).
- `region`: The beneficiary's residential area in the US (northeast, southeast, southwest, northwest).
- `charges`: Individual medical costs billed by health insurance.

## Data Preprocessing
- Import the necessary libraries.
- Load the dataset and check for missing values.
- Encode categorical variables using one-hot encoding.
- Normalize or scale numerical features.

## Exploratory Data Analysis (EDA)
- Calculate summary statistics and visualize the distribution of charges.
- Create a pair plot to visualize relationships between features.

## Data Splitting
- Split the data into features (X) and the target variable (y).
- Split the data into training and testing sets (e.g., 80% train, 20% test).

## Model Building
### 1. Linear Regression
- Initialize and train a Linear Regression model.
- Evaluate the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2).

### 2. Random Forest Regression
- Initialize and train a Random Forest Regression model.
- Evaluate the model using MAE, MSE, and R2.

### 3. Gradient Boosting Regression
- Initialize and train a Gradient Boosting Regression model.
- Evaluate the model using MAE, MSE, and R2.

### 4. Support Vector Regression (SVR)
- Initialize and train a Support Vector Regression (SVR) model.
- Evaluate the model using MAE, MSE, and R2.

## Conclusion
Based on the evaluation metrics for each regression model, the Gradient Boosting Regression model appears to be the best-performing model for predicting insurance costs. It has the lowest MAE and MSE and the highest R-squared value, indicating better accuracy and fit to the data. Therefore, for accurate predictions of insurance costs, it is recommended to use the Gradient Boosting Regression model. These models offer valuable insights into estimating insurance costs for better healthcare financial planning, but further refinement and validation with additional data can enhance their reliability.

## Authors
- [Ritik Nipane]

## Acknowledgments
- This project was provided by [Flip Robo Technologies](https://www.fliprobo.com/). We would like to express our gratitude for their support and resources that made this project possible.

This acknowledges Flip Robo Technologies for providing the project and shows appreciation for their contribution to your project.

