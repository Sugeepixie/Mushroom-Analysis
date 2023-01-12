# Mushroom-Analysis

## Selected topic:
- Classifying safe versus poisonous mushrooms.

## Reason for selecting topic:
- All five of us are massive mushroom enthusiasts and need to ensure that we can survive the upcoming climate apocalypse in the wild.

## Description of the data source:
- CSV file with 8124 instances of mushrooms and their attributes. This data set includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family.  
- Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended.
- The data comes from The Audobon Society Field Guide to North American Mushrooms (1981) and was contributed to the UCI Machine Learning Repository in 1987.

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

## Tableau link:
https://public.tableau.com/app/profile/bianca.calin1055/viz/MushroomAnalysisv_1/Ediblev_Poisonous

## Resources:
https://www.kaggle.com/datasets/uciml/mushroom-classification

## Code comments to add:
- Import dependencies
- Initialize SQLite and create database
- Read in CSV of mushroom data
- Create features and target DataFrames
- Pull list of column headers from features DataFrame and create f string syntax to create features table in SQLite
- Print "create_features" to ensure that correct column headers have been pulled
- Create features table in SQLite database  (cur.execute)
- Isolate features data from DataFrame
- Insert ensuing values into features table in SQLite database
- Declare variables that will execute SQLite query to select all data from features table in SQLite database
- Print features table to confirm
- Create syntax to create target table in SQLite
- Create target table in SQLite database  (cur.execute)
- Isolate target data from DataFrame
- Insert ensuing values into target table in SQLite database
- Read target table from SQLite as pandas DataFrame to ensure it loaded appropriately
- Declare variables that will execute SQLite query to select all data from target table in SQLite database
- Print target table to confirm
- Create variable to join target and features table from SQLite on ID
- Execute SQLite join created as variable in previous step
- Print results of SQLite join to confirm targets and features line up correctly
