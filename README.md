# Stock Market Analyzer


A comprehensive Python tool for analyzing stock market data, calculating technical indicators, and visualizing market trends. This analyzer allows users to download historical S&P 500 data and generate insights through various technical analysis techniques.

## What It Does

- **Historical Data Analysis:** Downloads and processes S&P 500 ETF (SPY) data from 1994 to present
- **Technical Indicators:** Calculates key technical indicators including:
          - Simple Moving Averages (20, 50, and 200-day)
          - Daily returns and cumulative performance
- **Visualization:**
          - Full history price chart with moving averages
          - Recent 2-year market performance
          - High-resolution image export (300 DPI)
- **Performance Metrics:**
          - Total return calculation
          - Annualized returns
          - Volatility measurement
          - Sharpe ratio for risk-adjusted performance
          - Period-specific performance (1M, 3M, 6M, 1Y)
- **Technical Analysis:**
          - Current market positioning relative to major moving averages
          - Trend identification (bullish/bearish)

## Requirements
- Python 3.9+
- Required packages:
          - pandas
          - numpy
          - matplotlib
          - seaborn
          - yfinance (v0.2.28 recommended)

## Installation

```bash
# Clone this repository
git clone https://github.com/nodokashibasaki3/stock-market-analyzer.git

# Navigate to the project directory
cd stock-market-analyzer

# Install required packages
pip install pandas numpy matplotlib seaborn yfinance==0.2.28
```

## Usage

```bash
# Run the analyzer
python stock_analyzer.py
```

## Output

The script generates:
1. Terminal output with comprehensive performance metrics
2. Two PNG image files:
    - spy_price_history.png - Complete historical analysis
    - spy_recent_price_history.png - Last 2 years of market performance

## Sample Results
- **Total Return:** Calculate the total percentage return since 1994
- **Annualized Return:** Average yearly return
- **Annualized Volatility:** Standard deviation of returns
- **Sharpe Ratio:** Risk-adjusted performance measure

## License

MIT — free to use, fork, and improve.

## 🙋‍♀️ Author

Developed by [Nodoka Shibasaki](https://github.com/nodokashibasaki3)
