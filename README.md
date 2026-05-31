# Predicting F1 Pit Stops with Random Forest

In Formula 1, a pit stop is a moment during the race when a driver enters 
the pit lane, usually to change tyres. In this project, I predict the variable 
`PitNextLap` - whether a driver will make a pit stop on the next lap.

The dataset contains race statistics such as the race location, year, driver, 
tyre compound, lap time, tyre life, and race progress. After exploratory data 
analysis and preprocessing (including one-hot encoding of categorical variables), 
I trained a Random Forest classifier.

## Results
| Metric | Score |
|--------|-------|
| AUC (validation) | 0.923 |
| AUC (Kaggle public leaderboard) | 0.921 |

## Technologies
- Python
- pandas, numpy
- scikit-learn
- matplotlib

## Dataset
[F1 Pit Stops - Kaggle Playground Series S6E5](https://www.kaggle.com/competitions/playground-series-s6e5)
