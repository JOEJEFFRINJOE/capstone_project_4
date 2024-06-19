# capstone_project_4

To address the challenges in the copper industry related to sales and pricing data, we will develop a comprehensive machine learning solution that includes both regression and classification models. This solution will effectively manage skewness, noisy data, and lead classification, ultimately improving the accuracy of pricing decisions and lead evaluations. The following steps outline the detailed approach:

Exploratory Data Analysis (EDA):

Investigate the dataset to identify skewness and outliers.
Use visual and statistical methods to understand data distribution and variability.


Data Transformation and Preprocessing:

Clean the dataset by removing or imputing missing values.
Normalize and scale the data to ensure consistent feature ranges.
Apply outlier detection techniques to mitigate the impact of anomalous data points.


ML Regression Model for Predicting Selling Price:

Develop a regression model to predict the continuous variable 'Selling_Price'.
Utilize algorithms robust to skewed and noisy data, such as Ridge Regression, Lasso Regression, or Gradient Boosting Regressor.
Implement feature engineering to enhance model performance.
ML Classification Model for Predicting Lead Status:



Build a classification model to predict the lead status (WON or LOST).
Use the STATUS variable, considering WON as Success and LOST as Failure.
Remove data points with STATUS values other than WON or LOST.
Evaluate and choose appropriate classification algorithms like Logistic Regression, Decision Trees, or Random Forest.


Deployment Using Streamlit:

Create an interactive Streamlit web application.
Develop user interfaces to input individual column values.
Implement functionality to predict and display the Selling_Price or Status (WON/LOST) based on the input values.
Ensure the application is user-friendly and provides real-time predictions.
