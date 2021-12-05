# Kaggle Diamonds Competition 💎

![foto](https://github.com/AnaWalsh/W7-Kaggle_competition/blob/main/images/diamonds.png)

## Objective

The objective of this project is to find the best machine learning model for a given dataset from [kaggle.](https://www.kaggle.com/c/diamonds-datamad1021-rev/data)

We were asked to do this project at the Ironhack Data Analytics Bootcamp.


## Structure of the project files

- Notebooks: one for cleaning the data and another one for doing predictions.

- src: functions that were used in the cleaning notebook.
        
- data: Diamonds dataset from [kaggle.](https://www.kaggle.com/c/diamonds-datamad1021-rev/data)

- Predictions: csv with the results of the predictions that were made.

- A slide with a summary of the obtained metrics and the rationale behind it.



## Working plan

**1.** Explore and clean the data. 

**2.** For the prediction I trained the following models (in the best ones I adjusted the parameters through grid search)

- Linear Regression (RMSE : 1244.55)

- Ridge (RMSE : 1244.53)

- Lasso (RMSE : 1244.48)

- SGD (RMSE : 99594178.25)

- KNeighbors (RMSE : 1898.34

- Random Forest (RMSE : 557.09)

- Gradient (RMSE : 596.05)


**3.** Make a prediction with the  best prediction model based on the value obtained with the RMSE: Random Forest


## Libraries

[Pandas](https://pandas.pydata.org/docs/)

[Matplotlib](https://matplotlib.org/)

[Seaborn](https://seaborn.pydata.org/)

[Numpy](https://numpy.org/doc/)

[Sklearn](https://scikit-learn.org/stable/)




