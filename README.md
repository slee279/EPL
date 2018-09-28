# matchpredictor
Soccer Match Predictor

Soccer Match Predictor will predict the result of each matches and the final standing of English Premier League 2018/2019 (EPL) using past five seasons (2013/14 ~ 2017/18). 

# Methods
1. Scores of each matches will be predicted using Poisson distribution. (Match Based Rating)
    - How many goals will be scored in 90 minutes
    - Using teams' offensive and defensive rating 
2. Save probabilities.
3. Combine the probabilities (Match Based Rating) and other datas (Roster Based Rating).
    - EPL teams' overall stats from past database(www.football-data.co.uk, www.transfermarkt.co.uk, www.sportsmole.co.uk, www.soccerstats.com)
    - PES(Pro Evolution Soccer) database(www.pesmaster.com) to predict the result more accurately.
4. After combine MBR and RBR (Off. rating, Def. rating, Game data, possion WR, possion DR, etc.), train/test split seasons date in order to fit models.(Regression models to predict total points of all teams in EPL 18/19).

# Assumptions
1. Goal scoring in soccer follows a Poisson process.
2. There's no transfers during season (after the new season has begun).
    - Only best 15 players in the team play
3. There's no injury.
4. Players conditions(fatigue level), weathers are the same.


# If time permits
1. Calculate the fatigue level (count days between matches).
2. Once I am able to forecast individual matches, turn those match-by-match probabilities into a season forecast using Monte Carlo simulations. Simulate the season thousands of times, and the probability that a team wins the tournament represents the share of simulations in which it wins it.


# Resource
https://fivethirtyeight.com/features/how-our-2018-world-cup-predictions-work/   
https://dashee87.github.io/football/python/predicting-football-results-with-statistical-modelling/  
www.football-data.co.uk   
www.transfermarkt.co.uk   
www.sportsmole.co.uk   
www.soccerstats.com   
www.pesmaster.com  
