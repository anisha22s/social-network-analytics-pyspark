# social-network-analytics
# Social Network Analysis in PySpark: A Venmo Transaction Case Study

## Project Overview
This project conducts a social network analysis on a dataset of Venmo transactions, leveraging the power of PySpark to process large-scale data. We have implemented various social network metrics and features to understand the users' behavior on Venmo.

(Note: Due to privacy concerns, the dataset used in this project can't be shared publicly.)

## Features and Metrics
Friends and Friends of Friends: We've implemented a script to identify a user's direct friends (those they've transacted with) and their friends of friends.

Dynamic Analysis: We've performed a dynamic analysis of the following social network metrics across a user’s lifetime in Venmo (from 0 up to 12 months):

Number of Friends and Number of Friends of Friends: We've computed the count of a user's direct friends and indirect friends over time.

Clustering Coefficient: We've calculated the clustering coefficient of a user's network to understand the degree to which their friends are also friends with each other.

PageRank: We've computed the PageRank of each user with the help of the graphframes package to identify influential users in the Venmo network.

## Dataset
The dataset includes the following fields: user1, user2, transaction_type, datetime, description, is_business, story_id.

## Tools and Libraries
PySpark   
Graphframes  
