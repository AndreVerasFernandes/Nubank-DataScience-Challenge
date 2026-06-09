# Nubank-DataScience-Challenge

Credit risk refers to the likelihood that a borrower will be unable or unwilling to fulfill their financial obligations, including mortgage payments, credit card balances, and other forms of debt.

Managing and reducing default risk is a critical objective for financial institutions. As a result, banks, investment firms, insurance companies, asset managers, and fintech organizations increasingly rely on data-driven technologies to assess the creditworthiness of their customers and identify potential defaulters before losses occur.

Machine Learning has become an essential tool in this process, enabling organizations to build predictive models that improve the accuracy of credit risk assessments. By analyzing historical customer data, these models can uncover patterns associated with default behavior and support more informed lending decisions.

## About the Dataset

Nubank is one of the largest digital banking platforms in Latin America and is widely recognized for its strong data-driven culture. The company leverages analytics and technology to optimize operations, enhance customer experiences, and support strategic decision-making.

This project uses a customer acquisition dataset to develop and compare credit default prediction models.

### Dataset:
http://dl.dropboxusercontent.com/s/xn2a4kzf0zer0xu/acquisition_train.csv?dl=0

### Data Analysis

The dataset consists of 45,000 customer records and 43 input features. The variable target_default is a binary indicator (True/False) representing whether a customer defaulted, and it serves as the target variable for the prediction task.

During the exploratory data analysis (EDA) phase, several data quality issues were identified. In particular, some variables contained missing values, while others exhibited significant outliers that could potentially affect model performance. Understanding and addressing these issues is an important step before training machine learning models, as it helps improve data reliability and predictive accuracy.
