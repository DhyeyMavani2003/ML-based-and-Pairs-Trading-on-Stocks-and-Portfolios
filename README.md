# ML based and Pairs Trading on Stocks and Portfolios

The goal of this project was to understand and explore various trading strategies on stocks and portfolios made of stocks (along with risk-free assets). Further details of each of the project components are outlined in the specific README.md files in the respective folders. Here I am presenting a general overview for help in navigation.

This project has 3 components:

**1. ML-based Trading**

- Equal Weights Naive trading strategy
- MVP Optimization by selecting weights based on risk tolerance, expected return and sharpe ratio
- LSTM based prediction and trading
- LSTM + GRU based prediction and trading
- LSTM + GRU + Attention based prediction and trading
- LSTM + CNN based trading

**2. Pairs Trading**

- "Buying the yesterday's loser strategy"
- Logistic Regression Heuristic
- Decision Trees strategy with Feature Engineering
- Future Work: Hyperparameter Tuning, Ensembling, Cointegration, and Kalman Filters

**3. Portfolio Construction and Risk Analysis**

- Descriptive Statistics and Distributions Fitting
- MVP construction with and without shorting
- Tangency Portfolio construction with and without shorting
- Asset Allocation in various scenarios
- PCA and Factor Analysis **[_Valuable Insight:_ Found out that VISA and Mastercard were clubbed in a factor, and all the Tech companies were clubbed into a factor in our results]**
- Risk Analysis through Value at Risk (VaR) and Expected Shortfall (ES)
- Fitting Copulas to model join distribution of returns **[_Spoiler:_ T-Copula was the best fit by a large margin because it was able to capture tail dependencies better than Gumbel Copula]**

