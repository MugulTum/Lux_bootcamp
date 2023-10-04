**Lux_bootcamp**
This repository contains the projects that I did while attending the Lux Academy bootcamp between Sept 27th and October 27th 2023
Read me project week 1: predicting customer churn
Imagine you're working with Sprint, one of the biggest telecom companies in the USA. They're really keen on figuring out how many customers might decide to leave them in the coming months. Luckily, they've got a bunch of past data about when customers have left before, as well as info about who these customers are, what they've bought, and other things like that.
So, if you were in charge of predicting customer churn how would you go about using machine learning to make a good guess about which customers might leave? Like, what steps would you take to create a machine learning model that can predict if someone's going to leave or not?
Here is the breakdown on how I would solve the problem.
**Breakdown solution:**
1.	Defining churn. Defining churn is about stating for what period of inactivity should a customer be considered a churn. 
2.	Data collection and preparation: The first step is to collect and prepare the data. This includes cleaning the data, removing any outliers, and converting categorical variables to numerical variables. I downloaded a Kaggle dataset for this project. 
3.	Feature engineering: Once the data is clean and prepared, I would perform feature engineering. This involves creating new features from the existing data that may be more predictive of churn. For my dataset, there is a column named churn which takes Boolean values and therefore I do not think there is a need for further feature engineering. 
4.	Model selection: Next, I would select a machine learning model. There are many different machine learning models that can be used for churn prediction, such as logistic regression, decision trees, and random forests. I would choose a model that is appropriate for the data that I have and that has performed well on other churn prediction tasks.
5.	Model training: Once I have selected a model, I would train it on the data. This involves feeding the model the data and allowing it to learn the relationships between the features and the target variable (churn).
6.	Model evaluation: Once the model is trained, I would evaluate its performance on a held-out test set. This involves feeding the model the test set data and seeing how well it predicts churn.

 
