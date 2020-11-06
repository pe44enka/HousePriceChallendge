## House Price Challenge

### Description 
This notebook is created as a part of **House Prices: Advanced Regression Techniques** Kaggle challenge and supposed to predict sale price of houses.

### Objectives
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. If we look closer at the dataset describing (almost) every aspect of houses we can see there are much more influences price negotiations than the number of bedrooms or a white-picket fence.

### Goal of the project
To built ML model to predict the final price of each house.

### Data
Data is available at [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview) as part of competition.

### Techniques
In this project following techniques are used:
* **Data preprocessing**: SelectFromModel, SimpleImputer, OneHotEncoder, StandardScaler, ColumnTransformer, pandas.get_dummies
* **ML algorihms**: LinearRegression, DecisionTreeRegressor RandomForestRegressor, GradientBoostingRegressor, XGBRegressor 
* **Hyperparameter turning:** GridSearchCV
* **Model training/applying:** Pipeline, tran_test_split

### Installation:
You shouldn't really install this code, just click on the "HousePriceChallenge.ipynb" file and in the follow window click on "Open in Colab" button. This will redirect you on [Colab](colab.research.google.com) by Google website. 
