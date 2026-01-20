# Market Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Active-green)

## Overview
This project serves as a foundational component for algorithmic trading strategies. By analyzing the sentiment (positive/negative polarity) of real-time tweets related to specific tickers or economic events, we can identify potential market movements correlated with public perception.

## Key Features
- **Real-time Data Collection**: Fetches tweets using the Twitter API.
- **Sentiment Scoring**: meaningful polarity scores using NLP techniques.
- **Volatility Correlation**: (In Development) Correlating sentiment spikes with market volatility.

## Tech Stack
- **Languages**: Python
- **Libraries**: Tweepy (Twitter API), TextBlob/VADER (Sentiment Analysis), Pandas, NumPy

## Getting Started

### Prerequisites
- Python 3.8+
- Twitter Developer API Keys

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rishisubedi/Market-Sentiment-Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Future Work
- Integration with LSTM models for time-series forecasting.
- Real-time dashboard for sentiment visualization.

---
*Note: This project is currently under active development.*
