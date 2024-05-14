


**Project Description: Predicting Cryptocurrency Price Changes**

**Overview:**
In this project, I aim to collect data from an API. The dataset used for this project was obtained via the CoinMarketCap API, which provides comprehensive data about various cryptocurrencies, including market prices, trading volumes, and historical trends.

**Dataset:**
The dataset comprises a selection of features related to different cryptocurrencies, including their market performance metrics and other relevant information. Here are some key features included in the dataset:

- Quote currency volume change over 24 hours (`quote.USD.volume_change_24h`)
- Percentage change in price over 1 hour (`quote.USD.percent_change_1h`)
- Percentage change in price over 24 hours (`quote.USD.percent_change_24h`)
- Percentage change in price over 7 days (`quote.USD.percent_change_7d`)
- Percentage change in price over 30 days (`quote.USD.percent_change_30d`)
- Percentage change in price over 60 days (`quote.USD.percent_change_60d`)
- CoinMarketCap ranking (`cmc_rank`)
- Market capitalization in USD (`quote.USD.market_cap`)
- Market capitalization dominance (`quote.USD.market_cap_dominance`)


**Data Processing and Analysis:**
Upon acquiring the dataset,  I performed several preprocessing steps.  I applied some Exploratory data analysis (EDA) techniques to gain insights into key correlations in the data.

**Modeling Approach:**
 I used and explored various regression algorithms to develop predictive models for forecasting cryptocurrency price changes. Initially, I trained and evaluated simple models like Linear Regression. I then tried more sophisticated ensemble methods like Random Forest and Gradient Boosting to improve predictive accuracy.

**Hyperparameter Tuning:**
 I conducted Hyperparameter tuning using techniques like randomized search to optimize the performance of the chosen models. By systematically searching through different combinations of hyperparameters, the goal was to identify the settings that minimize prediction errors and improve model generalization.

**Model Evaluation and Validation:**
Evaluated the performance of each model using Mean Squared Error (MSE) and R-squared. 

