# Offensive-Rebounding-ShotQuality

# Forecasting Offensive Rebounds in Basketball Using Location Data

## Dataset Overview

The datasets for this project include:

1. Play-by-Play Data (PBP): This dataset includes team names and, in the training set, specifies if a rebound is taken offensively or defensively.

2. Location Data (Locs): This is the essence of the competition. This dataset dilineates the coordinates of defenders, offensive players, and the shooter for each specific play.

## Objective

Given the data, the task is to predict the likelihood of an offensive rebound after a missed shot. The prediction will be based on the positions of the players at the time of the shot.

## My Approach

In my exploration of this problem, here is my thorough approach:

1. <u>Data preprocessing & EDA </u>:           Cleaned the data in dataframes. Explored visualizations of data.

2. <u>Distance Features</u>:              Calculated distances between key players and positions to observe disadvantages and advantages in obtaining an offensive board.

3. <u>Complex Feature Engineering</u>   Developed features using the results of EDA and basketball intuition

4. <u>Tuning and Model Valuation</u>:        Tuning hyperparameters using crossvalidation. Evaluating multiple models.

5. <u>Model Exploration</u>:           Along with the traditional algorithms, I experimented with Neural Networks and model ensembles. 
