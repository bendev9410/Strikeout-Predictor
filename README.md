
⚾ MLB Strikeout Predictor
A machine learning project that predicts how many strikeouts a pitcher will record in a game.
## What it does
Uses Statcast data + team batting stats from pybaseball.
Builds rolling pitcher form (last 5–10 starts) and opponent K% trends.
Trains a Random Forest to predict per-game strikeouts.
Predicts Ks for upcoming games using probable pitchers.
## Results (Work in Progress)
Baseline (league avg): ~1.5 MAE
Random Forest: ~0.9 MAE, R² ~0.6

## Why I built it
I love baseball and wanted to apply ML + data engineering to a real sports problem. I had alot of fun on this project and it helped me hone my skills in data collection, feature engineering, modeling, and producing usable predictions.

## Demo
Try it for yourself! simply run the notbook to find starting pitcher striekout predicions for the next 3 days
You can try it live on Kaggle 👉 **[here](https://www.kaggle.com/code/bennettmoore94/strikeout-predictor-3)**.

