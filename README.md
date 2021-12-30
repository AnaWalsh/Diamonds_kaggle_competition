# Kaggle Diamonds Competition 💎

![foto](https://github.com/AnaWalsh/W7-Kaggle_competition/blob/main/images/diamonds.png)

## Goal 🏁

The objective of this project is to find the best machine learning model for a given dataset from [kaggle.](https://www.kaggle.com/c/diamonds-datamad1021-rev/data)

We were asked to do this project at the Ironhack Data Analytics Bootcamp.


## Structure of the project files 

- Notebooks: one for cleaning the data and another one for doing predictions.
       
- data: Diamonds dataset from [kaggle.](https://www.kaggle.com/c/diamonds-datamad1021-rev/data)

- Predictions: csv with the results of the predictions that were made.


## Working plan

**1.** Explore and clean the data. 🧐

We have followed the criteria provided by the GIA (Gemological Institute of America) to recategorize some columns of our dataset:

- **Color**

    GIA categorizes diamond according to colour into five groups:

   - "Colorless" (D-F): These are the most rare, and therefore the most valuable.
    
   - "Near colorless" (G-J): Color is often unnoticeable except by trained graders. 
    
   - "Faint" (K-M) : Color is still difficult to see by the untrained eye.
    
   - "Very light" (N-R) : Subtle color can be seen in larger stones by an untrained eye. 
    
   - "Light" (S-Z) : Color can be seen in stones of different sizes. The diamons appear slightly yellow or brown but do not have sufficient color to be considered a "fancy" colored diamond. 

![foto](https://github.com/AnaWalsh/Kaggle_competition/blob/main/images/diamond-color-scale.png)

- **Clarity**

    The GIA Clarity Scale contains 11 grades, with most diamonds falling into the VS (very slightly included) or SI (slightly included) categories. In determining a clarity grade, the GIA system considers the size, nature, position, color or relief, and quantity of clarity characteristics visible under 10× magnification

    - Flawless (FL):  No inclusions or blemishes are visible to a skilled grader using 10× magnification

    - Internally Flawless (IF):  No inclusions and only blemishes are visible to a skilled grader using 10× magnification

    - Very, Very Slightly Included (VVS1 and VVS2): Inclusions are difficult for a skilled grader to see under 10× magnification

    - Very Slightly Included (VS1 and VS2): Inclusions are minor and range from difficult to somewhat easy for a skilled grader to see under 10x magnification

    - Slightly Included (SI1 and SI2): Inclusions are noticeable to a skilled grader under 10x magnification

    - Included (I1, I2, and I3): Inclusions are obvious under 10× magnification and may affect transparency and brilliance

![foto](https://github.com/AnaWalsh/Kaggle_competition/blob/main/images/diamondclarityscalegia.jpeg)


**2.** For the prediction I trained the following models (in the best ones I adjusted the parameters through grid search)

- Linear Regression (RMSE : 1244.55)

- Ridge (RMSE : 1244.53)

- Lasso (RMSE : 1244.48)

- SGD (RMSE : 99594178.25)

- KNeighbors (RMSE : 1898.34

- Random Forest (RMSE : 557.09)

- Gradient (RMSE : 596.05)


**3.** Make a prediction with the  best prediction model based on the value obtained with the RMSE: Random Forest


## Libraries 📚

[Pandas](https://pandas.pydata.org/docs/)

[Matplotlib](https://matplotlib.org/)

[Seaborn](https://seaborn.pydata.org/)

[Numpy](https://numpy.org/doc/)

[Sklearn](https://scikit-learn.org/stable/)


## TO DO 📝

- Compare test and train to analyze overfitting.

- Train models without previously deleting columns that showed collinearity. 

- Give H2O a try.




