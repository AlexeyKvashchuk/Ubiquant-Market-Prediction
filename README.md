# Ubiquant-Market-Prediction
Ubiquant Market Prediction Kaggle Competition

### Data Description

https://www.kaggle.com/competitions/ubiquant-market-prediction/overview


This dataset contains features derived from real historic data from thousands of investments. Your challenge is to predict the value of an obfuscated metric relevant for making trading decisions.

This is a code competition that relies on a time-series API to ensure models do not peek forward in time. To use the API, follow the instructions on the Evaluation page. When you submit your notebook, it will be rerun on an unseen test. This is also a forecasting competition, where the final private leaderboard will be determined using data gathered after the training period closes.

Files: train.csv

***row_id*** - A unique identifier for the row.

***time_id*** - The ID code for the time the data was gathered. The time IDs are in order, but the real time between the time IDs is not constant and will likely be shorter for the final private test set than in the training set.

***investment_id*** - The ID code for an investment. Not all investment have data in all time IDs.

***\[f_0:f_299\]*** - Anonymized features generated from market data.

***target*** - The target.

### Evaluation

This is a forecasting competition with an active training phase and a second period where models will be run against real market data.


Submissions are evaluated on the mean of the Pearson correlation coefficient for each time ID.

One must submit to this competition using the provided python time-series API, which ensures that models do not peek forward in time.

