# matchpredictor
Soccer Match Predictor

Soccer Match Predictor will predict the result of each matches and the final standing of English Premier League 2018/2019 (EPL) using past five seasons (2013/14 ~ 2017/18). 

# Methods
Scores of each matches will be predicted using Poisson distribution. 
  - How many goals will be scored in 90 minutes
  - Using teams' offensive rating and defensive rating 
  
The probability of Win/Draw/Lose calculated using Poisson, will be calculated with teams' overall stats from past database(www.football-data.co.uk, www.transfermarkt.co.uk, www.sportsmole.co.uk, www.soccerstats.com) and PES(Pro Evolution Soccer) database(www.pesmaster.com) to predict the result more accurately.

# Assumptions
1. There's no transfers during season (after the new season has begun).
  (Only best 15 players in the team play)
2. There's no injury.
3. Weathers are the same.


# If time permits
1. Calculate the fatigue level (count days between matches).
