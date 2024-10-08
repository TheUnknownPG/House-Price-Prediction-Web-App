# House Price Prediction with Machine Learning
**A website where user can get an estimate price of a house at certain places in USA by entering certain requirements of the user. <br />The website is connected to a Machine Learning model that is trained on a dataset containing prices of different property all across USA.**

## About the website:
The website is a single page HTML coded frontend which is connected on the backend with the help of flask.

Components on the site:
1. Location of the property (Drop-Down)
2. Area in Sq/Ft (Input)
3. No. of Bedrooms (Input)

## About the model:
The model has been trained on the dataset "[Housing Prices in USA](https://www.kaggle.com/datasets/vedavyasv/usa-housing)". The training algorithm in use is [LinearRegresson](https://scikit-learn.org/dev/modules/generated/sklearn.linear_model.LinearRegression.html).
The dataset was broken into **70/30** ratio with random state of 0.


## Requirements: 
Following libraries are required:
1. Sci-kit Learn (Sklearn)
2. Pandas
3. Flask
4. Numpy
5. Django

## ScreenShots:
### Home:
<p> <img src = "templates/Picture1.jpg" height="700">    <img src = "templates/Picture2.jpg" height="700"> </p><br>

### Prediction:

<p> <img src = "templates/Picture3.jpg" height="700">    <img src = "templates/Picture4.jpg" height="700"> </p><br>

