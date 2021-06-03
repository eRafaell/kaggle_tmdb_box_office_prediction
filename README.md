### TMDB Box Office Prediction

Kaggle competition predicting movies revenues. 
Competition Link: https://www.kaggle.com/c/tmdb-box-office-prediction

#### Problem statement
> In this competition, you're presented with metadata on over 7,000 past films from The Movie Database to try and predict their overall worldwide box office revenue. Data points provided include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries. You can collect other publicly available data to use in your model predictions, but in the spirit of this competition, use only data that would have been available before a movie's release.

> Submissions are evaluated on Root-Mean-Squared-Logarithmic-Error (RMSLE) between the predicted value and the actual revenue. Logs are taken to not overweight blockbuster revenue movies.

From the competition [link](https://www.kaggle.com/c/tmdb-box-office-prediction)

#### Goal of the project
The goal of the project was to predict the revenue of movies at the box office.

#### Project Details
- Exploratory data analysis and visualization
- Preprocessing with dealing with missing values, encoding categorical features and distribution for numerical features 
- Feature engineering and creating more features
- Building pipeline to fit various machine learning models
- Evaluating the models using RMSE metric
- Choosing the best model and improving it by using RandomizedSearchCV


#### Results of RMSE for used models

| Model | RMSE |
| ------ | ------ |
| XGBoost | 2.0507 |
| Gradient Boosting | 2.0696 |
| Linear Regression | 2.1917|
| Ridge | 2.1943 |
| ElasticNet | 2.1971 |
| Lasso | 2.2607 |
| Decision Tree | 2.2620 |

The result of RMSE for XGBoost after hyperparameter optimization equaled **2.0435**
