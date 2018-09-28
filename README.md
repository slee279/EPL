# matchpredictor
Soccer Match Predictor

Soccer Match Predictor will predict the result of each matches and the final standing of English Premier League 2018/2019 (EPL) using past five seasons (2013/14 ~ 2017/18). 

# Methods
1. Scores of each matches will be predicted using Poisson distribution. 
    - How many goals will be scored in 90 minutes
    - Using teams' offensive and defensive rating 
2. Save probabilities in the dataframe.
3. Combine the probabilities and other datas and perform classification.
    - EPL teams' overall stats from past database(www.football-data.co.uk, www.transfermarkt.co.uk, www.sportsmole.co.uk, www.soccerstats.com)
    - PES(Pro Evolution Soccer) database(www.pesmaster.com) to predict the result more accurately.

# Assumptions
1. There's no transfers during season (after the new season has begun).
    - Only best 15 players in the team play
2. There's no injury.
3. Players conditions(fatigue level), weathers are the same.


# If time permits
1. Calculate the fatigue level (count days between matches).
