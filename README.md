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
  
## [Project 8: ML Model for Oil Company in Choosing Most Profitable Well Location](https://github.com/mnug1996/Project-8-ML-Model-for-Oil-Company-in-Choosing-Most-Profitable-Well-Location)

- Used bootstapping on 1000 samples per region to analyze profit; region 2 had the lowest risk (1.80%), highest average profit ($4.2 mil), and most accurate distribution.
- Created a linear regression model to predict well profits and analyzed the top 5 wells per region; region 2 had the most accurate top predictions
- Viewed the initial distribution and removed outliers
<!--
**mnug1996/mnug1996** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
