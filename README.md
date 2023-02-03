## Project Overview
For this project, I attempted to predict the number of points scored by each team in tonight's NBA games. Currently, the model uses the following variables:

+Average points per game (PPG)
+Average PPG for the last three games
+Opponents adjusted defensive rating
+Days of rest
+Home / Away

Additional explanatory variables potentially include net rating, and opponents PPG allowed in the last three games

## Evaluation
The mean absolute error is in the ballpark of 8-12 points for each team on a given night. At a glance, that sounds pretty good. The average number of points scored by each team in an NBA game is around 113-114, so being within 10% is a good starting point. I plan to evaluate if my model is better than simply predicting that team's season average points-per-game
