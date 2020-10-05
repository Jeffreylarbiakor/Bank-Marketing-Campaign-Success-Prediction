# Marketing-Campaign-Prediction
Marketing campaigns are characterized by focusing on the customer needs and their overall satisfaction. The dataset used contains details of marketing campaigns done via phone with various details for customers such as demographics, last campaign details etc. The focus of the project is to help a bank to predict accurately whether a customer will subscribe to the focus product for the campaign - Term Deposit after the campaign.
---

## Problem Statement
Marketing campaigns are characterized by focusing on the customer needs and their overall satisfaction. Nevertheless, there are different variables that determine whether a marketing campaign will be successful or not. Some important aspects of a marketing campaign are as follows: 

Segment of the Population: To which segment of the population is the marketing campaign going to address and why? This aspect of the marketing campaign is extremely important since it will tell to which part of the population should most likely receive the message of the marketing campaign. 

Distribution channel to reach the customer's place: Implementing the most effective strategy in order to get the most out of this marketing campaign. What segment of the population should we address? Which instrument should we use to get our message out? (Ex: Telephones, Radio, TV, Social Media Etc.) 

Promotional Strategy: This is the way the strategy is going to be implemented and how are potential clients going to be address. This should be the last part of the marketing campaign analysis since there has to be an in-depth analysis of previous campaigns (If possible) in order to learn from previous mistakes and to determine how to make the marketing campaign much more effective.

You are leading the marketing analytics team for a banking institution. There has been a revenue decline for the bank and they would like to know what actions to take. After investigation, it was found that the root cause is that their clients are not depositing as frequently as before. Term deposits allow banks to hold onto a deposit for a specific amount of time, so banks can lend more and thus make more profits. In addition, banks also hold better chance to persuade term deposit clients into buying other products such as funds or insurance to further increase their revenues.

You are provided a dataset containing details of marketing campaigns done via phone with various details for customers such as demographics, last campaign details etc. Can you help the bank to predict accurately whether the customer will subscribe to the focus product for the campaign - Term Deposit after the campaign?
---

## Data Description
### Train Set
Train set contains the data to be used for model building. It has the true labels for whether the customer subscribed for term deposit(1) or not(0) 
* **id:**	Unique identifier for each sample in the dataset. Cannot be used for modelling
* **customer_age:**	Age of the Customer in years
* **job_type:**	Type of job of the customer
* **marital:** Marital Status of the Custmer
* **education:** Education Level of the Customer
* **default:** Whether customer has Defaulted in Past
* **balance:** Current Balance in the Customer's Bank
* **housing_loan:** Has customer taken a Housing Loan
* **personal_loan:** Has customer taken a Personal Loan
* **communication_type:** Type of communication made by the bank with the customer
* **day_of_month:**	Day of month of the last contact made with customer
* **month:** Month for the last contact made with customer
* **last_contact_duration:** Last Contact duration made with the customer (in seconds)
* **num_contacts_in_campaign:**	Number of contacts made with the customer during the current campaign.
* **days_since_prev_campaign_contact:** Number of days passed since customer was contacted in previous campaign.
* **num_contacts_prev_campaign:** Number of contacts made with the customer during the previous campaign.
* **prev_campaign_outcome:** Success or Failure in previous Campaign.
* **term_deposit_subscribed:** (Target) Has the customer taken a term deposit ?

### Test Set
Set of calls for which the prediction needs to be done regarding the subscription status of the customer for term deposit post campaign

* **id:**	Unique identifier for each sample in the dataset. Cannot be used for modelling.
* **customer_age:**	Age of the Customer in years
* **job_type:**	Type of job of the customer
* **marital:**	Marital Status of the Custmer
* **education:**	Education Level of the Customer
* **default:**	Whether customer has Defaulted in Past
* **balance:**	Current Balance in the Customer's Bank
* **housing_loan:**	Has customer taken a Housing Loan
* **personal_loan:**	Has customer taken a Personal Loan
* **communication_type:**	Type of communication made by the bank with the customer
* **day_of_month:**	Day of month of the last contact made with customer
* **month:**	Month for the last contact made with customer
* **last_contact_duration:**	Last Contact duration made with the customer (in seconds)
* **num_contacts_in_campaign:**	Number of contacts made with the customer during the current campaign.
* **days_since_prev_campaign_contact:**	Number of days passed since customer was contacted in previous campaign.
* **num_contacts_prev_campaign:**	Number of contacts made with the customer during the previous campaign.
* **prev_campaign_outcome:**	Success or Failure in previous Campaign.

[Back To The Top](#marketing-campaign-prediction)
---
