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

## 🐍 Python Analysis

### Key Features:
- **Data Cleaning:** Data was cleaned and prepared using Python’s powerful libraries.
- **Exploratory Data Analysis (EDA):** Detailed analysis of stock prices, volume, and trends.
- **Machine Learning Models:** Applied **Linear Regression** to forecast future stock prices.
- **Automated Visualizations:** Generated various charts automatically to visualize the data.

### Machine Learning Models:
- **Linear Regression:** Used to predict future stock prices based on historical data trends.

### Visualizations in Python:
1. **Stock Prices Over Time (Aug 2023 - Aug 2024)**  
   ![Python Stock Prices](link-to-python-stock-prices-image)

   *Description*: Similar to the Excel chart but generated using Python, this chart shows the Open, High, Low, and Close prices over time.

2. **Volume Over Time (Aug 2023 - Aug 2024)**  
   ![Python Volume](link-to-python-volume-image)

   *Description*: A line chart or bar chart depicting the volume over time, highlighting the trends in trading activity.

3. **Moving Averages Comparison**  
   ![Python Moving Averages](link-to-python-moving-averages-image)

   *Description*: A Python-generated chart comparing moving averages to identify trends and potential signals.

4. **Trend Analysis with Forecasting**  
   ![Python Trend Analysis](link-to-python-forecasting-image)

   *Description*: A line chart that includes both historical data and a forecasted trendline generated using linear regression.

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
