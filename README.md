# Bundesliga 2025-2026 Predictor

- Since the 2025-2026 Bundesliga season is coming up, I decided to make predictors for the final standings/fixtures using classification and regression methods.

- With classification, I predicted the standings using just the goals scored and conceded by each team as features for the classifer, generating season summaries for the last 5 seasons and using those results as inputs for predictions.
- With regression, I included expected goals, possession, shots and shots on target while also calculating team strength coefficients using their average goals scored and conceded, and home advantage. Poisson values were generated for randomness, so I simulated the season 1000 times and generated a grid of how many times each team finished in each position.

- At the end of the season (16th May, 2026), I will be comparing the actual final table to the ones predicted here to see how accurate my predictions were.
