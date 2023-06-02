![Alt Text](./Images/Churn.png)


# FPandA_Churn_Model
Using Decision Tree Classification Model to predict customer churn.


# Data & Work
Data understanding - Interestingly this is not actually SyriaTel Customer data as SyriaTel was one of the two largest telecom providers in Syria and the data is of customers in all of the 50 USA states. Data on the reference site has little to no background info on this data.


CLeaning - Dropped personally identifying info. Data was fairly clean from start and did not need null handling after using pd.get_dummies to dummy out the necessary columns.
Cleaning can be found in the multiple files other than the final file (plan to circle back on this project after bootcamp to finalize the project - want to keep my work resources for reference at that time).

Interestingly, the use of SMOTE to oversample the Churn data did not improve the model. It brought  the scores down. SMOTE was not used for the final model.


# 'Churn Analysis - Final File' Jupyter Notebook used for Analysis
Analysis - reference 'Churn Analysis - Final File' for work analysis. Decision Tree was developed to predict Churn customers.


# Presentation
https://docs.google.com/presentation/d/1AS6WV29iYggkqiov86pNoTbis5sj8LAQG-fOF7cthws/edit#slide=id.g22612c97c33_0_236






































# Reference Info

# Data from project:
SyriaTel Customer ChurnLinks to an external site.
Build a classifier to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company. This is a binary classification problem.

Most naturally, your audience here would be the telecom business itself, interested in reducing how much money is lost because of customers who don't stick around very long. The question you can ask is: are there any predictable patterns here?


# Data from website:
Churn in Telecom's dataset

About Dataset:
No description available

Collaborators:
david_becks (Owner)

All other info is blank


