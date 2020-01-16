# Recommendation-system-using-meetup-data
## *How to build a recommendation system from scratch?*

![Image description](meetup_logo.png) <br />
Image source: https://www.meetup.com/apps/ 

## Task 

Recommendation engines are super simple or atleast, they are made to seem super simple by the countless number of online tutorials that uses either a movie or a song dataset. This project focuses on building a recommendation system from scratch - extract real data, structure it and build several recommendation systems. 

Meetup is service used to organize events for users with similar interests. Meetup generates revenue from the group owners - the higher the number of members in the groups, the higher the membership fee/revenue. Evidently, any significant improvement in the engagement of the users would result in increased revenue. One of the ways to increase engagement is to personalize the events/groups recommendation in the meetup platform so that users are encouraged to attend more events. In this project, a few recommendation systems were built using the  data extracted from the meetup API. 

## Evaluation 
The recommendation system was evaluated using the Area Under the ROC curve for a fixed recommendation set size.

## Approach

1) Data Source: Extracted data of Austin, Texas using Meetup API to extract JSON objects of events, groups, rsvp counts etc.  
2) Data wrangling to create user-item matrix 
3) Hyperparameter tuning using PySpark on the Databrick platform 
4) Final recommendations using the selected hyperparameters 

## Results 

## Credits
- Starter code has been taken from [Sumit Kumar Arora](https://github.com/reachsumit).
