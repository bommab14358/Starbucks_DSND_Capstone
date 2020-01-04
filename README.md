# Starbucks_DSND_Capstone
# Starbucks analysis for Udacity DSND Capstone
## Installations
Python version - 3.7.1
Seaborn and Matplotlib

## Project Motivation
The project aims to analyze the marketing activity and spend data to understand the impact of different promotional campaigns on customer's spending pattern 

## File Descriptions
The data is contained in three files:
1. portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
2. profile.json - demographic data for each customer
3. transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:
1. portfolio.json
- id (string) - offer id
- offer_type (string) - type of offer ie BOGO, discount, informational
- difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - time for offer to be open, in days
channels (list of strings)
profile.json

age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income
transcript.json

event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours since start of test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record

## Analysis
The notebook in this repository contains the EDA, Modeling and other operations related to this analysis

## Observations
Observations from the analysis are summarized in this article -> https://medium.com/@bharathbommakanti/peek-into-airbnbs-pricing-strategy-for-boston-f091f56f516d

## Acknowledgements
This dataset is part of Airbnb Inside, and the original source can be found at http://insideairbnb.com/get-the-data.html
