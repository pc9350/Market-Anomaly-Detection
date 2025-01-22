# Market-Anomaly-Detection

This project implements an early warning system for identifying potential financial market crashes using machine learning and LLM-powered strategy generation. The system analyzes market data to detect anomalies and generates investment strategies for risk mitigation and portfolio optimization.

## Features

- **Anomaly Detection Models**: Utilizes multiple ML models including Random Forest, XGBoost, and Isolation Forest to identify market anomalies
- **Strategy Generation**: Implements automated trading decisions based on detected anomalies
- **LLM Integration**: Uses Groq API to generate detailed investment strategies and market analysis
- **Risk Management**: Includes position sizing and performance metrics calculation
- **Performance Analytics**: Tracks key metrics including Sharpe ratio, win rate, and maximum drawdown

## Technical Stack

- Python
- Pandas for data manipulation
- Scikit-learn for ML models
- Groq API for LLM integration
- NumPy for numerical computations
- Matplotlib/Seaborn for visualizations

## Usage

```python
# Example usage
data_path = 'path/to/your/market_data.csv'
api_key = 'your_groq_api_key'
# Run the strategy
run_strategy_example(data_path, api_key)

```

## Output Example

The system provides:
- Current market position recommendations
- Position sizing suggestions
- Performance metrics
- Detailed strategy explanation from LLM
- Risk management considerations

## Skills Demonstrated

- Machine Learning & Data Science
- Financial Analysis & Trading Strategy Development
- Python Programming & API Integration
- LLM Integration & Prompt Engineering
- Risk Management Implementation

## Challenges Faced

Handling NaN values and data quality issues in financial time series data, optimizing model performance for imbalanced datasets, implementing effective position sizing, and managing API rate limits with LLM integration.

## Future Iterations

Implement deep learning models (LSTM, Transformers) for improved anomaly detection, add real-time data streaming, develop a web interface for strategy monitoring, and enhance the LLM integration with market sentiment analysis and automated strategy adjustments.