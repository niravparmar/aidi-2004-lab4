
# determine-fish-species

This project focuses on determining the fish species based off of the length, width, height and weight of the said fish.

## Author

Name : Niravkumar Parmar
Student Id : 100855270
Subject : 2004 - AI in Enterprise
Course : Lab Assignment 4 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.txt.
The imp libraries included are:
- pandas
- numpy
- flask
- gunicorn
- sklearn

```python
pip install -r requirements.txt
```

## Usage

```python
python app.py
```

## Deployment

Currently the project is deployed on heroku.
The app can be accessed [here](https://fish-species-100855270.herokuapp.com/)

## Files

- model_training.ipynb contains the model structure
- Fish.csv is the dataset
- app.py is the main flask app
- templates/index.html has the html file
- static/css/style.css has the css file for the html
- model.pkl is the saved model
