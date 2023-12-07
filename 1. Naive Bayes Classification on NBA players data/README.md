# Naive Bayes classification on NBA players data
## Project Overview
 Perform feature engineering on basketball player's data and build a Naive Bayes model that predicts whether a player will have an NBA career lasting five years or more. Created a new column called 'efficiency' based on existing features. The model created provides some value in predicting an NBA player's chances of playing for five years or more. It more accurately identified those players who will likely play for more than five years than it did those who likely will not.
 ## Business understanding
Working for a fictious firm that provides insights for management and coaches in the National Basketball Association (NBA), a professional basketball league in North America. The league is interested in retaining players who can last in the high-pressure environment of professional basketball and help the team be successful over time. Analyzing a subset of data that contains information about NBA players and their performance records to determine which features will most effectively predict whether a player's NBA career will last at least five years.
## Data understanding
The data for this activity consists of performance statistics from each player's rookie year. There are 1,341 observations, and each observation in the data represents a different player in the NBA. The target variable is a Boolean value that indicates whether a given player will last in the league for five years. 
### 1. Dataset used in feature engineering code
   This activity uses a dataset called nba-players.csv. It represents 22 columns of United States National Basketball Association (NBA) player performance records per game for one season, including stats like average number of 3-point baskets made per game, and average number of offensive rebounds per game. The dataset contains:1,340 rows – each row is a different NBA player’s stats per game across one season ; and 22 columns
### 2.  Dataset used in Naive Bayes code
   This activity uses a modified version of the NBA dataset used previously. The file is called extracted-nba-players.csv. It represents 11 columns of United States National Basketball Association (NBA) player performance records per game for one season, including stats like average number of 3-point baskets made per game, and average number of offensive rebounds per game. The dataset contains:1,340 rows – each row is a different NBA player’s stats per game across one season; and 11 columns
## Modeling and evaluation
### 1. Form Feature Engineering code
The following attributes about player performance could help predict their NBA career duration and should be included in a presentation to stakeholders: field goals, three-point field goals, free throws, rebounds, assists, steals, blocks, turnovers, total points, and efficiency as points per minute.
### 2. From Naive Bayes Classification
![image](https://github.com/Anisha-kk/Machine-Learning---Supervised-Learning/assets/152973245/d1a6895c-ebd8-4fda-ab75-0e261ab96dfd)

The model created provides some value in predicting an NBA player's chances of playing for five years or more. Notably, the model performed better at predicting true positives than it did at predicting true negatives. In other words, it more accurately identified those players who will likely play for more than five years than it did those who likely will not.
## Conclusion
Naive Bayes model is good for classification. It can also accomodate new information easily. But a lot of preprocessing steps need to be done (feature extraction, scaling etc).


