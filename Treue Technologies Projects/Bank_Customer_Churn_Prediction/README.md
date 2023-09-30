# Bank_Customer_Churn_Prediction

This project was completed as part of Treue Technologies Internship.
## Introduction
> Over the years, bank churn rates have steadily increased. However, with the advent of AI, there's a powerful tool to minimize these churn rates. Bank churn prediction, powered by artificial intelligence and data analytics, offers a proactive approach to identify customers at risk of leaving. By harnessing the potential of data-driven insights, banks can now take targeted actions to retain their valuable clientele and foster long-term customer relationships.<br> 
In this project, the primary objective is to develop a highly accurate model for predicting customer churn in the banking industry
Through the analysis of historical customer data, including transaction records, account information, demographics, and interaction patterns, we aim to uncover valuable insights and underlying factors that contribute to customer attrition. This predictive model will empower banks to take proactive measures to retain customers, enhance customer satisfaction, and optimize their business strategies. Ultimately, the goal is to drive customer retention and strengthen the long-term relationships between banks and their clients.

# Column Description
| Variable        | Definition                                          |
|-----------------|----------------------------------------------------|
| RowNumber       | RowNumber used for identification                  |
| CustomerId      | A unique Identifier                                 |
| Surname         | Surname of the customer                            |
| CreditScore     | Credit score of the customer                       |
| Geography       | Geographic region of the customer                   |
| Gender          | Gender of the customer                             |
| Age             | Age of the customer in years                       |
| Tenure          | Time spent with the bank                           |
| Balance         | Amount of money in the customer's account balance  |
| NumOfProducts   | Number of products purchased by the customer       |
| HasCrCard       | An integer representing if the customer received a credit card |
| IsActiveMember  | An integer representing the activeness of the customer  |
| EstimatedSalary | The estimated salary of the customer              |
| Exited          | An integer representing if the customer has churned |


# Table of Contents
- `data:` the folder containing the original and the cleaned datasets.
- `model:` the folder containing the trained Model.
- `Bank Customer Churn Data Analysis and Visualization Notebook.ipynb:` the Jupyter Notebook containing the cleaning and analytical techniques used.
- `Bank_Customer_Churn_Prediction.ipynb`: the Jupyter Notebook containing the techniques used in creating the model.
- `Requirements.txt`: the required python libraries.
  
# Installation and Configuration
Download Anaconda at https://www.anaconda.com/download/ and install the libraries in the requirement.txt file using PIP

Install Jupyter Notebook by running the following command:
```
conda install jupyter notebook
```
or
```
pip install jupyter notebook
```

Then launch the Jupyter Notebook to view the .ipynb file.

