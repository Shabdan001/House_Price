# House price prediction
The “House Prices” dataset is often used in regression and data analysis tasks to predict real estate prices based on various characteristics of houses. This dataset contains information about homes in Ames, Iowa, and contains many features that describe the physical and economic characteristics of properties.

# Used tools

Missing value imputation:
1. CategoricalImputer
2. MeanMedianImputer

Rare labels:
1. RareLabelEncoder

Encoder:
1. OneHotEncoder
2. OneHotEncoder(top_categories)
3. MeanEncoder

Discretizator:
1. EqualFrequencyDiscretiser

Feature Selection:
1. DropConstantFeatures
2. DropDuplicateFeatures
3. SmartCorrelatedSelection

Scaler:
1. StandardScaler

# ML Models Regression from Scikit-Learn

 1. LinearRegression
 2. Lasso
 3. ElasticNet
 4. LogisticRegression 
 5. SVR 
 6. DecisionTreeRegressor 
 7. RandomForestRegressor
 8. GradientBoostingRegressor
 9. KNeighborsRegressor
10.  XGBoost: XGBRegressor

# Regression metrics

1. mean_squared_error
2. mean_absolute_error
3. r2_score
4. root_mean_squared_error

### We used pipeline and GridSearchCV for finetuning model 
