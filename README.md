# Independent-Study

# **📌 Bitcoin Price Prediction with Sentiment Analysis**
*Exploring the Impact of Social Media Sentiment on Bitcoin Price Movements*


## **📌 Project Overview**
We are analyzing **Bitcoin historical price data** and **social media sentiment data** to determine whether **public sentiment influences Bitcoin price movements**. This project will combine **time-series analysis** with **sentiment analysis** to enhance Bitcoin price prediction models.


## **📂 Datasets Used**
### **1️⃣ Bitcoin Historical Price Data**
We are using Bitcoin price data from various sources to analyze **market trends, volatility, and long-term price changes**.

- 📊 **[Yahoo Finance - BTC-USD Historical Data](https://finance.yahoo.com/quote/BTC-USD/history/)**  
  Provides **daily** open, high, low, and close (OHLC) prices for Bitcoin.  
- 📈 **[CoinMarketCap Bitcoin Historical Data](https://coinmarketcap.com/currencies/bitcoin/historical-data/)**  
  Offers **daily trading volume** and market capitalization trends.  
- ⏳ **[Kaggle - Bitcoin Historical Data](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data)**  
  Features **minute-by-minute** trading data across different exchanges (2012-present).  


### **2️⃣ Social Media Sentiment Data**
To understand how **public sentiment impacts Bitcoin price**, we are using social media datasets from Twitter and Reddit.

- 🐦 **[Twitter API](https://developer.twitter.com/en/docs/twitter-api)**  
  Enables access to **real-time and historical** tweets mentioning Bitcoin for sentiment analysis.  
- 🔥 **[Reddit API (Pushshift.io)](https://github.com/pushshift/api)**  
  Retrieves **Bitcoin-related discussions** from **r/Bitcoin** and **r/CryptoCurrency** to analyze community sentiment.  
- 💬 **[Kaggle - BTC Tweets Sentiment Dataset](https://www.kaggle.com/datasets/aisolutions353/btc-tweets-sentiment)**  
  Pre-collected tweets **labeled with sentiment (Positive, Neutral, Negative)**, useful for model training.  


### **3️⃣ Combined Datasets**
In addition to individual sources, we are also using **pre-processed sentiment datasets** that combine Reddit and Twitter data with financial indicators.

- 📑 **[Bitcoin Reddit Sentiment Dataset](https://aclanthology.org/2022.finnlp-1.27.pdf)**  
  Includes **annotated Reddit posts and comments** about Bitcoin, categorized by sentiment and emotion.


## **📚 Additional Resources**
To enhance our analysis, we are leveraging **open-source projects and repositories**:

- 🛠 **[GitHub - Bitcoin Sentiment Analysis](https://github.com/tomalexsmith/Bitcoin-sentiment-analysis)**  
  A project that investigates the **correlation between Bitcoin's market value and Twitter sentiment**.


## **🛠 Considerations for the Project**
We are focusing on key areas to **improve Bitcoin price prediction accuracy**:

- **📡 Data Collection:**  
  - Utilize APIs (**Twitter, Reddit**) for real-time sentiment tracking.  
  - Combine historical price data with sentiment trends.  

- **🧼 Data Preprocessing:**  
  - Clean and preprocess text data for sentiment classification.  
  - Align sentiment data with Bitcoin price movements **over time**.  

- **📊 Model Selection:**  
  - Use **time-series forecasting models** (ARIMA, LSTMs) to predict Bitcoin prices.  
  - Incorporate **sentiment features** into deep learning models.  


## **📌 Why This Approach?**
By leveraging **Bitcoin price trends and social media sentiment**, we aim to:
✅ **Identify market trends and volatility patterns**  
✅ **Analyze the impact of public sentiment on price movements**  
✅ **Develop an AI-powered model to predict Bitcoin price fluctuations**  

This project provides valuable insights into **crypto market behavior** and demonstrates how **social media sentiment** can be a key indicator for trading strategies. 🚀  


## **📜 Final Deliverables**
- 📊 **Bitcoin Price Trend Analysis**  
- 💬 **Sentiment Analysis & Correlation with Price**  
- 🤖 **Bitcoin Price Prediction Model**  
- 📜 **Final Report with Insights & Conclusion**  


