# Customer Churn Prediction

This project aims to predict customer churn for a telecom company using a given dataset. It involves performing exploratory data analysis, building a predictive model, and establishing evaluation metrics for the model's performance.

## Project Overview

This data project has been used as a take-home assignment during the recruitment process for Data Science positions at Sony Research. The dataset consists of customer information from a telecom company, and the goal is to predict whether a customer will churn based on their usage patterns and service details.

### Dataset

You must be a yearly or lifetime subscriber to download the dataset.  
**Download Dataset:** [Click here to download](https://github.com/abhishek-sriram/DS-Hands-On/blob/main/Sony%20Research/Sony_Research.csv)  

The dataset is provided in the file `Data_Science_Challenge.csv` and includes customer details such as usage metrics, service plans, and whether they churned or not.

### Assignment

The tasks for this project are as follows:
1. Perform **exploratory data analysis (EDA)** to extract insights from the dataset.
2. **Split the dataset** into training and testing sets, providing reasoning for the split.
3. Build a **predictive model** to forecast customer churn, and justify your choice of algorithm.
4. Establish **metrics** to evaluate the model's performance.
5. Discuss potential issues with **deploying the model** into production.

## Data Description

The dataset contains the following columns:

| Column Name           | Column Type    | Description                                                  |
|-----------------------|----------------|--------------------------------------------------------------|
| `State`               | String         | The state where a customer comes from                        |
| `Account length`      | Integer        | Number of days a customer has been using services            |
| `Area code`           | Integer        | The area code where a customer is located                    |
| `Phone number`        | Alphanumeric   | The customer's phone number                                  |
| `International plan`  | String         | Whether the customer has an international plan (Yes/No)      |
| `Voicemail plan`      | String         | Whether the customer has a voicemail plan (Yes/No)           |
| `No. vmail msgs`      | Integer        | Number of voicemail messages sent by the customer            |
| `Total day minutes`   | Float          | Total call minutes during the day                            |
| `Total day calls`     | Integer        | Total number of calls made during the day                    |
| `Total day charge`    | Float          | Total amount charged during the day                          |
| `Total eve minutes`   | Float          | Total call minutes during the evening                        |
| `Total eve calls`     | Integer        | Total number of calls made during the evening                |
| `Total eve charge`    | Float          | Total amount charged during the evening                      |
| `Total night minutes` | Float          | Total call minutes during the night                          |
| `Total night calls`   | Integer        | Total number of calls made during the night                  |
| `Total night charge`  | Float          | Total amount charged during the night                        |
| `Total intl minutes`  | Float          | Total international call minutes                             |
| `Total intl calls`    | Integer        | Total number of international calls made                     |
| `Total intl charge`   | Float          | Total international call charges                             |
| `Customer service calls` | Integer     | Total number of customer service calls                       |
| `Churn`               | Boolean        | Whether the customer has churned or not                      |

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
