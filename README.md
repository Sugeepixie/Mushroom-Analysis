# Mushroom-Analysis

## Selected topic:
- Classifying safe versus poisonous mushrooms.

## Reason for selecting topic:
- All five of us are massive mushroom enthusiasts and need to ensure that we can survive the upcoming climate apocalypse in the wild.

## Description of the data source:
- CSV file with 8124 instances of mushrooms and their attributes. This data set includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family.  
- Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended.
- The data comes from The Audobon Society Field Guide to North American Mushrooms (1981) and was contributed to the UCI Machine Learning Repository in 1987.

## Description of the communication protocols:
- Team members will communicate online via methods such as Slack and Zoom, both in and outside of class time. This will achieve our goal of analyzing mushrooms.

## Outline of the project:
- We will identify differences in edible versus poisonous mushrooms.
- This can be achieved by identifying various aspects of mushrooms based on our dataset to determine whether they are edible or poisonous.
- By classifying our data by different features and creating a target, we can test to confirm safe and poisonous mushrooms and their qualities.

## Questions:
1) Which features are most indicative of a poisonous mushroom?
2) Which features of mushrooms are most palatable?
3) Which habitat contains the highest percentage of edible mushrooms?
4) What populations contain the most edible and most poisonous mushrooms?

## Machine Learning Model:
- We want to better understand the classification (edible vs. poisonous) mushrooms belong to based on our dataset. This can be achieved through using the Random Forest Classifier, to precisely classify our data. 
- The Random Forest Classifier is an ensemble learning model consisting of several decision tree algorithms trained on random subsets of our data. 
- By combining multiple (relatively uncorrelated) decision trees, the Random Forest Classifier protects against overfitting and improves overall accuracy. The model also allows us to rank the importance of our input variables, and is able to accomodate larger datasets. 

- The following steps will be used for our model:
 * Load clean Data
 * Create Features
 * Create Target
 * Split, Train, Test with train_test_split()
 * Instantiate the model with RandomForestClassifier()
 * Fit the model with model.fit()
 * Make Predictions with model.predict()
 * Calculate Accuracy score with balanced_accuracy_score()
 * Print classifiaction report with classification_report_imbalanced()

## Google slides link:
https://docs.google.com/presentation/d/1TcVUXv8PpJf7bvGHLgkctSf4tc1Di38AYmpPCqDlXzk/edit#slide=id.p

## Resources:
https://www.kaggle.com/datasets/uciml/mushroom-classification

## Code comments to add:
- 
