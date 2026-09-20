# ML-Regression-Models-
This dataset contains online reservation records from customers booking accommodation. The data captures a variety of features describing customer behaviors, booking timeframes, operational requirements, and transaction details.Got this dataset from Kaggle.
Building machine learning regression models to predict the average price per room.
The project covers the complete machine learning workflow, including data cleaning, exploratory data analysis (EDA), preprocessing, feature scaling, model training, and model evaluation.


Total Observations: 36,275 entries
Total Features: 19 original columns

The dataset contains hotel booking information such as:
Lead time
Number of adults
Number of children
Number of weekend nights
Number of week nights
Type of meal plan
Required parking spaces
Room type reserved
Number of special requests
Market segment type
Average price per room
Booking status



Target Variable: 
The model is set up as a regression task using avg_price_per_room as the dependent variable
The target variable represents the average price per room, making this a regression problem because the target is a continuous numerical value

Feature Engineering: 
Categorical traits (type_of_meal_plan, room_type_reserved, market_segment_type) were encoded into dummy indicators via one-hot encoding


The main objectives of this project are:
Clean and preprocess the hotel reservation data.
Perform exploratory data analysis.
Analyze relationships between different features.
Prepare the data for machine learning.
Apply feature scaling and categorical encoding.
Build multiple regression models.
Evaluate model performance using regression metrics.
Compare the performance of different models.


The following preprocessing steps were performed for datacleaning
Checked dataset shape and information.
Checked for missing values.
Checked for duplicate records.
Removed unnecessary Booking_ID column.
Examined categorical and numerical variables.
Checked numerical distributions and potential outliers.


Regression Models
The following regression algorithms were implemented:
Linear regression 
decision tree
random forest
svr
knn


Performance Benchmark: 
A K-Neighbors Regressor (KNN) implementation currently achieves the highest \(R^{2}\) performance metrics with an approximate score of 66%.
