# BANK MARKETING: Predicting Customer Subscription to Term Deposit (FIXED DEPOSIT)

## Business Use Case

A Portuguese bank has experienced a decline in revenue and identified that their clients are not depositing as frequently as before. Term deposits are a vital source of income for the bank, allowing them to invest in higher-gain financial products and persuade clients to purchase additional products. The bank aims to identify existing clients with a higher likelihood of subscribing to a term deposit, optimizing their marketing efforts and increasing revenue.

## Project Description

The client, a retail banking institution, relies on term deposits as a significant source of income. They have various outreach plans, including email marketing, advertisements, telephonic marketing, and digital marketing. Telephonic marketing is an effective method to reach potential subscribers, but it requires substantial investments in large call centers. Therefore, it is crucial to identify potential subscribers in advance to target them with personalized call campaigns.

This project utilizes client data such as age, job type, marital status, and other details, along with call information, to predict whether a client will subscribe to a term deposit.

## Dataset

### Source
The dataset is available on [GitHub](https://github.com/dsrscientist/dataset5).
	

## Dataset Information

The dataset is related to direct marketing campaigns (phone calls) conducted by a Portuguese banking institution. The goal is to predict whether the client will subscribe to a term deposit product. The dataset consists of two files:

1. **train.csv**: This dataset is used for model training and contains client and call details, including the target variable "subscribed."

2. **test.csv**: This dataset is used to predict whether a new set of clients will subscribe to the term deposit using the trained model.

## Dataset Attributes

Here is a description of the dataset attributes:

- **ID**: Unique client ID.
- **age**: Age of the client.
- **job**: Type of job.
- **marital**: Marital status of the client.
- **education**: Education level.
- **default**: Credit in default.
- **housing**: Housing loan.
- **loan**: Personal loan.
- **contact**: Type of communication.
- **month**: Contact month.
- **day_of_week**: Day of the week of contact.
- **duration**: Contact duration.
- **campaign**: Number of contacts performed during this campaign to the client.
- **pdays**: Number of days that passed by after the client was last contacted.
- **previous**: Number of contacts performed before this campaign.
- **poutcome**: Outcome of the previous marketing campaign.

Output variable (desired target):

- **Subscribed (target)**: Has the client subscribed to a term deposit? (YES/NO)

## Project Workflow

1. **Data Loading**: The training and testing datasets were retrieved from the provided links.
2. **Data Preprocessing**: An initial data quality assessment was conducted to address any missing values and inconsistencies.
3. **Exploratory Data Analysis (EDA)**: Initial data exploration was performed to gain insights into the dataset.
4. **Data Splitting**: The training dataset was divided into subsets for model development and evaluation.
5. **Model Building**: Various machine learning models were constructed to predict customer subscription to term deposits.
6. **Model Evaluation**: Model performance was assessed using appropriate metrics.
7. **Hyperparameter Tuning**: Model hyperparameters were optimized for better performance.
8. **Deployment (Optional)**: If a satisfactory model is achieved, it can be deployed for prediction on new data.
9. **Documentation**: This documentation provides an overview of the project, dataset attributes, and the workflow used.

## Conclusion

The BANK MARKETING: Predicting Customer Subscription to Term Deposit project is focused on predicting whether clients will subscribe to a term deposit product. The project assists the Portuguese bank in optimizing its marketing efforts to target potential subscribers effectively.

## Acknowledgments

This project was completed as part of the portfolio for [Ritik Nipane] during the internship with Flip Robo Technologies.

## Contributors

- [Ritik Nipane](https://github.com/RitzyKingS)

## License

This project is open-source and available under the [MIT License](LICENSE).

---
