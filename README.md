# Practicum Projects:

## [Project 15: Interconnect Churn Forecasting Model](https://github.com/mnug1996/Project-15-Interconnect-Churn-Forecasting-Model)

- Created a model to predict client chrun (AUC-ROC: 0.85) to help the company target customers for promotional and special offers for client retention.
- Explored several different models an evaluated each one to find the best performing model.
- Analyzed class distribution in relation to client churn.
- Utilized feature importance methods (ExtraTreesClassifier & Heatmap) to explore the most influential factors

## [Project 14: Computer Vision Model for Age Verification in Grocery Store Alcohol Sales](https://github.com/mnug1996/Project-14-Computer-Vision-Model-for-Age-Verification-in-Grocery-Store-Alcohol-Sales)

- Created a computer vision model to verify customer's age (MAE: 7.98) to help a grocery store validate alcohol sales.
- Tuned model with tensforflow.keras methods (learning rate, augmentations, epochs, and density units) to achieve an accetpable model perfomance.
- Used tensorflow.keras ImageDataGenerator to process and manipulate 7591 images.
- Utilized a GPU (Practicum's server) to train and test the model.

## [Project 13: Model for Detection of Negative Movie Reviews](https://github.com/mnug1996/Project-13-Model-for-Negative-Movie-Review-Detection)

- Created a logistic regression model (f1: 0.88, ROC AUC: 0.95) to detect negative movie reviews
- Evaluated several models with varying pre-lemmatization methods; found that in this project lemmatization did not have a significant effect.
- Vectorized moview reviews using NLTK and TfidfVectorizater in order to use the data for model training.
- Used EDA to explore the data; found that negative review consistently outnumber positive reviews. 

## [Project 12: Time Series Analysis for Taxi Company](https://github.com/mnug1996/Project-12-Time-Series-Analysis-for-Taxi-Company)

- Created a linear regression model (RMSE: 40 orders) to forecast the number of orders within the next hour for a taxi company.
- Tested several other models with various hyperparameters tunings, however the linear regression model without tuning performed the best.
- Analyzed monthly trends: the number of orders goes up towards the fall months.
- Analyzed daily trends: the number of orders goes up at the end of the day.

## [Project 11: ML Model to Predict Car Prices for Used Car Sales Company](https://github.com/mnug1996/Project-11-ML-Model-to-Predict-Car-Prices-for-Used-Car-Sales-Company)

- Made a lightGBM model with an RMSE of $1415 when predicting used vehicle prices based on certain features.
- Compared regression models with gradient boosting models and used hyperparameter tuning for each model to optimize performance.
- Used ordinal encoder to convert categorical variable into a useable format for model training.
- Cleaned the data by removing outliers and analyzing the feature distributions before and after removal.
  
## [Project 10: Using Linear Algebra and Machine Learning to Solve Insurance Company Inquiries](https://github.com/mnug1996/Project-10-ML-Model-for-Insurance-Company-Inquiries)

- Created a linear regression model (RMSE: 0.31, R2: 0.66) that works with with obfuscated data to predict the number of insurance benefits a customer has received.
- Used kNN to identify customers that are similar to one another; found that scaled data (f1: 0.98) works better than unscaled (f1: 0.68).
- Found that scaled data affects the result of the kNN algorithm.
- Obfuscated the data to protect customer data.

## [Project 9 ML Model to Predict Amount of Gold Recovered from Gold Ore](https://github.com/mnug1996/Project-9-ML-Model-to-Predict-Amount-of-Gold-Recovered-from-Gold-Ore)

- Created a linear regression model (mean smape: -0.0496) that predicts the amount of gold recovered from gold ore.
- Explored different models with hyperparameter tuning using gridsearchcv.
- Analyzed metal concentrations using seaborn.sns visualization for different purification stages; gold concentration increases linearly.
- Preprocessed missing features, imputed missing values.

## [Project 8: ML Model for Oil Company in Choosing Most Profitable Well Location](https://github.com/mnug1996/Project-8-ML-Model-for-Oil-Company-in-Choosing-Most-Profitable-Well-Location)

- Used bootstapping on 1000 samples per region to analyze profit; region 2 had the lowest risk (1.80%), highest average profit ($4.2 mil), and most accurate distribution.
- Created a linear regression model to predict well profits and analyzed the top 5 wells per region; region 2 had the most accurate top predictions
- Viewed the initial distribution and removed outliers

## [Project-7 Supervised Learning to Predict Bank Clientele Turnover](https://github.com/mnug1996/Project-7-Supervised-Learning-to-Predict-Bank-Clientele-Turnover)

- Created a DecisionTreeClassifier model (f1: 0.59 test) to predict whether a customer will leave the bank soon based on customer behavior data for client retention.
- Tuned parameters for several models to improve f1 score.
- Tried several methods to improve class imbalance; downsampling was the best method (f1: 0.657 vs. f1: 0.612).
- Scaled the data on the training set.

## [Project 6 Machine Learning Model for Phone Plan Recommendations](https://github.com/mnug1996/Project-6-Machine-Learning-Model-for-Phone-Plan-Recommendations/blob/main/README.md)

-
-
-
-


