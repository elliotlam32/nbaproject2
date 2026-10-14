# nbaproject2
2 options
1) finding similar players(twins)
2) Use per possession parameters. scale them. use cosine similarity to asses the similarity between players.
3) similar players, but slightly different "diet"
4) box score, and advanced stats. also get shot location from nba api. move into one table. use z score standardization to turn every players statline into a vector. then use vector project to see how the different playstyles align with one another
5) then use wasserstein distance to assess similarity. use filter usage and efficiency as usual. potentially add weights for certain features - unsure how to do this
