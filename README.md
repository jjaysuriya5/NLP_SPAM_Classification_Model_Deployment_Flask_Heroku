# NLP_SPAM_Classification_Model_Deployment_Flask_Heroku

URL - https://jjnlpspamclassification-api.herokuapp.com/

The below step by step actions are performed to deploy the model

1) Model building
model.ipynb - This file contains the training model where Multi nomial naive bayes model is build on the input data and the model is saved as model.pkl file

-----------------

2) Creating Application
app.py - This File consist of Flask application where the user is asked to input the required field and the corresponding output is obtained when clicking the submit button

-----------------

3) Procfile
Procfile - This file contains the python server name and the flask application name

-----------------

4) requirements.txt
requirements.txt - This file contains the packages which are required for this project

-----------------

5) Heroku
Finally deploy the model using Heroku(PAAS) model bu connecting to this github repository
