# Term-Deposit-Classifier

1. Developed a ML model to predict term deposit subscription.
2. Explored data, engineered features and optimizedmodel performance.
3. Compared the results given by different classification models. Best accuracy score was
given by Decision Tree Classifier i.e. 90.63%.

## Problem Statement

Your client is a retail banking institution. Term deposits are a major source of income for a bank.
A term deposit is a cash investment held at a financial institution. Your money is invested for an agreed rate of interest over a fixed amount of time, or term.

The bank has various outreach plans to sell term deposits to their customers such as email marketing, advertisements, telephonic marketing and digital marketing.

Telephonic marketing campaigns still remain one of the most effective way to reach out to people. However, they require huge investment as large call centers are hired to actually execute these campaigns. Hence, it is crucial to identify the customers most likely to convert beforehand so that they can be specifically targeted via call.

You are provided with the client data such as : age of the client, their job type, their marital status, etc. Along with the client data, you are also provided with the information of the call such as the duration of the call, day and month of the call, etc. Given this information, your task is to predict if the client will subscribe to term deposit.

## Data

1. train.csv : Use this dataset to train the model. This file contains all the client and call details as well as the target variable “subscribed”. You have to train your model using this file.
2. test.csv : Use the trained model to predict whether a new set of clients will subscribe the term deposit.

## Data Dictionary
Here is the description of all the variables :
**Variable: Definition**
1. ID: Unique client ID
2. age: Age of the client
3. job: Type of job
4. marital: Marital status of the client
5. education: Education level
6. default: Credit in default.
7. housing: Housing loan
8. loan: Personal loan
9. contact: Type of communication
10. month: Contact month
11. day_of_week: Day of week of contact
12. duration: Contact duration
13. campaign: number of contacts performed during this campaign to the client
14. pdays: number of days that passed by after the client was last contacted
15. previous: number of contacts performed before this campaign
16. poutcome: outcome of the previous marketing campaign
17. Subscribed (target): has the client subscribed a term deposit?

## How good are your predictions?

**Evaluation Metric:** The Evaluation metric for this competition is accuracy.
