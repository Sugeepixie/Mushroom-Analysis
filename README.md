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

## Questions:
1) Which features are most indicative of a poisonous mushroom?
2) Which features of mushrooms are most palatable?
3) Which habitat contains the highest percentage of edible mushrooms?

## Machine Learning Model:
 * Load Clean Data
 * Create Features
 * Create Target
 * Split, Train, Test with train_test_split()
 * Instantiate the Model with RandomForestClassifier()
 * Fit the Model with model.fit()
 * Make Predictions with model.predict()
 * Calculate Accuracy score with alanced_accuracy_score()
 * Print classifiaction report with classification_report_imbalanced()

## Resources:
https://www.kaggle.com/datasets/uciml/mushroom-classification
