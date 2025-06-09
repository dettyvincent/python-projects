# NBA Basket Ball Data Analysis Project

Welcome to the world of Basketball Data! This is an NBA basketball analysis project.
In this project we are creating visualizations using matplotlib. The [input data set](https://github.com/dettyvincent/python-projects/blob/main/DataAnalysisProject/InputDataset.ipynb) contains various attributes and their values for NBA basketball matches for different seasons in the form of list. 
Based on the given vectors, the below [objects](https://github.com/dettyvincent/python-projects/blob/main/DataAnalysisProject/ObjectsCreated.ipynb) are created
 
## Matrices:
 - Salary
 - Games
 - MinutesPlayed
 - FieldGoals
 - FieldGoalAttempts
 - Points
 -FreeThrows
 -FreeThrowAttempts
 
## Lists:
 - Players
 - Seasons

## Dictionaries:
 - Sdict
 - Pdict

Out of these objects, below [functions](https://github.com/dettyvincent/python-projects/blob/main/DataAnalysisProject/Visualizations.ipynb) are created to plot the visualizations:

- myplot() - Plot a given matrix of the list of players for each seasons.
- Freethrowattemptspergameplot() - Plot Free throw attempts per game for the given list of players. Use star marker and dotted line.
- Freethrowaccuracyplot() - Plot accuracy of free throws for the given list of players. Use square marker and dashed line.
- Playerplayingstyle() - Plot Player playing style. For this, calculate points per field goals excluding free throws. Each free throw worth 1 point

[Here](https://github.com/dettyvincent/python-projects/blob/main/DataAnalysisProject/FinalOutput.ipynb) is the integrated analysis of the data.

## [Insights](https://github.com/dettyvincent/python-projects/blob/main/DataAnalysisProject/Insights.ipynb):

- **myplot(Salary)**

Kobe Bryant is the top paid player through all the seasons. His record was over 30 million dollars in 2013.

- **myplot(Salary / Games)**
- **myplot(Salary / FieldGoals)**

Kobe Bryant and Derrick Rose were getting paid so much per game in 2013. This anomaly appeared because they could not play game in 2013 because of injury.
Players got paid regardless of whether they played or not. To avoid these anomalies from the visualizations, normalize the in-game metrics.

In-Game metrics 
- **myplot(FieldGoals / Games)**

Kobe Bryant had high amount of field goals back in time but it dropped a lot by 2014. Le Bron James is at the top in 2014.

- **myplot(FieldGoals / FieldGoalAttempts)**
- **myplot(FieldGoalAttempts / Games)**
- **myplot(Points / Games)**

This shows the accuracy of the players. Dwight Howard is the most accurate player but the number of attempts per game is low for Dwight Howard. That's why he is scoring less points per game.




