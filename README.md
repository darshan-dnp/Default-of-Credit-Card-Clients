# Default-of-Credit-Card-Clients

ML project to check probability of default for credit card clients.

**Problem Setting and Definitions**

Recently, the use of credit cards have been increased drastically. People are inclining more
towards the use of their credit cards instead of debit cards due to the benefits like rewards,
credit score, protection against frauds etc. However, people often disregard their ability to
repay the credit taken from the bank or company and increase the chances of credit crises.
On the other hand, it increases the risk taken by the card issuer company. To minimize the
loss incurred by defaulters, it became very important for credit card issuers to identify high
risk credit card default users. With the help of this project, we will try to classify if the user
will default the payment of next month or not. The data consist of target variable as ‘default
payment next month’. The target variable is binary categorical variable so we are looking
forward to implement machine learning classification techniques and algorithms.

**Data Source**

Link to the UCI Repository

[Default of Credit Card Clients](https://archive-beta.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

**Data Description**

The dataset consists of 30,000 records and 24 variables including target variable.

1. **default payment next month (y):**

- This is the response variable of the dataset. The variable is labelled as 1 in case of
  default payment and 0 in case of not a default payment.
- The class of interest is y=1 which indicates the default payment.

2. **limit_bal**

- This numeric variable indicates the limit of given credit amount in dollars.
- It includes both the individual consumer credit and his/her family (supplementary)
  credit.

3. **sex**

- This binary categorical variable indicates the sex of clients. 1 indicates ‘male’ and 2
  indicates ‘female’.

4. **education**

- This categorical variable indicates the level of education of clients.
- Education levels are labelled as 1 = graduate school, 2 = university, 3 = high school and
  4 = others.

5. **marriage**

- This categorical variable indicates the marital status of clients.
- Marital statuses are labelled as 1 = married, 2 = single and 3 = others.

6. **age**

- This numeric variable indicates the age of clients.

7. **pay_0 to pay_6**

- These 6 categorical variables indicates the status of past 6 monthly payments.
- The data has been labelled as -1 = pay duly, 1 = payment delay for one month, 2 = payment delay for two months, 8 = payment delay for eight months, 9 = payment delay for nine months and above etc.

8. **bill_amt1 to bill_amt6**

- These 6 numerical variables indicates the amount of bill statements.

9. **pay_amt1 to pay_amt6**

- These 6 numerical variables indicates the amount of previous payment.
