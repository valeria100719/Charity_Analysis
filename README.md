# Charity_Analysis

The informatic system was used to assess whether non-profit candidates will be successful if funded by Alphabet Soup.

We started our analysis with 34,000 organizations and information related to their funding history, income, status and whether or not they were successful.
The data was pre-processed and optimized for accuracy of 75% or better.

## Analysis
The target variable for this model was the "IS_SUCCESSFUL" variable.
The features of this model are "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS" and "ASK_AMT".
The variables that are superfluous for our analysis have been removed from the input data are the non-advantageous ID columns; "EIN" and "NAME".

A binary classifier that is capable of predicting whether or not an applicant will be successful if funded by Alphabet Soup using the features collected in the provided dataset is created.

## Results
I was unable to achieve target model performance.
In an effort to optimize the performance of my models, I added more layers, and changed the optimization feature on hidden layers. 
See the figures below
 fig1
![alt text](https://github.com/valeria100719/Charity_Analysis/blob/main/pics/1.png?raw=true)
 fig2
![alt text](https://github.com/valeria100719/Charity_Analysis/blob/main/pics/2.png?raw=true)
 fig3
![alt text](https://github.com/valeria100719/Charity_Analysis/blob/main/pics/3.png?raw=true)



## suggestions

I would use Random Frorest Classifiers as an alternative to solve the classification problem. This model combines multiple smaller models into a more robust and accurate model. The data would be easy to be transformed and fit into this model.
