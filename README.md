# Data-Driven-Trader-Sentiment-Study

📊 Data-Driven-Trader-Sentiment-Study

This project analyzes the relationship between market sentiment (fear, greed, neutral) and trader performance using historical PnL data. It applies data cleaning, statistical testing, visualization, and basic machine learning to uncover patterns that can help improve trading strategies.



🧠 Project Features

- 📈 Visual analysis of trader performance vs sentiment
- 📉 Volatility comparison between fear and greed markets
- 🧪 Statistical significance testing using T-Test
- 🔍 Segmentation of performance by trade size
- 🤖 Basic machine learning model to predict profitable trades



📂 Dataset Overview

fear_greed_index.csv  
  Contains daily sentiment classification (fear, greed, neutral) with    dates.

historical_data.csv  
  Includes trading information: execution timestamps, closed PnL, trade size, and execution price.



🚀 Setup & Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-trader-analysis.git
   cd sentiment-trader-analysis
   ```

2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Place your CSV files inside the working directory:
   - `fear_greed_index.csv`
   - `historical_data.csv`



📊 Visualizations

- Boxplot: Profit/Loss by Market Sentiment  
- Line chart: Average daily PnL by sentiment  
- Bar chart: Volatility comparison (standard deviation)  
- Tabular summaries: PnL by sentiment and trade size




🔬 Statistical Insights

- **Profits** are generally higher in **Greed** conditions
- **Volatility (risk)** is also higher during Greed
- **T-Test** confirms that PnL difference is statistically significant
- **Larger trades** under Greed conditions outperform others




🤖 ML Classifier (Random Forest)

Predicts whether a trade was profitable based on:
- Trade Size
- Execution Price
- Sentiment (converted to binary: greed = 1, else = 0)

Evaluated with:
- Precision
- Recall
- F1-Score




📝 Summary Output

🔍 Summary:
1. Profits tend to be higher in Greed conditions.
2. Risk also rises, as seen in greater PnL variance.
3. The profit difference is statistically significant.
4. Larger trades under Greed performed best.
5. Sentiment helps improve profit prediction.




