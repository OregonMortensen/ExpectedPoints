# ExpectedPoints
Monte Carlo simulation for calculating expected points in football

The translation from Expected Goals (xG) to Expected Points (xP) involves a method where probabilities for the three potential outcomes in a soccer match are calculated based on the xG from the match. This process of calculating the probabilities relies on Monte Carlo simulation, a statistical technique enabling us to model the inherent uncertainties and randomness in the beautiful game.
Within the xP framework, probabilities for each team winning, drawing, or losing are meticulously determined through multiple simulations. To assign values, these probabilities are then multiplied by 3 and 1 points, representing the rewards for a win and a draw, respectively. The resulting figures are tallied for each team, culminating in an xP score.
The essence of this is formulated in the following formula, where the last term always equals to zero and therefore are removed.
xP = Win Prob. × 3p + Draw Prob. × 1p + Loss Prob. × 0p
The strength of this approach lies in its responsiveness to the quality of performance. Teams that consistently exhibit high positive xG difference in their matches are consequently rewarded with elevated xP scores, reflecting their propensity for creating goal-scoring opportunities, and defending well. Conversely, teams with less positive xG difference find themselves with more modest xP, aligning with their challenges in generating significant goal-scoring chances.
In essence, the xP system provides a nuanced and dynamic perspective on team performance, allowing us to move beyond raw statistics and delve into the intricate dance of possibilities that unfold on the soccer field.
