# **Siddarth Puliyanda Portfolio**
Welcome to my GitHub portfolio! My name is Siddarth and I'm a Big Data professional with 5 years of experience at Northrop Grumman, an M.S. in Analytics from Georgia Tech, and B.S. in Statistics from UC Riverside. I’m passionate about uncovering hidden patterns in data and transforming raw numbers into actionable insights and thrive on turning complex data into clear, strategic narratives that are clear for both technical and non-technical parties to understand.

I’m highly proficient at Python, SQL, and Tableau, but also have hands-on experience in R, Power BI, Spark, and modern cloud platforms like AWS/GCP. The data landscape is always evolving, and I stay ahead by actively exploring emerging tools and techniques—whether it’s diving into AI advancements, optimizing data pipelines, or experimenting with new visualization libraries. My expertise is grounded in experience, but my curiosity ensures I never stop learning.

My portfolio highlights a few personal projects, showcasing my end-to-end skills in data collection, cleaning, analysis, and visualization—as well as my ability to build models and communicate findings for data-driven decision-making. Feel free to explore further below!

## [NBA MVP Machine Learning 🏀](https://github.com/siddp95/NBA/tree/main/NBA%20MVP%20ML)
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

<img src="/images/Screen%20Shot%202023-06-14%20at%206.07.57%20PM.png" width="60%" height="60%">

## [2024 NFL Touchdown Regression 🏈](https://github.com/siddp95/Fantasy-Football-2024/blob/main/2024%20TD%20Regression.ipynb)
* Collected, cleaned, and analyzed 2023 NFL stats to determine the whether a player scored more or less touchdowns than expected during the season
* Recalculated the amount of fantasy points a player would have scored in 2023 based on the predicted amount of touchdowns
* Created residual plots that displayed the names of players who had the most and least amount of difference between predicted vs. actual 
* Hypothesized how this information can be used to predict the amount of touchdowns scored by a player in the 2024 season
* Python libraries: pandas, numpy, seaborn, matplotlib

<img src="/images/Screen%20Shot%202023-06-14%20at%206.09.12%20PM.png" width="67%" height="67%">

## [Stock Analysis Dashboard 📈](https://st-stock-analysis.streamlit.app/)
* Developed a Streamlit-powered analytics tool that consolidates real-time market data, technical indicators, and fundamental metrics into a single dashboard—reducing hours of manual research into a 10-minute nightly review for informed trading decisions
* Engineered a Python data pipeline (pandas/yfinance) that automates timezone normalization, missing data handling, and batch updates—transforming raw API data into actionable insights for both short-term trades and long-term portfolio health checks
* Built an LSTM neural network (TensorFlow/Keras) to predict stock prices with a $2.34 mean absolute error, paired with interactive visualizations (Plotly) to formulate trade setups using moving averages and valuation metrics
* Python libraries: Streamlit, tensorflow, yfinance, pandas
<img src="/images/stock_dashboard_pic.png" width="70%" height="70%">

## [Blackjack Simulation 🃏](https://github.com/siddp95/Projects/tree/main/Blackjack%20Simulation)
* Built a Monte Carlo simulation to test the profitability of different Blackjack strategies by simulating 10,000 hands for every variation and analyzing the outputs
* Concluded the number of decks at a Blackjack table has no significant effect on profit and that 16 is the most optimal stay value, although all strategies lead to negative profit when simulated 10,000 times
* Debunked the effectiveness of the Martingale betting strategy over a long run, since Vegas imposes strict upper and lower table limits
* Python libraries: scipy, pandas, matplotlib, numpy

<img src="/images/Screen%20Shot%202023-06-14%20at%206.10.34%20PM.png" width="62%" height="62%">
