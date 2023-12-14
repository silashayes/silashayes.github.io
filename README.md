# [Football Expected Points Simulation & Ranking System](https://github.com/silashayes/football-expected-points)

## Expected Points Simulation
- Calculates the expected points of a given situation (down, yards to go, yardage) by simulating football plays
- Sampling of plays comes from a mixture model that models the number of yards gained on a play in a given situation
- Model is parameterized so can be adjusted to perform analysis
- In this case, difference in expected value when running/passing rate increased by a small percentage was analyzed
- Additionally, the value (i.e. difference in expected points) of a good punter over an average punter analyzed
<p align="center">
  <img src="./images/EP%20Pass%20Visualization.png" alt="EP Viz" style="width:"500px;"/>
</p>

## Ranking System
- Ranking system uses Markov chain properties (similar to PageRank) to rank teams at the end of the year based on their performance
<p align="center">
  <img src="./images/Rankings%20Table.png" alt="Markov Rank Viz" style="width:"500px;"/>
</p>
