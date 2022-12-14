# Bloc 3 : [Predictive analysis of structured data using artificial intelligence 📁🔍 ] Mandatory for JedhaBootcamp certification

Here you can explore various projects around Machine Learning Algorithms : ( see under the description and goals of each project).

Don't hesitate to follow each ReadMe of every projet if you would like to run it 😼🔎

1) Walmart Sales 
2) Convertion rate 
3) Uber Pickups

Mail : fezzibasma@gmail.com

Vidyard Link : 


# First project : Walmart Sales ( Supervised Machine-Learning ) 

## Walmart Sales : predict weekly sales

### Company's Description 📇
Walmart Inc. is an American multinational retail corporation that operates a chain of hypermarkets, discount department stores, and grocery stores from the United States, headquartered in Bentonville, Arkansas. The company was founded by Sam Walton in 1962.

#### Project 🚧
Walmart's marketing service has asked you to build a machine learning model able to estimate the weekly sales in their stores, with the best precision possible on the predictions made. Such a model would help them understand better how the sales are influenced by economic indicators, and might be used to plan future marketing campaigns.

#### Goals 🎯
The project can be divided into three steps:

Part 1 : make an EDA and all the necessary preprocessings to prepare data for machine learning
Part 2 : train a linear regression model (baseline)
Part 3 : avoid overfitting by training a regularized regression model
Scope of this project 🖼️
For this project, you'll work with a dataset that contains information about weekly sales achieved by different Walmart stores, and other variables such as the unemployment rate or the fuel price, that might be useful for predicting the amount of sales. The dataset has been taken from a Kaggle competition, but we made some changes compared to the original data. 🤓








# Second project : Predict conversions 🏆🏆 ( Supervised Machine-Learning ) 

In this project, you will participate to a machine learning competition like the ones that are organized by https://www.kaggle.com/. You will be able to work with jupyter notebooks as usual, but in the end you'll have to submit your model's predictions to your teacher/TA, so your model's performances will be evaluated in an independent way. The scores achieved by the different teams will be stored into a leaderboard 🏅🏅

#### Description of a machine learning challenge 🚴🚴
In machine learning challenges, the dataset is always separated into to files :
data_train.csv contains labelled data, which means there are both X (explanatory variables) and Y (the target to be predicted). You will use this file to train your model as usual : make the train/test split, preprocessings, assess performances, try different models, fine-tune hyperparameters etc...
data_test.csv contains "new" examples that have not be used to train the model, in the same format as in data_train.csv but it is unlabeled, which means the target Y has been removed from the file. Once you've trained a model, you will use data_test.csv to make some predictions that you will send to the organizing team. They will then be able to assess the performances of your model in an independent way, by preventing cheating 🤸
Your model's predictions will be compared to the true labels and releases a leaderboard where the scores of all the teams around the world are stored
All the participants are informed about the metric that will be used to assess the scores. You have to make sure you're using the same metric to evaluate your train/test performances !

#### Company's Description 📇
www.datascienceweekly.org is a famous newsletter curated by independent data scientists. Anyone can register his/her e-mail address on this website to receive weekly news about data science and its applications !

#### Project 🚧
The data scientists who created the newsletter would like to understand better the behaviour of the users visiting their website. They would like to know if it's possible to build a model that predicts if a given user will subscribe to the newsletter, by using just a few information about the user. They would like to analyze the parameters of the model to highlight features that are important to explain the behaviour of the users, and maybe discover a new lever for action to improve the newsletter's conversion rate.

They designed a competition aiming at building a model that allows to predict the conversions (i.e. when a user will subscribe to the newsletter). To do so, they open-sourced a dataset containing some data about the traffic on their website. To assess the rankings of the different competing teams, they decided to use the f1-score.

#### Goals 🎯
The project can be cut into four steps :

Part 1 : make an EDA and the preprocessings and train a baseline model with the file data_train.csv
Part 2 : improve your model's f1-score on your test set (you can try feature engineering, feature selection, regularization, non-linear models, hyperparameter optimization by grid search, etc...)






# Third project : UBER Pickups. ( Unsupervised Machine-Learning )

#### Company's Description 📇
Uber is one of the most famous startup in the world. It started as a ride-sharing application for people who couldn't afford a taxi. Now, Uber expanded its activities to Food Delivery with Uber Eats, package delivery, freight transportation and even urban transportation with Jump Bike and Lime that the company funded.
The company's goal is to revolutionize transportation accross the globe. It operates now on about 70 countries and 900 cities and generates over $14 billion revenue! 😮

#### Project 🚧
One of the main pain point that Uber's team found is that sometimes drivers are not around when users need them. For example, a user might be in San Francisco's Financial District whereas Uber drivers are looking for customers in Castro.

(If you are not familiar with the bay area, check out Google Maps)

Eventhough both neighborhood are not that far away, users would still have to wait 10 to 15 minutes before being picked-up, which is too long. Uber's research shows that users accept to wait 5-7 minutes, otherwise they would cancel their ride.

Therefore, Uber's data team would like to work on a project where their app would recommend hot-zones in major cities to be in at any given time of day.

#### Goals 🎯
Uber already has data about pickups in major cities. Your objective is to create algorithms that will determine where are the hot-zones that drivers should be in. Therefore you will:

Create an algorithm to find hot zones
Visualize results on a nice dashboard
Scope of this project 🖼️
To start off, Uber wants to try this feature in New York city. Therefore you will only focus on this city. Data can be found here:

👉👉 Uber Trip Data 👈👈

You only need to focus on New York City for this project



