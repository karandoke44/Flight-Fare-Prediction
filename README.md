# Flight Fare Prediction: 

Nowadays, airline ticket prices can vary dynamically for the same flight. Customers are seeking to get the lowest price while airlines are trying to keep their overall revenue as high as possible and maximize their profit. Airlines use various kinds of computational techniques to increase their revenue such as demand prediction and price discrimination. But from customer perspective they want to save money so i have proposed a model that predicts the approximate ticket price so that customer can find when is the optimal time to buy a ticket is. 

The Flight Fare Prediction predict the flight price using XGBoost regression based Machine Learning algorithms and helps users look for optimal time and prices to book flight tickets.
## Table of Content
  * [Demo](#demo)
  * [Dataset](#dataset)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Bug Request](#bug-request)
  * [Future scope of project](#future-scope)


## Demo
Heroku Link: [https://flight-fare-prediction-kd.herokuapp.com/](https://flight-fare-prediction-kd.herokuapp.com/)

[![](https://i.postimg.cc/CL1xCghv/flight-pre-prediction.jpg)](https://flight-fare-prediction-kd.herokuapp.com/)

[![](https://i.postimg.cc/FKQfVBn7/flight-result-prediction.jpg)](https://flight-fare-prediction-kd.herokuapp.com/)

## Dataset


- [Dataset Link](https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh)

## Overview
This is a Flask web app which predicts fare of Flight ticket.

## Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning model to get most out of it. I came to know mathematics behind all supervised models. Finally it is important to work on application (real world application) to actually make a difference.

## Installation
The Code is written in Python 3.10.1. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

**Clone the repository**

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.

Open a terminal and run the following git command:
```bash
    git clone "url you just copied"
```

create an environment with python version=3.10

```bash
    conda create -n yourenvname python=3.10
```
activating yourenvname
```bash
    activate yourenvname
```
cd to the directory where requirements.txt is located.
```bash
    C:\Users>cd where requirements.txt is located
```
install necessary libraries in yourenvname
```bash
    pip install -r requirements.txt
```
Now you are good to run the python scripts and ipynb files

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

Steps for deployment:-
```bash
   heroku
   heroku login
   git init
   git add .
   git commit -m "Initial Commit"
   heroku create [project name]
   git remote -v
   git push heroku master
```

## Directory Tree 
```
├── template
│   ├── home.html
├── Procfile
├── Docs of HLD,LLD,DPR
    ├── ARCHITECTURE FLIGHT FARE.pdf
    ├── DETAIL PROJECT REPORT FLIGHT FARE.pdf
    ├── HIGH LEVEL DESIGN FLIGHT FARE ESTIMATOR.pdf
    ├── LOW LEVEL DOCUMENT FLIGHT FARE.pdf
    ├── WIRE-FRAME FLIGHT FARE ESTIMATOR.pdf
├── README.md
├── app.py
├── flight_price.ipynb
├── flight_rf.pkl
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 


## Bug Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/karandoke44/Flight-Fare-Prediction/issues) here by including your search query and the expected result

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 
