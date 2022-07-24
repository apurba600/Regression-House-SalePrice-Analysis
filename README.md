# House-SalePrice-Analysis

Analyzing house features to find the most correlated features which can be helpful for real estate purposes.
This project also covers using machine learning model to predict the saleprice of the house.

LIBRARIES USED:
- Pandas: For Data wrangling and analysis
- Numpy: To deal with arrays
- matplotlib and Seaborn: For data visualization such as barchart, heatmap etc.
- Sklearn: For preprocessing data to train ML model, for ML models and metrics to validate 
- Ipython.display: To display the image in the notebook


FILES IN THE REPOSITORY:

- Dataset (CSV Files): Training dataset, Testing dataset, Submission sample sataset, Final_submission ( this is the predicted prices for the test set)
- Description file (txt file): Features detailed description
- README.md: Contains the details and summary of the project

QUESTIONS

- What are the most correlated features in a house to the sale price?
- What year were most of the houses built and does it have any correlation with the saleprice? is there variation in saleprice based on month?
- Can we use ML model to predict house saleprice given the same features with good axxuracy?

SUMMARY
- The most correlated features with sale price were Overall quality of the house, Ground level living area, number of Car garage.
- Most of the houses were built in the year 2005, 2006. On average the houses built after 1980 have higher Saleprice. There is also no significance    difference in terms of average saleprice based on month. September taking the lead.
- Cross validation and Gridsearch were used to find the best performing ML model with best performing hyper-parameter. The model chosen was gradient boosting regressor (Best_hyperparameter :  {'learning_rate': 0.1, 'loss': 'squared_error', 'n_estimators': 300}) to predict the house sale price. Which gave a decent RMSE score of 0.025 on the training set and 0.13 on the test dataset.

