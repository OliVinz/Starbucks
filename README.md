# Starbucks Capstone Project | Udacity - Data Science Nanodegree
Find my medium article detailing the whole process here
https://medium.com/@oliver.vinzelberg/exploratory-data-analysis-and-modelling-performed-on-starbucks-customer-data-1f7683fe972d


Overview

Starbucks, a coffee giant known for its rewards app, regularly sends promotional offers to entice customers. However, not all offers resonate equally. This project aims to personalize these offers by predicting customer responses based on their past interactions. Through thorough data analysis (EDA) and machine learning models, we strive to help Starbucks target the right customers with the right offers, boosting their marketing effectiveness.

For this project, the data sets are provided by Starbucks and Udacity in the form of three JSON files. These contains simulated data that mimics customer behavior on the Starbucks rewards mobile app.

    portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
    profile.json - demographic data for each customer
    transcript.json - records for transactions, offers received, offers viewed, and offers completed

Libraries used:
    pandas
    numpy as np
    math
    json
    datetime
    seaborn
    matplotlib
    sklearn
    time


Here is the schema and explanation of each variable in the files:

portfolio.json

    id (string) - offer id
    offer_type (string) - type of offer ie BOGO, discount, informational
    difficulty (int) - minimum required spend to complete an offer
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



Acknowledgements

Special thanks to Starbucks and Udacity for providing the data for this project!
