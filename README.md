# AM10_Final_Group_Project_Gp13

AM10 Data Visualisation Group 13
Short Term Technical Indicators Across Asset Classes Implications for Allocation Decisions

This project studies how short term technical indicators behave across different asset classes and how these patterns can inform simple allocation decisions. We compare cryptocurrencies and commodities to understand whether indicators such as trend, momentum, volatility and price deviations provide signals that differ across markets.

We work with a large multi asset dataset covering the years 2000 to 2025. It includes daily prices, volumes and information for assets such as Bitcoin, Ethereum, Gold, Oil and Silver. The dataset required cleaning, aligning dates across assets, fixing missing values and creating engineered features such as returns, future returns, rolling volatility, momentum and price Z scores.

Data available here https colon slash slash www dot kaggle dot com slash datasets slash mubashir24 slash multi asset market data 2000 2025

Our analysis uses Python for data cleaning, feature engineering and modelling, and Tableau for visualisation. Techniques include
• Scatterplots, heatmaps and distribution charts
• Correlation analysis
• Linear and logistic regression
• LASSO logistic regression
• A simple allocation backtest based on predicted signals

Key Questions

Do these indicators behave differently across asset classes

Are signals more reliable within cryptocurrency markets or commodity markets

Does adding machine learning improve predictive accuracy

Can these signals support a basic allocation rule

Results
Technical indicators show inconsistent power across assets. Cryptocurrencies display stronger momentum and volatility effects while commodities behave in a more stable and muted way. Although models improve slightly over random guessing, signals remain unstable. The simple allocation test highlights when indicators may help and when they fail.

This project summarises our work from data preparation to modelling and visual analysis. All steps can be reproduced by cloning the repository.
