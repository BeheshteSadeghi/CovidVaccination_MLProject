## Covid Vaccination

### I worked on a dataset of covid vaccination which includes informaiton about name of countries, name of vaccines and different statistics about vaccinations in each date.

### The focus of this project is on Data Cleaning, Data Analysis, Data Extraction for story-telling, Gaining an insight from Pycaret Regression tool over best ML algorithms,and finally comparing 4 top models for selecting the best.
### 
##
### Fisrt, different raws of raw dataset is investigated, to gain as much idea for storytelling, as possible. In this direction, interesting plots and tables are extracted.

### After choosing the country for modelling, data is cleaned. For filling missing values, a linear regression approach is chosen, based on the available data for this country in other dates.
### Then outliers are removed and data is scaled.

### After applying Pycaret over the cleaned data, top models are selected for hyper-parameter tuning:
#### 1. RandomForest
#### 2. Extratrees
#### 3. GradientBoosting
#### 4. CatBoost

### Then the performance of these models are compared together based on MAE factor.
### The best model (CatBoost model) is then saved using joblib module for further use.
