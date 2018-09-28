# matchpredictor
Soccer Match Predictor

Soccer Match Predictor will predict the result of each matches and the final standing of English Premier League 2018/2019 (EPL) using past five seasons (2013/14 ~ 2017/18). 

# Methods
1. Scores of each matches will be predicted using Poisson distribution. (Match Based Rating)
    - How many goals will be scored in 90 minutes
    - Using teams' offensive and defensive rating 
2. Save probabilities in the dataframe.
3. Combine the probabilities and other datas (Roster Based Rating) and perform classification.
    - EPL teams' overall stats from past database(www.football-data.co.uk, www.transfermarkt.co.uk, www.sportsmole.co.uk, www.soccerstats.com)
    - PES(Pro Evolution Soccer) database(www.pesmaster.com) to predict the result more accurately.


# Assumptions
1. There's no transfers during season (after the new season has begun).
    - Only best 15 players in the team play
2. There's no injury.
3. Players conditions(fatigue level), weathers are the same.


# If time permits
1. Calculate the fatigue level (count days between matches).
2. Once I am able to forecast individual matches, turn those match-by-match probabilities into a season forecast using Monte Carlo simulations. Simulate the season thousands of times, and the probability that a team wins the tournament represents the share of simulations in which it wins it.


# Source
https://fivethirtyeight.com/features/how-our-2018-world-cup-predictions-work/   
https://dashee87.github.io/football/python/predicting-football-results-with-statistical-modelling/  
www.football-data.co.uk   
www.transfermarkt.co.uk   
www.sportsmole.co.uk   
www.soccerstats.com   
www.pesmaster.com  
