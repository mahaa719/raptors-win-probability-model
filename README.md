# raptors-win-probability-model
#PROJECT OVERVIEW
This project analyzes multi-season game-level data for the Toronto Raptors to identify key performance metrics that drive win probability.
Using logistic regression modeling in R, I examined how shooting efficiency, rebounding, and home-court advantage influence game outcomes.
The goal was to translate basketball performance data into clear, strategic insights that could inform competitive and operational decision-making.
DATASET:
NBA game-level data (1,700+ observations)
Includes:
Points scored
Field goal percentage (FG%)
3-point percentage
Rebounds
Home vs. away indicator
Game outcomes
The dataset was cleaned and filtered to include only Raptors games.
TOOLS AND METHODS:
R
tidyverse (data cleaning & feature engineering)
ggplot2 (visualization)
glm() – Logistic Regression (win probability modeling)
Feature Engineering
Created structured variables to isolate Raptors performance:
team_points
opp_points
home (1 = home game)
win (1 = win, 0 = loss)
team_fg_pct
team_reb
KEY FINDINGS:
The Raptors won approximately 51.5% of games across the observed seasons.
Field goal percentage was the strongest predictor of winning (statistically significant at p < 0.001).
Rebounding significantly increased win probability.
Home-court advantage positively impacted outcomes.
Logistic regression reduced deviance from 2449 → 1799, indicating strong explanatory power.
Interpretation (In Simple Terms)
When the Raptors shoot more efficiently, they are much more likely to win.
Controlling rebounds (possession advantage) increases the chances of winning.
Playing at home provides a measurable competitive edge.
VISUALIZATION:
The model generates predicted win probabilities for each game and visualizes how scoring output relates to win likelihood.
Higher team scoring and shooting efficiency correspond to higher predicted win probability.
Business & Strategy Implications:
This analysis demonstrates how performance metrics translate into competitive outcomes.
From a strategic perspective:
Shooting efficiency is a critical driver of success → valuable for player development and roster construction analysis.
Rebounding impacts possession control → aligns with performance analytics for lineup optimization.
Home advantage suggests venue engagement and environmental impact may influence performance outcomes.
This project reflects how statistical modeling can inform sports strategy decisions
