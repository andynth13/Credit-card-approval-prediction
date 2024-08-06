# Credit card approval model

## Skill demonstration:

1. Model building with PCA to reduce features, SMOTE for imbalance data

2. Apply bussiness mindset and analytical thinking to balance the bank's profit as well as the customer's sastisfaction.


##  Project goal

Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk.

This notebook aim to create an model to predict the chance to approve or reject customer's request for new credit card. The model should be balance between business's revenue and the customer's eligibility.

## Dataset
The data was downloaded with some modification from [Kaggle Credit Card approval prediction dataset](http://www.google.fr](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction/ "Kaggle link").

## Result and Recommendation

* With limited information about customer background, such as employment status, salary, family factors,.. the model can predict at best only 50% high risk cases. We should consider to collect more critical data such as customer's financial status, expense and payment trends in the past few months/ years.
* Re-evaluate the criterias for cc approval after a certain amount of time to catch up with the payment trends and improve the prediction with most updated data.


