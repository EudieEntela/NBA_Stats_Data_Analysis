# NBA Teams and Players Statistics From Year 1994 to 2024 Data Analysis

## Summary
In this project, I will try and answer a couple question and explain relation between data found:

- The lowest average team age vs. the highest average team age for each year
- Percentage of players in the NBA from ages 20 to 30
- Top 10 teams with the most amount of unique players in the last 30 years
- Total number of points per team in the last 5 years
- The relationship between age and points per game based on player position in the last 20 years
- Visualizing the relationship between "field goal percentage (FG%) and "field goal attempts (FGA) for players in the 10th and 11th season.
- What is the average points and assists per season for all players ages 19 to 30 years old who have played in more than 50 games in a season?

## Data Description

Using two datasets, I've merged them together based on player names. I then shorten the dataset from 1947 to 1994 extending to 2024 in order to find 
relevant statistics on modern basketball played today.
I also removed any rows that aren't NBA, found all the null values and replaced them with the value 0. Most null values were averages,
and do make sense in this case.
All data has been found at: https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats/

## Summary and Data Findings

In this project, wiht the help of mostly Matplotlib and Seaborn, I was able to make 7 graphs using barplot, piechart and scatterplot and more.
Depending on the dataset needed, I grouped data together based on age, position, team, year, and more in order illustrate results that can be later studied
and used to come to conclusions. Here are some of my findings from the created graphs:

- Basketball teams create rosters that aren't too young, but also aren't nearing the end of their careers. With some rosters having a low average age of around 23 y/o and high average of around 30 y/o, they look to have a bit of experience already playing in the league but not enough were they can't keep up with the younger ones.
  
- To confirm the statement above, from the pie chart that I created, when grouping players based on ages, there seems to be more player at the age range of 23 to 27 y/o
  
- The teams to have the most amount of players to play for them in the last 30 years are the teams that have not necessarily have the best results throughout those 30 years. These number of players seem to be different roster they have tried play with but haven't had much success which in turn creates more roster changes.
  
- Although scoring more points than another team in game will get you a win, scoring a great amount of points throughout the season doesn't necessarily mean a successfull season.Looking at the bar totals, teams that have won championships have not longer bars or more points than the rest of the teams
  
- The point guard and shooting guard positions differ from poward forward and centers when it comes to free throw percentage. They have a higher number of players at a higher percentage, as opposed to PFs and Cs that have a more dispersed range.
  
- The number of points scored and assists made seem to gradually increase as you get older and gain more experience. But after the age of 27, that total starts to slowly decline

This was a very fun project to do! Having a wide range of data can answer a lot of lingering questions that you have. And having the ability to manipulate data to your linking is definitely a great skill to have.

