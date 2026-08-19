# Chasing Financial Freedom, One Model at a Time

Self-initiated collaborative thesis (2 members) testing whether a model can actually predict if a stock will rise or fall. Built a full pipeline in Python comparing a Naive Persistence baseline against Random Forest models (Baseline & Enhanced) using 14 - 17 engineered features (SMA20, MACD, RSI), validated with 5-fold TimeSeriesSplit and a Wilcoxon Signed-Rank Test.

Result: the simple baseline (RMSE ≈80) beat both RF models (RMSE ≈160 - 170) even with fancier features. RF struggled most when the stock hit an all-time high in 2024, unable to predict beyond prices it had seen before.

Learned: complexity ≠ accuracy trust honest results over hoped-for ones, and validate claims statistically, not by eye.

Tech: Python · scikit-learn · pandas
