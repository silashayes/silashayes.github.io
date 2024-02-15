# [Football Expected Points Simulation & Ranking System](https://github.com/silashayes/football-expected-points)

## Expected Points Simulation
- Calculates the expected points of a given situation (down, yards to go, yardage) by simulating football plays
- Sampling of plays comes from a mixture model that models the number of yards gained on a play in a given situation
- Model is parameterized so can be adjusted to perform analysis
- In this case, difference in expected value when running/passing rate increased by a small percentage was analyzed
- Additionally, the value (i.e. difference in expected points) of a good punter over an average punter analyzed
<p align="center">
  <img src="./images/EP%20Pass%20Visualization.png" alt="EP Viz" width="100%"/>
</p>

## Ranking System
- Ranking system uses Markov chain properties (similar to PageRank) to rank teams at the end of the year based on their performance
<p align="center">
  <img src="./images/Rankings%20Table.png" alt="Markov Rank Viz" width="40%"/>
</p>

# [A Bayesian Approach to Predicting Weather](https://github.com/silashayes/bml-weather)

## 3 Models for Predicting Weather
- Models the probability of whether or not it will rain tomorrow given variables from today
- Compares pooled, unpooled, and hierarchical approaches to the problem via prior and posterior predictive distributions and Bayesian p-values
<p align="center">
  <img src="./images/Posterior%20Predictives.svg" alt="Posterior Predictives" width="80%"/>
</p>
- Performs counterfactual analysis on certain variables to analyze their impact on whether it will rain tomorrow
<p align="center">
  <img src="./images/Rainfall%20Counterfactual.svg" alt="" width="80%"/>
</p>
- Examines effect graphs of the 3 models to assess reliability of inferential conclusions
<p align="center">
  <img src="./images/Effect%20Graphs.svg" alt="" width="80%"/>
</p>
