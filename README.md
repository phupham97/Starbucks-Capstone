# Starbucks-Capstone
The analysis shows how to send reasonable offers to Starbucks customers. I have analyzed Starbucks transactional data showing user purchases made on the app. This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. This transactional data also has a record for each offer that a user receives as well as a record for when a user actually views the offer. There are also records for when a user completes an offer.
# Libraries
I imported pandas, numpy, matplotlib and multiple sklearn models.
# Questions
The analysis will try to help Starbucks to find out how to send reasonable offers based on some question:

Question 1: Which kind of offer attract the customers the most ?

Question 2: Can we classify the customers, based on some demographics features, such as age or gender ?

Question 3: Which features will have high impact on customers’ behaviors ?

Question 4: Can we predict the customers’ behaviors based on a model ?

Question 5: Can we make any advice for Starbucks to attract more ?

# File description

1. Data:

1.1. profile.json: Rewards program users (17000 users x 5 fields)

+ gender: (categorical) M, F, O, or null
+ age: (numeric) missing value encoded as 118
+ id: (string/hash)
+ became_member_on: (date) format YYYYMMDD
+ income: (numeric)

1.2. portfolio.json: Offers sent during 30-day test period (10 offers x 6 fields)

+ reward: (numeric) money awarded for the amount spent
+ channels: (list) web, email, mobile, social
+ difficulty: (numeric) money required to be spent to receive reward
+ duration: (numeric) time for offer to be open, in days
+ offer_type: (string) bogo, discount, informational
+ id: (string/hash)

1.3. transcript.json: Event log (306648 events x 4 fields)

+ person: (string/hash)
+ event: (string) offer received, offer viewed, transaction, offer completed
+ value: (dictionary) different values depending on event type
+ time: (numeric) hours after start of test
2. Starbucks_Capstone_notebook.ipynb: Notebook with detailed code cells.
# Results
You can see my results here: https://medium.com/@phamhuuphu.251197/have-you-ever-got-a-discount-from-starbucks-7d7f98eaa040
