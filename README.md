# Bloc 3 : [Predictive analysis of structured data using artificial intelligence 📁🔍 ] Mandatory for JedhaBootcamp certification

Here you can explore various projects around Machine Learning Algorithms : ( read below the description and goals of each project 🌋).

Don't hesitate to follow each ReadMe of every projet if you would like to run it 😼🔎

1) Walmart Sales 
2) Convertion rate 
3) Uber Pickups

Mail : fezzibasma@gmail.com

Vidyard Link : [#](https://share.vidyard.com/watch/JahVymiEY5KXERvv8au1Uc?) 

# First project : UBER Pickups ( Unsupervised Machine-Learning )

#### Company's Description 📇
Uber is one of the most famous startup in the world. It started as a ride-sharing application for people who couldn't afford a taxi. Now, Uber expanded its activities to Food Delivery with Uber Eats, package delivery, freight transportation and even urban transportation with Jump Bike and Lime that the company funded.
The company's goal is to revolutionize transportation accross the globe. It operates now on about 70 countries and 900 cities and generates over $14 billion revenue! 😮

#### Project 🚧
One of the main pain point that Uber's team found is that sometimes drivers are not around when users need them. For example, a user might be in San Francisco's Financial District whereas Uber drivers are looking for customers in Castro.

(If you are not familiar with the bay area, check out Google Maps)

Eventhough both neighborhood are not that far away, users would still have to wait 10 to 15 minutes before being picked-up, which is too long. Uber's research shows that users accept to wait 5-7 minutes, otherwise they would cancel their ride.

Therefore, Uber's data team would like to work on a project where their app would recommend hot-zones in major cities to be in at any given time of day.

#### Goals 🎯
Uber already has data about pickups in major cities. Your objective is to create algorithms that will determine where are the hot-zones that drivers should be in. 
Create an algorithm to find hot zones
Visualize results on a nice dashboard
Scope of this project 🖼️
To start off, Uber wants to try this feature in New York city.


## Result with k-means : 

 <img width="964" alt="image" src="https://user-images.githubusercontent.com/23299967/207673475-70078a5a-d632-4738-8108-1724d8b6a3f8.png">
 
## Result with dbscan : 
<img width="976" alt="image" src="https://user-images.githubusercontent.com/23299967/207673690-41f47e07-7bf3-4c49-9d9b-926cf81839cd.png">


# Second project : Walmart Sales ( Supervised Machine-Learning ) 

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

# Third project : Predict conversions 🏆🏆 ( Supervised Machine-Learning ) 

#### Company's Description 📇
www.datascienceweekly.org is a famous newsletter curated by independent data scientists. Anyone can register his/her e-mail address on this website to receive weekly news about data science and its applications !

#### Project 🚧
The data scientists who created the newsletter would like to understand better the behaviour of the users visiting their website. They would like to know if it's possible to build a model that predicts if a given user will subscribe to the newsletter, by using just a few information about the user. They would like to analyze the parameters of the model to highlight features that are important to explain the behaviour of the users, and maybe discover a new lever for action to improve the newsletter's conversion rate.

They designed a competition aiming at building a model that allows to predict the conversions (i.e. when a user will subscribe to the newsletter). To do so, they open-sourced a dataset containing some data about the traffic on their website. To assess the rankings of the different competing teams, they decided to use the f1-score.

#### Goals 🎯
The project can be cut into four steps :

Part 1 : make an EDA and the preprocessings and train a baseline model with the file data_train.csv
Part 2 : improve your model's f1-score on your test set (you can try feature engineering, feature selection, regularization, non-linear models, hyperparameter optimization by grid search, etc...)

## Result with different algorithms : 

## Gradient Descent Stochastic Classifier and XGDC ( XGBoost with extreme Gradient descent ) performs very well with overfitting. XGBoost applies a better regularization technique to reduce overfitting, and it is one of the differences from the gradient boosting.

<img width="1069" alt="image" src="https://user-images.githubusercontent.com/23299967/207675151-b1f21b15-aefc-409b-a3d0-ca8ec0960043.png">





