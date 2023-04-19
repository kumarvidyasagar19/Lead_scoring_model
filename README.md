# Lead_scoring_model
I have develope a lead scoring machine learning model of housing accomodation booking system. Data set given by UniAcco comapny, the comapny working for provideing accomodation facility to student. 
But company recently realised that there is huge dropping ratio.so i have develope a machine learning and Exploratory data analysis (EDA) model to use company given dataset so that company can make approprite rule to handle the problem.

# Problem: Lead Scoring Model

Selling something is not an easy task. A business might have many potential customers, commonly referred as leads, but not enough resources to cater them all. Even most of the leads won’t turn into actual bookings. So there is a need for a system that prioritises the leads, and sorts them on the basis of a score, referred to here as lead score. So whenever a new lead is generated, this system analyses the features of the lead and gives it a score that correlates with chances of it being converted into booking. Such ranking of potential customers not only helps in saving time but also helps in increasing the conversion rate by letting the sales team figure out what leads to spend time on.
Here you have a dataset of leads with their set of features and their status. You have to build a ML model that predicts the lead score as an OUTPUT on the basis of the INPUT set of features. This lead score will range from 0-100, so more the lead score means more chances of conversion of lead to WON.

* NOTE: The leads with STATUS other than ‘WON’ or ‘LOST’ can be dropped during training.
* NOTE: Treat all columns as CATEGORICAL columns
* NOTE: This '9b2d5b4678781e53038e91ea5324530a03f27dc1d0e5f6c9bc9d493a23be9de0' represents NaN and could be present in more than one column.

Steps should be:
1. Data Cleaning ( including Feature Selection)
2. Training ( on Y percent of data)
3. Testing ( on (100-Y) percent of data)
4. Evaluate the performance using metrics such as accuracy, precision, recall and F1-score.


# This dataset appears to contain information about agents and their interactions with potential clients interested in renting accommodations. 
* Unnamed: 0: an index column
* Agent_id: unique identifier for each agent
* status: status of the interaction (LOST, WON, etc.)
* lost_reason: reason for losing the potential client
* budget: budget range of the potential client
* lease: duration of the lease
* movein: move-in date for the potential client
* source: identifier for the source of the lead
* source_city: city where the lead originated
* source_country: country where the lead originated
* utm_source: identifier for the source of the lead
* utm_medium: identifier for the medium of the lead (e.g. youtube ads, banner, etc.)
* des_city: city where the potential client is looking to rent
* des_country: country where the potential client is looking to rent
* room_type: type of room the potential client is looking for
* lead_id: unique identifier for each lead
