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

- Created a DecisionTreeClassifier model (accuracy=0.779) to recommend phone plans based on customer behavior.
- After tuning on the validation set, the test set was then used to evaluate the models.
- Used hyperparameter tuning on the DecisionTreeClassifier and RandomForestClassifier models to find the best settings for accurate predictions.
- Split the data correctly into 60:20:20 ratio (train, validation, test).

## [Project 5: Data Collection, SQL, and Statistical Analysis of Taxi Services](https://github.com/mnug1996/Project-5-Data-Collection-SQL-and-Statistical-Analysis-of-Taxi-Services)

- Performed a t-test (p-value<0.05) which means the average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays.
- Analyzed competitor data to understand passenger preferences and the impact of external factors on rides for a new ride-sharing company.
- Found the top 10 neighbors that the new taxi service should focus on to gain new services and attraction.
- Retrieved data from competitor database using SQL.

## [Project 4 Data Analysis of Patterns in Succesful Video Games](https://github.com/mnug1996/Project-4-Data-Analysis-of-Successful-Video-Games)

- Using t-tests, it was found that average user ratings for Xbox One vs PC (p=0.21>0.05) and genres action vs sports (p=2.85e<sup>-32</sup><0.05) were significantly different
- Analyzed the top 5 genres from the regions of the world (EU, JP, NA); found that EU and NA had very similar top performers.
- Found the most lucrative game genres were action and shooters (total sales resulting in 20mil and 15mil respectively).
- Used correlation and scatter matrix to reveal that critic and user score ratings had a weak effect on total sales across all platforms.

## [Project 3 Statistical Data Analysis Comparing Two Telecom Plans](https://github.com/mnug1996/Project-3-Statistical-Data-Analysis-Comparing-Two-Telecom-Plans-)

- Performed SDA and found that the ultimate plan was more profitable ($70 avg mo. revenue) than the surf plan ($55 avg mo. revenue), so the company may adjust their budgeting according to this finding.
- Used a t-test to find that average revenue did not vary between different regions (NY-NJ, p=0.17>0.05).
- Found that data usage was the most profitable aspect of both plans (avg = $23/month)
- Used data manipulation in order to calculate revenue.

## [Project 2: EDA of Influences on Vehicle Price for Car Website](https://github.com/mnug1996/Project-2-EDA-of-Influences-on-Vehicle-Price-for-Car-Website)

- Found that the most contributing factor to vehicle price was age (-0.47 correlation coefficient) showing that it had a major negative effect.
- Visualized vehicle type counts using a bar plot to display the most commonly posted vehicle type ads (trucks, SUV, and sedans all exceeded 10k postings).
- Utilized scatter matrix to uncover many interesting details about the data (Ex. vehicles 20 years or younger are listed for about 100 days, any older than this thay are listed for longer.)
- Cleaned the data by fixing formatting, nan's, strange values, and removing outliers and examining the distribution of the data.

## [Project 1: Data Analysis of Bank Client's Risk of Defaulting](https://github.com/mnug1996/Project-1-Data-Analysis-of-Bank-Client-s-Risk-of-Defaulting)

- Created pivot tables to show the relationship between marital status and debt; customers without children were more often to be found with debt (516) compared to customers with children (412).
- Found that lower income and property loans had the highest relation to untimely loan repayment.
- Made categories using lemmatization to help create concise classification in order to better understand the data.
- Preprocessed the data by handling missing values, data-type formatting, and processing duplicates.





