# 📈 Stock Price Prediction using Time Series Analysis

This project presents an in-depth study on stock price forecasting, specifically for **Apple Inc. (AAPL)**, using various **time series analysis techniques**. The study evaluates and compares traditional statistical models like **ARIMA and SARIMA**, deep learning-based models like **LSTMs**, and **Fuzzy Time Series** to develop a robust predictive framework.

## 📌 **Project Overview**
The goal of this project is to analyze historical stock prices of Apple Inc. and apply **multiple forecasting models** to identify patterns and trends, ultimately improving stock price prediction accuracy.

**Techniques Used:**
- **Long Short-Term Memory (LSTM)** for deep learning-based sequential forecasting
- **Autoregressive Integrated Moving Average (ARIMA)**
- **Seasonal ARIMA (SARIMA)** for capturing seasonal effects
- **Fuzzy Time Series** to handle uncertainty in stock price movements
- **Ensemble Approach** combining multiple models for improved accuracy

## 📂 **Project Structure**
📁 Stock_Price_Prediction/ │── 📄 Apple.csv # Dataset containing Apple stock price data │── 📄 Project Manual.txt # Instructions to set up and run the project │── 📄 CI_IEEE_Paper.pdf # Research paper on stock price forecasting │── 📄 CI_Presentation.pptx # Presentation slides summarizing the research │── 📄 README.md # Project documentation │── 📜 Fuzzy_time_series_fin.ipynb # Jupyter Notebook for Fuzzy Time Series model │── 📜 Stock_arima_sarima_lstm.ipynb # Jupyter Notebook for ARIMA, SARIMA, and LSTM


## 🚀 **Getting Started**
### 1️⃣ **Prerequisites**
Ensure you have the following installed before running the code:
- Python (>=3.8)
- Jupyter Notebook or Google Colab
- Required Python libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn statsmodels tensorflow keras
2️⃣ Setup & Execution
Download the dataset (Apple.csv) and place it in the project directory.
Run the Jupyter Notebooks:
Open Fuzzy_time_series_fin.ipynb and Stock_arima_sarima_lstm.ipynb in Jupyter Notebook or Google Colab.
Execute all cells to visualize and analyze the results.
📊 Models Implemented

Model	Purpose	Strengths	Limitations
ARIMA	Captures trends in stock data	Works well for short-term forecasts	Not suitable for complex patterns
SARIMA	Models seasonal stock price trends	Effective for time series with seasonality	Computationally expensive
LSTM	Deep learning model for sequential data	Captures long-term dependencies	Requires large datasets
Fuzzy Time Series	Handles uncertainty in data	Incorporates qualitative factors	Subjective design choices
Ensemble Model	Combines multiple forecasts	Improves overall prediction accuracy	Increased computational cost
📈 Results & Insights

The SARIMA model demonstrated the highest accuracy with the lowest Root Mean Squared Error (RMSE).
The LSTM model effectively captured long-term dependencies but required significant computational resources.
Ensemble learning improved overall accuracy but required careful balancing between different models.
❗ Limitations

Predictions are based solely on historical stock data and do not factor in external market influences.
The dataset is limited to Apple Inc., and results may vary for other stocks.
Some models require extensive hyperparameter tuning to improve accuracy.
📢 Acknowledgments

This research was conducted by Nilay Nisheethkumar Patel & Ashwani B Neminimadathil at Georgia State University.

Special thanks to Dr. Yanqing Zhang for his invaluable guidance in fuzzy logic and time series forecasting.

📜 References

Selvin, S., Vinayakumar, R., Gopalakrishnan, E.A., et al. (2017). "Stock price prediction using LSTM, RNN, and CNN."
Greff, K., Srivastava, R.K., Koutník, J., et al. (2017). "LSTM: A search space odyssey."
Chong, E., Han, C., Park, F.C. (2017). "Deep learning networks for stock market analysis and prediction."
Zhang, G.P. (2003). "Time series forecasting using a hybrid ARIMA and neural network model."
