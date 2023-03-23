<h1 align="center"> Bike Sharing Demand Prediction </h1>

<p align="center" width="100%">
    <img width="60%" src="https://img.freepik.com/free-vector/bicycle-isometric-composition_98292-6968.jpg?w=740&t=st=1674133479~exp=1674134079~hmac=a753032aae8d1c6b4bf31375f3036157162044150348041bdc8626a5aa4939d5">
</p>

<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p>The project gives the number of bikes required at a given point of time to keep operations going.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> Table of Content</h2>

  * Overview
  * Dataset Information
  * EDA and Feature Engineering
  * Model
  * Result

This project is aimed at providing the number bike required at any given point of time with high accuracy, with this the company can operate any friction.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)



<h2> Overview</h2>

With the help of 1 year data on bike sharing from Seoul has been used to build a Regression Machine Learning (ML) model. The model looked into the 1 year patterns of demands based on different features to build a model which is highly accurate to provide the number of bikes that are required at a given point of time. It is a very effective and optimum way of operating such kind of business where the demand is not constant.


<h3> Tools Used: <h3>

1. Python

2. Numpy and Pandas for data cleaning

3. Data visualization

4. Sklearn for model building

5. Jupiter Notebook

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> Dataset information</h2>

Raw Dataset:

<p align="left" width="100%">
    <img width="80%" src="https://user-images.githubusercontent.com/90998859/214131922-523fb5d0-3637-45a4-9e11-a868cbb786d6.png">
</p>


The final dataset has the following 12 features (1 dependent + 11 independent):
<p align="left" width="100%">
    <img width="80%" src="https://user-images.githubusercontent.com/90998859/214132230-6970a951-9d1a-4a5e-817f-afffca2e1ca2.png">
</p>

* rented_bikes (dependent) - number of rented bikes at a particular time

* hour (clock time 0-23)

* temperature (city temperature)

* humidity (city humidity)

* wind_speed (city wind speed)

* visibility (city visibility)

* solar_radiation

* rainfall (raining or not raining)

* snowfall (snowfalling or not snowfalling)

* holiday (if the day is an official holiday or a working day)

* month_name (January to December)

* week (weekday or weekend)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> EDA and Feature Engineering</h2>

Steps performed:

* Did univariate analysis on numerical features

* Divided datset into 'numerical' and 'categorical' features

* Plotted graphs such as Line Graph, Bar Graph, Strip Plot, etc to get insight into the dataset


* Outlier detection and treatment
<p align="left" width="100%">
    <img width="20%" src="https://user-images.githubusercontent.com/90998859/214135949-1b9ef876-cb0e-462a-ab3e-b6c0e9195f97.png">
</p>

* Performed square_root transformation on dependent feature to deal with the skewness
<p align="left" width="100%">
    <img width="30%" src="https://user-images.githubusercontent.com/90998859/214137973-3c9e5c01-8a2f-41ac-8905-924510da122c.png">
 </p>


* Plotted the scattered plot of numerical features with 'Linear Regression'

* Heat Map to know the correlation among features

* Employed VIF (Variance Inflation Factor) to deal with the highly corrleated features

* Converted categorical features such as 'hour', 'month' into numerical features with the help of OneHotEncoding



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> Model </h2>

* Performed Feature Scaling with MinMaxScaler on final dataset

<p align="left" width="100%">
    <img width="50%" src="https://user-images.githubusercontent.com/90998859/214135259-a569d366-260d-494a-bcd5-80e2075019ba.png">
    
</p>


* Following Four Regression Algorithms were trained

1. Linear Regression

2. Lasso Regression

3. Ridge Regularization

4. Random Forest Regression

* Evaluated every algorithm on Train and Test sets with MSE, RMSE, R2, and Adjusted R2

* Employed Cross Validation and Hyper parameter with GridSearchCV on Ridge Regression

* Performed Feature importance on Random Forest Regression 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> Result </h2>

Regression Model: Final Summary

* On Train Dataset

    
</p>


* On Test Dataset

    
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Tushar Raskar > | Data Science Enthusiast

<p> <i> Contact me for Data Science Project Collaborations and Research</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/chvikas/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/chvikas)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@chvikas)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Technologies Used::</h2>

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://user-images.githubusercontent.com/32620288/139657460-40ef4562-76bd-43f5-bbca-47b6bd29863e.png" width=100>](https://numpy.org)    [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/450px-Pandas_logo.svg.png" width=150>](https://pandas.pydata.org)  [<img target="_blank" src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width=150>](https://seaborn.pydata.org) [<img target="_blank" src="https://matplotlib.org/_static/logo2_compressed.svg" width=170>](https://matplotlib.org)   [<img target="_blank" src="https://user-images.githubusercontent.com/32620288/137518674-f36c5ad3-3d64-4c7a-a07c-53f247750394.png" width=170>](https://colab.research.google.com/)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

