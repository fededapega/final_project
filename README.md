# final_project

# Intro
In the realm of financial markets, leveraging historical data and advanced analytics has become paramount in predicting future trends and making informed decisions. In this project, I embarked on a comprehensive analysis of Bitcoin (BTC) utilizing a decade's worth of meticulously gathered data. Leveraging this extensive dataset, I incorporated various technical indicators and candlestick patterns to construct a robust predictive model.
Employing cutting-edge machine learning techniques, particularly Long Short-Term Memory (LSTM) neural networks, I endeavored to forecast the 7-day return of Bitcoin with precision and accuracy. By training the LSTM model on a rich feature set comprising historical price data, relative strength index (RSI), moving averages, and other pertinent indicators, I aimed to capture the intricate patterns inherent in BTC's market behavior.
The model trained on standardized data has a relatively high error, indicating that it is not performing well in predicting the 7-day return percentage for the asset.
The model trained on normalized data has a much lower error, but it may suffer from overfitting, meaning it might not generalize well to new, unseen data.
In summary, both models have issues that need addressing. The standardized model needs improvement to reduce its error, while the normalized model needs adjustments to prevent overfitting and improve its generalization capabilities.


Furthermore, beyond predictive modeling, this project delves into the realm of candlestick pattern analysis—a cornerstone of technical analysis in financial markets. By generating comprehensive buy, hold, and sell signals based on prevailing asset trends, we provide a nuanced understanding of BTC's market dynamics. This analysis serves as a valuable tool for traders and investors seeking to navigate the complex landscape of cryptocurrency markets with confidence and clarity.

## Installation

1. Clone the repository:

    git clone https://github.com/fededapega/final_project.git

2. Install the required dependencies using pip:

    pip install pandas yfinance pandas_ta numpy scikit-learn keras matplotlib

## Usage

To use the project:

1. Make sure you have installed all the dependencies as mentioned in the Installation section.
2. Run the provided Python script in your preferred Python environment.

   


 
