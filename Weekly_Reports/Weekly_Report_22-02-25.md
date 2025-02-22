# Weekly Report (22-02-25)

## Overview
This week our team focused on exploring the datasets provided and literature survey to gain insight on potential techniques to use for the project.

### Feature details

| **Abbreviation** | **Statistic**                     | **Description**                                                                                   |
|------------------|-----------------------------------|---------------------------------------------------------------------------------------------------|
| **PTS**          | Points Scored                     | Total points scored by the player in a game.                                                      |
| **MIN**          | Minutes Played                    | Total time the player was on the court.                                                           |
| **FGM**          | Field Goals Made                  | Successful two- or three-point shots.                                                             |
| **FGA**          | Field Goals Attempted             | Total shots taken.                                                                                |
| **PM**           | 3-Point Field Goals Made          | Successful three-point shots.                                                                     |
| **PA**           | 3-Point Field Goals Attempted     | Total three-point shots taken.                                                                    |
| **FTM**          | Free Throws Made                  | Successful free throws.                                                                           |
| **FTA**          | Free Throws Attempted             | Total free throw shots taken.                                                                     |
| **OREB**         | Offensive Rebounds                | Times player regained possession after a missed shot.                                             |
| **DREB**         | Defensive Rebounds                | Times player secured the ball after opponent’s missed shot.                                       |
| **REB**          | Total Rebounds                    | Sum of offensive and defensive rebounds.                                                          |
| **AST**          | Assists                           | Passes leading directly to a made basket.                                                         |
| **BLK**          | Blocks                            | Shots blocked by the player.                                                                      |
| **STL**          | Steals                            | Times the player took the ball from an opponent.                                                  |
| **TO**           | Turnovers                         | Times the player lost possession of the ball.                                                     |
| **PF**           | Personal Fouls                    | Number of fouls committed.                                                                        |
| **Team Score**   | Team's Total Points               | Total points scored by the team in the match.                                                     |
| **Win**          | Win Indicator                     | 1 if the team won, 0 if the team lost.                                                            |
 
Game Score	Performance metric based on Hollinger’s Formula (PTS, AST, STL, etc.).

### Literature Survey
#### Sharma, S. U., Divakaran, S., Kaya, T., & Raval, M. (2022, July). A hybrid approach for interpretable game performance prediction in basketball. In 2022 International Joint Conference on Neural Networks (IJCNN) (pp. 01-08). IEEE.

Sharma et al. propose a Decision Tree-based approach to predict and interpret game performance in basketball. The study focused on a Women's Division-I basketball team, analysing data from 16 athletes over 25 weeks, encompassing 2,800 records with 37 attributes. These attributes included sleep and recovery metrics from wearable devices, training statistics, and cognitive assessments. The researchers developed a hybrid model combining factor analysis with decision tree-based methods, including classification/regression trees and random forests. This approach first reduced the dataset into seven latent factors through factor analysis, then utilised these factors to construct decision trees for game score prediction.
