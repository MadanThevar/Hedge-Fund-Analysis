# 📊 IVV Stock Data Analysis 📈

Welcome to the **IVV Stock Data Analysis** project! This project focuses on analyzing the performance of the IVV (iShares Core S&P 500 ETF) stock using historical data. The analysis is performed using both **MS Excel** , **Python**, **Power-Bi** showcasing different methods of analysis and data visualization.

## 🚀 Project Overview

The goal of this project is to perform an in-depth analysis of the IVV stock to understand its behavior over time, identify trends, and provide forecasts for future performance using two different tools: **MS Excel**, **Python**, **Power-Bi**.

### 📊 Data Source:
- The data used in this analysis was sourced from **Yahoo Finance**. The dataset includes historical stock prices, volumes, and other relevant financial metrics for the IVV ETF from August 2023 to August 2024.


---

## 📊 MS Excel Analysis

### Key Features:
- **Data Organization:** The data is neatly organized in Excel for easier analysis.
- **Technical Indicators:** Calculation of Moving Averages and other key indicators.
- **Lookup and Reference Functions:** Utilized **XLOOKUP**, **INDEX**, and **VLOOKUP** functions to efficiently search and retrieve data based on specific criteria.
- **Statistical Analysis:** Performed **Summary Statistics** to calculate measures such as mean, median, and standard deviation.
- **Visualizations:** Charts created to visualize trends, volume, and price movements.

### Functions Used:
- **XLOOKUP:** Was used to efficiently search for and retrieve specific values from a dataset based on a corresponding lookup value. It's particularly useful when working with large datasets where you need to find data points like adjusted close prices or specific dates.
- **INDEX:** function was used to return the value of a cell in a specified row and column within a range. This function is ideal for extracting data from a table or array when the row and column numbers are known, providing flexibility in more complex data manipulations.
- **Summary Statistics:** Calculated key statistical measures to provide insights into the distribution and central tendency of the data.
  Output: 
<img width="908" alt="Screenshot 2024-08-26 at 17 07 26" src="https://github.com/user-attachments/assets/a0e2e775-7c2e-457d-9aa6-12e4cf9c8aab">

### Visualizations in Excel:
1. **30-Day Forward Trend Analysis of Close Prices**: 
   - **Insight**: The analysis reveals a consistent upward trend in the stock's closing prices, with an R-squared value of 0.9058, indicating strong momentum and suggesting continued growth in the near future.
   - <img width="528" alt="Screenshot 2024-08-25 at 15 55 34" src="https://github.com/user-attachments/assets/05f496df-c0af-45a4-9a18-294b9cc89f3e">


2. **Volume vs Closing Price (Aug 2023 - Aug 2024)**

   **Insight**: The Closing Price shows a general upward trend over the period, with some fluctuations, indicating periods of both growth and correction in the stock price.
The Volume has several spikes, particularly noticeable around March 2024 and July 2024. These spikes could indicate higher trading activity during these periods, possibly due to significant market events or earnings announcements that drove investor interest.
- <img width="571" alt="Screenshot 2024-08-26 at 17 00 01" src="https://github.com/user-attachments/assets/58914a0d-e100-4fe4-8206-c3acefe369f9">


3. **5-Day Moving Averages**  
   - **Insight**: The 5-Day Moving Average chart shows a steady upward trend over time, indicating consistent growth in stock prices with minimal short-term volatility.

- <img width="720" alt="Screenshot 2024-08-26 at 17 05 34" src="https://github.com/user-attachments/assets/a2dbfd5e-9158-4007-a70d-2d6de3dd9c5e">


5. **Pareto Chart: Distribution of Adjusted Close Prices with Cumulative %**
   
   <img width="651" alt="Screenshot 2024-08-25 at 15 37 59" src="https://github.com/user-attachments/assets/2d14b9bc-b4f0-43f7-8cdb-098635c6360b">

   **Insight**: A Pareto chart showing the distribution of Adjusted Close Prices in different ranges, along with the cumulative percentage. This chart helps in understanding the distribution and identifying the most common price ranges.

### Excel Files:
- `IVV(AutoRecovered).xlsx`: Contains all the raw data, calculations, and visualizations.

---

## Python Analysis 🐍

This section focuses on the data analysis conducted using Python, leveraging the power of various libraries to explore the stock data further.

### Key Visualizations 📊

1. **Stock Prices vs Volume Over Time**:
   - This graph shows a clear upward trend in the stock's closing prices, with a strong linear relationship (R² = 0.9058), indicating consistent growth over time.
   - **Key Insight**: The graph shows a significant spike in trading volume around May 2024, which coincides with a noticeable drop in stock prices. This pattern typically indicates increased selling pressure, possibly triggered by impactful news or market events.
     <img width="1272" alt="Screenshot 2024-09-02 at 16 58 32" src="https://github.com/user-attachments/assets/fea791bb-79de-43d1-9918-e33bf654f66c">


2. **Close Price with 10-Day and 50-Day Moving Averages**:
   - **Key Insight**: This graph displays the stock's daily closing prices, overlaid with its 10-day and 50-day moving averages. The 10-day MA reacts quickly to price changes, useful for spotting short-term trends, while the 50-day MA helps identify longer-term market directions. Crossings of these MAs by the closing price often signal potential trend reversals.
   - The point where the close price dips below both the 10-day and 50-day moving averages, around May 2024, indicates a potential bearish trend reversal. This could be a signal for traders and investors to reassess their positions as the market might be moving into a downtrend phase, suggesting a strategic decision point regarding holdings in this stock.
  <img width="1099" alt="Screenshot 2024-09-02 at 17 12 47" src="https://github.com/user-attachments/assets/c41e3739-bcaa-4d01-8b04-0c089e096cf7">


3. **Daily Return vs 10-Day Volatility**:
   - **Key Insight**: The scatter plot displaying Daily Return vs. 10-Day Volatility shows a dispersed pattern with no clear correlation between daily returns and short-term volatility. This indicates that higher volatility does not consistently lead to higher or more positive returns, suggesting that risk management strategies should be nuanced and consider additional factors beyond just volatility.

     <img width="650" alt="Screenshot 2024-09-02 at 17 20 49" src="https://github.com/user-attachments/assets/f5eae525-074f-435a-a7bc-a8f1c41274a3">
 
## 📈 Machine Learning Models and Insights 🤖

### Model Performance 📉

- **Logistic Regression** 📊:
  - **Accuracy Score**: 58.54%
  - **Insight**: Best for binary outcome predictions, this model's moderate accuracy suggests potential limitations with continuous stock price data.

- **Random Forest** 🌳:
  - **Accuracy Score**: 48.78%
  - **Insight**: Excellent for handling diverse datasets and preventing overfitting, albeit with modest accuracy in this instance.

- **Support Vector Machine (SVM)** 💡:
  - **Accuracy Score**: 63.41%
  - **Insight**: With the highest accuracy, SVM excels in classifying complex, non-linear data patterns.

- **Gradient Boosting** ⚡:
  - **Accuracy Score**: 46.34%
  - **Insight**: Although less accurate, it progressively improves predictions by learning from past mistakes.

## 🕒 ARIMA Model Analysis

### Overview

The **ARIMA (Autoregressive Integrated Moving Average)** model is a cornerstone in our analysis to forecast the future prices of the IVV (iShares Core S&P 500 ETF). It's specifically chosen for its efficacy in handling time series data, which is essential for understanding trends and cyclic behaviors in financial markets.

### Model Insight 🧠

- **Insight**: By meticulously analyzing the temporal dependencies and seasonal patterns in historical stock prices, the ARIMA model offers predictions with a significant degree of accuracy. It's particularly adept at understanding subtle shifts in market dynamics, which can be crucial for predicting stock movements during volatile periods.

### Graph Representation 📊

Below is the graph showing both the historical and forecasted stock closing prices as modeled by ARIMA:

<img width="663" alt="Screenshot 2024-09-09 at 15 52 30" src="https://github.com/user-attachments/assets/a6ac7072-5118-4152-95cb-2e496622864f">


- **Graph Description**: This graph provides a clear visualization of the historical closing prices from September 2023 through September 2024. Key features of the graph include:
  - **Trend Analysis**: The overall upward trend in the graph indicates a general increase in the stock price over time, with notable dips which could represent market corrections or external economic impacts.
  - **Forecasted Data**: The forecasted prices, extending from the last historical point, suggest a continuation of the upward trend but with potential fluctuations that could imply upcoming market volatility.
  - **Data Points**: Each point on the graph represents a daily closing price, providing a granular view of the stock's performance over the period.
  - **Visual Differentiation**: The historical data is displayed in a solid blue line, while forecasted data should ideally be marked in a different style (e.g., dashed line, different color) to distinguish between observed and predicted values clearly.

This graph not only aids in visualizing past performance but also in projecting future trends, which are pivotal for strategic planning and decision-making by investors and financial analysts.

## 💬 Sentiment Analysis

### Overview

Sentiment analysis plays a crucial role in our project, providing insights into the market sentiment surrounding the IVV (iShares Core S&P 500 ETF) stock. We utilize TextBlob, a powerful natural language processing (NLP) tool, to analyze sentiments expressed in financial news articles. This helps gauge public sentiment, which can significantly influence stock prices.

### Sentiment Analysis Details

- **Tool Used**: TextBlob
- **Data Source**: Financial news articles, primarily sourced from Yahoo Finance.
- **Key Metrics**:
  - **Sentiment Polarity**: Indicates the positivity or negativity of the sentiment. Values above 0 suggest positive sentiment, below 0 indicate negative.
  - **Sentiment Subjectivity**: Measures the amount of personal opinion vs. factual information; values closer to 1 indicate high subjectivity.

### Example Analysis

A recent analysis was performed on an article discussing the iShares Core S&P 500 ETF (IVV):

- **Article Excerpt**: "The iShares Core S&P 500 ETF (IVV) is designed to track the performance of the S&P 500 Index, which includes 500 of the ETF provides investors with broad exposure to the U.S. equity market, reflecting the performance of a broad cross-section of industries."
- **Sentiment Polarity**: 0.18 (Slightly Positive)
- **Sentiment Subjectivity**: 0.46 (Moderately Subjective)

<img width="1512" alt="Screenshot 2024-09-09 at 16 04 31" src="https://github.com/user-attachments/assets/f4d51a98-0ca6-4e9d-bb61-14e73fe9da1c">

## Financial Metrics Fetching with yfinance for IVV ETF

This section demonstrates how to retrieve key financial metrics for the iShares Core S&P 500 ETF (IVV) using the Python library `yfinance`. The metrics included are P/E Ratio, Earnings Per Share (EPS), Dividend Yield, and Revenue Growth, providing a snapshot of the ETF's financial health.

### Sample Python Code

<img width="660" alt="Screenshot 2024-09-09 at 16 12 23" src="https://github.com/user-attachments/assets/0282194a-da62-4775-8082-69cc163a68f6">


### Interpretation 📈

- **Insight**: The analysis reveals a slightly positive sentiment, suggesting a generally favorable view of the IVV ETF among financial commentators. This positive sentiment can lead to increased investor confidence and potentially enhance the ETF's market performance.
- **Impact on Stock Performance**: Positive market sentiment typically correlates with increased buying activity, which can drive up stock prices. Conversely, negative sentiment can lead to selling pressure and a decrease in stock prices.

This sentiment analysis provides a valuable perspective on how emotional and subjective factors can affect financial markets, complementing traditional financial metrics and enhancing our understanding of market dynamics.


### Functions & Libraries Utilized 🔧

- **Pandas**: For data manipulation and cleaning.
- **Matplotlib** & **Seaborn**: For creating informative and visually appealing charts.
- **Scikit-learn**: For implementing and evaluating the machine learning models.

### Data Source 📅

The data used in this analysis was sourced from Yahoo Finance, ensuring a comprehensive and accurate dataset for the period from August 2023 to August 2024.

---

### Python Files:
- `IVV Stock Data Analysis.html`: A detailed HTML report generated from the Python analysis, including the code and visualizations.

---

## 🛠️ Tools Used

- **MS Excel**: For initial data organization, calculations, and visualization.
- **Python**: For advanced data analysis and automated visualization.
- **Pandas**: For data manipulation and preparation.
- **Matplotlib**: For creating visualizations in Python.
- **Scikit-Learn**: For implementing the Linear Regression model.

---

## 🎯 Objectives

- **Understand historical stock performance**: By analyzing past data, we can gain insights into future trends.
- **Identify patterns**: Recognize patterns that could indicate potential future movements in stock prices.
- **Make informed decisions**: Use the insights gained from the analysis to inform investment decisions.

---
