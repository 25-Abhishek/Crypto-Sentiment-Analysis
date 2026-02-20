# Crypto Trader Performance vs. Market Sentiment Analysis

##  Project Overview
This project was developed as a part of the Data Science Intern assignment. It explores the relationship between a cryptocurrency trader's performance and the overall market sentiment. By merging historical trading data with the daily **Fear & Greed Index**, the project analyzes how different market moods (e.g., Fear, Neutral, Greed) impact the trader's Profit/Loss (PnL) and Win Rate.

##  Datasets Used
1. **Historical Trade Data (`historical_data.csv`)**: Contains trade-level metrics including timestamp, coin, execution price, side (Buy/Sell), and Closed PnL.
2. **Fear & Greed Index (`fear_greed_index.csv`)**: Contains daily sentiment values (0-100) and categorical classifications (e.g., Extreme Fear, Greed).

##  Tech Stack & Libraries
* **Python 3.x**
* **Pandas**: For data cleaning, datetime formatting, and inner merging of datasets.
* **Matplotlib & Seaborn**: For generating professional and scannable visualizations.

##  How to Run the Project
1. Clone the repository or download the project files.
2. Ensure both dataset files (`historical_data.csv` and `fear_greed_index.csv`) are located in the same root directory as the code file.
3. Install the required dependencies using pip:
   ```bash
   pip install pandas matplotlib seaborn
