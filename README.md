
# YouTube Adview Predicition

Youtube advertisers pay content creators based on adviews and clicks for the goods and services being marketed. They want to estimate the adview based on other metrics like comments, likes etc. The problem statement is therefore to train various regression models and choose the best one to predict the number of adviews.




## Data
The dataset used for this project includes various features of YouTube videos such as:

1. Video ID
2. Video Title
3. Published Date
4. Channel Title
5. Video Category
6. Duration
7. Number of Likes
8. Number of Dislikes
9. Number of Comments
10. Number of Shares
The data is stored in a CSV file named youtube_data.csv. You can place this file in the data/ directory.



## Features

### Data Preprocessing
 Data Cleaning: Handling missing values and outliers.
Feature Engineering: Creating new features and transforming existing ones.
Normalization: Scaling numerical features to a standard range.
### Exploratory Data Analysis (EDA)
Visualization of the distribution of features.
Correlation analysis between features and the target variable (ad views).
Identifying patterns and insights from the data.
### Model Development
Linear Regression
Decision Trees
Random Forests
Gradient Boosting Machines
Neural Networks
### Model Evaluation
Splitting the data into training and testing sets.
Evaluating models using metrics like Mean Squared Error (MSE) and R-squared.
Hyperparameter tuning using Grid Search and Cross-Validation.



