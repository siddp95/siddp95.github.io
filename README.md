# **Siddarth Puliyanda Portfolio**
Welcome to my personal Github portfolio! As a Data Science enthusiast with a focus on sports and online gaming, I have developed a range of programming projects that demonstrate my skills, knowledge, and passion in this field.

This portfolio contains three of my programming project highlights, showcasing my ability to collect, clean, analyze, and visualize data to extract insights and build models that solve real-world problems.

## [Project 1: NBA MVP Machine Learning](https://github.com/siddp95/NBA/tree/main/NBA%20MVP%20ML)
* Created a 3 part machine learning model that predicts the MVP winner and top 5 vote receivers for a given season, based on historical NBA player stats and team records
* [Part 1: MVP Scraping](https://github.com/siddp95/NBA/blob/main/NBA%20MVP%20ML/MVP%20Scraping.ipynb)
  * Webscraped NBA player and team data from Basketball Reference, dating back to the 1995 season (year I was born)
* [Part 2: MVP Cleaning](https://github.com/siddp95/NBA/blob/main/NBA%20MVP%20ML/MVP%20Cleaning.ipynb)
  * Cleaned the data scraped from the previous part by filling in missing values, mapping team name classifications, and deleting extraneous columns
* [Part 3: MVP Machine Learning](https://github.com/siddp95/NBA/blob/main/NBA%20MVP%20ML/MVP%20Machine%20Learning.ipynb)
  * Constructed a machine learning model using Ridge Regression that calculates the percentage of MVP votes a player should expect to receive, and then utilized Random Forest Regression to improve upon the original model by analyzing predictors that are not commonly tracked NBA statistics (stats ratios, team played for, and position)
  * Successfully predicted 4 out of 5 top MVP vote finishers for the 2023 season, and backtested how the model would perform over all the data since the 1995 season
  * Theorized how outside factors that are not included in the model can influence MVP voting results, such as recency bias, strength of team, and voter fatigue
* Python libraries: BeautifulSoup, selenium, sklearn, pandas

![](/images/Screen%20Shot%202023-06-14%20at%206.07.57%20PM.png)

## [Project 2: 2023 NFL Touchdown Regression](https://github.com/siddp95/Fantasy-Football-2023/blob/main/2023%20TD%20Regression.ipynb)
* Collected, cleaned, and analyzed 2022 NFL stats to determine the whether a player scored more or less touchdowns than expected during the season
* Recalculated the amount of fantasy points a player would have scored in 2022 based on the predicted amount of touchdowns
* Created residual plots that displayed the names of players who had the most and least amount of difference between predicted vs. actual 
* Hypothesized how this information can be used to predict the amount of touchdowns scored by a player in the 2023 season
* Python libraries: pandas, numpy, seaborn, matplotlib

![](images/Screen%20Shot%202023-06-14%20at%206.09.12%20PM.png)

## [Project 3: Blackjack Simulation](https://github.com/siddp95/Projects/tree/main/Blackjack%20Simulation)
* Built a Monte Carlo simulation to test the profitability of different Blackjack strategies by simulating 10,000 hands for every variation and analyzing the outputs
* Concluded the number of decks at a Blackjack table has no significant effect on profit and that 16 is the most optimal stay value, although all strategies lead to negative profit when simulated 10,000 times
* Debunked the effectiveness of the Martingale betting strategy over a long run, since Vegas imposes strict upper and lower table limits
* Python libraries: scipy, pandas, matplotlib, numpy

![](images/Screen%20Shot%202023-06-14%20at%206.10.34%20PM.png)
