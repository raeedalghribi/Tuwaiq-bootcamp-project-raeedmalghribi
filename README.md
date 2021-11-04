# Predicting the price value of FIFA players
Raeed Mohammed M Alghribi


## Abstract
The goal of this project is to analysis a list features of more than 16K pro-players that playing in FIFA (International Federation of Association Football), and to set a classification model to predict each player price base on the features that been given in the dataset. Based on the result, we can estimate the price value of new players.


## DATA
My dataset contains more than 16K cases with 22 features some of these features are [player_age, height_cm, weight_kg, position, movement_reactions, shooting, passing, preferred_foot, power_strength, movement_sprint_speed, value_eur …]. All columns are int except [position, preferred_foot] which are strings. Using multiple linear regression as my first algorithm with scaling to set the data patron in to suitable fit for the output prediction. Also, as we can see from the dataset some features can be categorical and XGBoost  model will performs well for this scenario, However, the end result will be compared to see the best predicting accuracy.
Dataset Ref:( https://www.kaggle.com/stefanoleone992/fifa-21-complete-player-dataset)





## Tools
•	Data Processing: Pandas, Numpy, Scipy.
•	Modelling: SciKit-Learn, PyTorch.
•	Visualization: Matplotlib, Bokeh







