# Advance-machine-learning

Dataset link : http://archive.ics.uci.edu/ml/datasets/Bank+Marketing 
There are 41188 rows and 21 columns in the data set. 

# What's Problem are you tackling, and what's the setting we're considering? 
The overall problem we are tackling is that many banks want to know what type of customers would want to avail a campaign offer so that it will make them understand what type of users they should invest time into. We have set a baseline to first analyze the data through explanatory analysis, by explaining the data we set to analyze the problem statement by performing different classifiers, experimenting different ways to improve performance of those classifiers which can help in the prediction the campaign offers. The initial dataset is the banking dataset with 41188 rows and 21 features. Most features were categorial hence we tried to transform the data and use dummy variables to get in depth of each categorical variable within. The categorical variables were as following: 'job','marital','education','default','housing','loan','contact','month','day_of_week','poutcome'

# Which of the research questions have you tried to answer that you came up with during your proposal?
Our main research question is:
### To predict whether a customer avails term deposit or not.
However, we did another sub research question in order to analyze the following research question:

### Can willingness to subscribe for term deposit projects be predicted by education variable, marital status, job and other variables.
As these variables were categorical variables we can only analyze these through EDA, we came to a conclusion through the analysis that variables like education, martial, status does impact the term deposit as we saw that professionals with admin and blue collar jobs are more inclined towards accepting the term deposit. Also, customers who are married are more interested in accepting the term deposit. By looking at education variables we can also see that customers with a higher educational degree are more educated in terms of understanding the policies and terms to accept the term deposit. Furthermore, client whose job profession is admin have subcribed more to the bank deposit term. From all these analysis we came to a conclusion that material status and education has an impact towards term deposit.

### Average portrait of the person who is willing to subscribe to a term deposit.
From the analysis we have predicted that young people are Millennials that who are currently between 25 and 40 years old are tending towards acceptance of term deposits. These people are highly educated and married. They are also those individuals who are doing high level jobs such as blue collar jobs. As a typical portrait of a person X who is inclined towards term deposit is someone with a highest education level and married witha a blue color job.

# Which ML techniques have we tried? What others will we apply?
We tried 7 different classifiers which are randomforest, decision tree, logistic regression, gaussian naive bayes, k_nearestneighbors, gradient boosting and support vector. Further we performed hyper-parameter tuning and PCA analysis over these classifiers in order to analyze performance between the classifiers. We also used a feature importance method for tree-based models( Decision tree and random forest). Decision tree classifiers tend to overfit very easily by memorizing the training data so to reduce the overfitting we chose random forest.
