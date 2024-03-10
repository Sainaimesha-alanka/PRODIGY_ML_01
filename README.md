# PRODIGY_ml_01
ML Internship at Prodigy InfoTech

Task - 01

Linear Regression model to predict the prices of houses
This repository contains code on Linear Regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms with the dataset from Kaggle Housing Prices Competition.

Description
Addressing real-world challenges, forecasting housing costs is a pivotal issue. Leveraging machine learning, this project endeavors to tackle the problem by delving into the realm of regression techniques. The objective is to analyze the dataset's features and ascertain the most precise model through Linear Regression Model.

Algorithm: Predict House Prices using Linear Regression
Step 1: Import Necessary Libraries
- Import required libraries such as numpy, pandas, matplotlib, seaborn, sklearn.
Step 2: Load the Data
- Read the training dataset ('train.csv') into a pandas DataFrame.
- Read the testing dataset ('test.csv') into a pandas DataFrame.
Step 3: Explore and Preprocess Data
- Explore the data using functions like df.head(), df.shape, df.info(), and df.isnull().sum().
- Handle missing data
- Explore and preprocess categorical features:
    - Handle missing values in categorical columns in both training and test datasets.
    - Perform one-hot encoding for categorical features.
Step 4: Feature Selection
- Select relevant features for the model.
- Analyze correlation between selected features and the target variable ('SalePrice').
Step 5: Data Visualization
- Visualize data using heatmaps and histograms to understand correlations and distributions.
Step 6: Split the Data
- Split the dataset into independent variables (X) and the target variable (y).
- Split the data into training and testing sets.
Step 7: Feature Scaling
- Standardize the feature variables using StandardScaler.
Step 8: Train a Linear Regression Model
- Create a Linear Regression model.
- Train the model using the training set.
Step 9: Make Predictions
- Use the trained model to make predictions on the test set.
Step 10: Evaluate the Model
- Calculate and display the Root Mean Squared Error (RMSE) to evaluate model performance.
- Visualize the predicted values against actual values using scatter plots and residual plots.
Step 11: Additional Analysis
- Analyze and interpret the results, such as the significance of selected features and any patterns in the residuals.
Step 12: Save or Deploy the Model
- If satisfied with the model, save the model for future use or deploy it for predictions.
Usage
Dataset from Kaggle Housing Prices Competition.
Used Jupiter Notebook for Python Coding.
Abbreviation in the dataset
SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
MSSubClass: The building class
MSZoning: The general zoning classification
LotFrontage: Linear feet of street connected to property
LotArea: Lot size in square feet
Street: Type of road access
Alley: Type of alley access
LotShape: General shape of property
LandContour: Flatness of the property
Utilities: Type of utilities available
LotConfig: Lot configuration
LandSlope: Slope of property
Neighborhood: Physical locations within Ames city limits
Condition1: Proximity to main road or railroad
Condition2: Proximity to main road or railroad (if a second is present)
BldgType: Type of dwelling
HouseStyle: Style of dwelling
OverallQual: Overall material and finish quality
OverallCond: Overall condition rating
YearBuilt: Original construction date
YearRemodAdd: Remodel date
RoofStyle: Type of roof
RoofMatl: Roof material
Exterior1st: Exterior covering on house
Exterior2nd: Exterior covering on house (if more than one material)
MasVnrType: Masonry veneer type
MasVnrArea: Masonry veneer area in square feet
ExterQual: Exterior material quality
ExterCond: Present condition of the material on the exterior
Foundation: Type of foundation
BsmtQual: Height of the basement
BsmtCond: General condition of the basement
BsmtExposure: Walkout or garden level basement walls
BsmtFinType1: Quality of basement finished area
BsmtFinSF1: Type 1 finished square feet
BsmtFinType2: Quality of second finished area (if present)
BsmtFinSF2: Type 2 finished square feet
BsmtUnfSF: Unfinished square feet of basement area
TotalBsmtSF: Total square feet of basement area
Heating: Type of heating
HeatingQC: Heating quality and condition
CentralAir: Central air conditioning
Electrical: Electrical system
1stFlrSF: First Floor square feet
2ndFlrSF: Second floor square feet
LowQualFinSF: Low quality finished square feet (all floors)
GrLivArea: Above grade (ground) living area square feet
BsmtFullBath: Basement full bathrooms
BsmtHalfBath: Basement half bathrooms
FullBath: Full bathrooms above grade
HalfBath: Half baths above grade
Bedroom: Number of bedrooms above basement level
Kitchen: Number of kitchens
KitchenQual: Kitchen quality
TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
Functional: Home functionality rating
Fireplaces: Number of fireplaces
FireplaceQu: Fireplace quality
GarageType: Garage location
GarageYrBlt: Year garage was built
GarageFinish: Interior finish of the garage
GarageCars: Size of garage in car capacity
GarageArea: Size of garage in square feet
GarageQual: Garage quality
GarageCond: Garage condition
PavedDrive: Paved driveway
WoodDeckSF: Wood deck area in square feet
OpenPorchSF: Open porch area in square feet
EnclosedPorch: Enclosed porch area in square feet
3SsnPorch: Three season porch area in square feet
ScreenPorch: Screen porch area in square feet
PoolArea: Pool area in square feet
PoolQC: Pool quality
Fence: Fence quality
MiscFeature: Miscellaneous feature not covered in other categories
MiscVal: $Value of miscellaneous feature
MoSold: Month Sold
YrSold: Year Sold
SaleType: Type of sale
SaleCondition: Condition of sale
Techniques
The following techniques are implemented in this project:
1.Linear Regression
2.Heatmap (correlation graph)
