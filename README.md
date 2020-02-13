# Instruction for web application

## Overview
The app.py file contains a simplified application that can be run standalone:
```
$ flask run
```
## Usage
1.If you want to check home page, go to the link below:
http://127.0.0.1:5000/

2.If you want to get the prediction with some data, go to the link below(example):
 http://127.0.0.1:5000/predict?date=2012-10-01T18:00:00&weathersit=1&temperature_C=15&feeling_temperature_C=14&humidity=20&windspeed=5
you can change the value of any parameters, or you can also ignore some parameters, in this case it will impute the ignored parameters with mean value of the train dataset.

3.If you want to get the train score of the model you choose(xgboost or ridge), go to the link below(example):
http://127.0.0.1:5000/score?model=ridge
you can ignore the model parameter, it will take model as the default value, xgboost. You can also set the model parameter as ridge or xgboost, which will give you the train score respectively.

