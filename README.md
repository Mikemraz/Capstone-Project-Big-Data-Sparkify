# Udacity Nanodegree big data Capstone Project--Sparkify


## Project Backgound
### Motivations
developing Skills of:  
1. Loading large datasets into Spark and manipulating them using Spark SQL and Spark Dataframes
2. Using the machine learning APIs within Spark ML to build and tune models
3. Integrating the skills I've learned in the Spark course and the Data Scientist Nanodegree program

### Task and Datasets 
the goad is to predict churned users based on activites and attributes data of them. And deploy the solution on a distributed system.
The size of original datasets is 12GB. Due to the limited computation power of free version of IBM Cloud, a medium-sized sub-datasets is utilized.  

### frameworks needed to run this jupyter notebook:
1. Pyspark SQL and Pyspark ML and other libraries it is building on.
2. Matplotlib for visualization.
3. IBM Cloud(free) or other Clould sevices.

## Summary of Project
Procedures of analysis:  
1. data cleaning
2. data exploration
3. feature engineering
4. modelling
5. deploy on IBM cloud

Results:  
Two models, logistice regression and random forest, with different hyperparameters are tested. Random forest was found to 
yield better performance (AUC score of 0.6) thus was selected as final proposal.

## Other deliverables
Summary and some flections on this project: [Medium post](https://medium.com/@jlm3448179892009/get-my-hands-dirty-with-big-data-for-the-first-time-50788c975cef)

## Acknowledgement
The dataset is kindly provided by Udacity team. And some instructions in the notebook are also well prepared by Udacity team.