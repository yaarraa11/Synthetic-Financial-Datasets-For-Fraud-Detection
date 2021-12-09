# Synthetic Financial Datasets For Fraud Detection

* Nouf Almalki
* Yara Aldossary

# Synthetic Financial Datasets : An Overview

Ever since the advent of internet the digital revolution has rising and has creeped into all aspects to our lives. One of the most important digital revolution happend in financial system and especially transacting money to someone from any part of the world digitally. Digital transactions have become a part of daily life like purchasing a product online, sending money to friends, depositing cash in bank account, investment purposes etc., They had a lot of benefits so does paved way for fradulent activities. People started using digital money transactions medium to launder money and make the money look like it comes from a legal source. This dataset (https://www.kaggle.com/ealaxi/paysim1) is presently only one of four on Kaggle with information on the rising risk of digital financial fraud, emphasizing the difficulty in obtaining such data.


# Problem statement

The main technical challenge it poses to predicting fraud is the highly imbalanced distribution between positive and negative classes in 6 million rows of data. Another stumbling block to the utility of this data stems from the possible discrepancies in its description.

# Objective

The objective is to find the patterns of transactions performed and help algorithms learn those patterns in identifying the fradulent transactions and flag them.


# Headers

This is a sample of 1 row with headers explanation:

* step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

* type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

* amount - amount of the transaction in local currency.

* nameOrig - customer who started the transaction

* oldbalanceOrg - initial balance before the transaction

* newbalanceOrig - new balance after the transaction

* nameDest - customer who is the recipient of the transaction

* oldbalanceDest - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

* newbalanceDest - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

* isFraud - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

* isFlaggedFraud - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.

# Goals

1 - Exploratory analysis of data to extract the pattern of fraudlent activites.

2 - Build a machine learning model to classify fraud and non-fraud transactions.

3 - Reduce the false negatives by tuning the model.

# Tools

* Technologies: Python, Jupyter notebook.
* Libraries: NumPy, Pandas, Sklearn, Matplotlib, Seaborn.

