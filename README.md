# Microsoft Stock Prediction and Trading Algorithm

This repository is based on seed code from the [fin-ml GitHub repository](https://github.com/tatsath/fin-ml/blob/master/Chapter%205%20-%20Sup.%20Learning%20-%20Regression%20and%20Time%20Series%20models/Case%20Study%201%20-%20Stock%20Price%20Prediction/StockPricePrediction.ipynb). Enhancements were made to the seed code by incorporating additional feature engineering techniques, implementing advanced machine learning models, and evaluating the results with comprehensive financial metrics and statistical tests. Below is an overview of the project and its components.

---

## **Project Objectives**
1. Predict Microsoft stock prices using various machine learning models and statistical techniques.
2. Incorporate technical indicators such as RSI, MACD, and Bollinger Bands using TA-Lib.
3. Optimize feature selection using methods like PCA and RFE.
4. Compare and identify the most robust predictive model among Machine Learning, ARIMA, and LSTM.
5. Build a trading algorithm using the best-performing model.
6. Evaluate the trading system using financial metrics such as Sharpe ratio, profit ratio, and CAGR.
7. Assess model robustness with White reality checks and Monte Carlo permutation tests.

---

## **Repository Structure**
```
├── Input
│   ├── [Input data files and resources for preprocessing and analysis]
├── README.md                   # Project documentation
├── Seed Code.ipynb             # Original seed code for stock prediction
├── StockPricePrediction.ipynb  # Notebook for initial feature and model development
├── StockPricePrediction_Final.ipynb # Finalized notebook with feature importance plot
├── StockPricePrediction_Final.html # HTML version of the final notebook
├── best_model.sav              # Serialized file of the best model
├── coda-list.txt               # Metadata or additional notes for the project
```

---

## **How to Run**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/WoodyChang21/microsoft-stock-prediction.git
   cd microsoft-stock-prediction
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r coda-list.txt
   ```

3. **Run Notebooks**:
   Open and execute the Jupyter Notebooks (`StockPricePrediction.ipynb` and `StockPricePrediction_Final.ipynb`) to preprocess data, train models, and evaluate results.

4. **Analyze Results**:
   Check the final HTML file (`StockPricePrediction_Final.html`) for a summary of the analysis and feature importance plot.

---

## **Evaluation**
- The project evaluates the robustness of predictive models and trading algorithms using:
  - Train/Test financial performance metrics
  - Statistical tests to check for overfitting and biasb (White Reality Check, Monte Carlo Permutation)

---

## **Future Enhancements**
1. Extend the trading algorithm to include other financial instruments.
2. Integrate the feature selection into the training pipeline
3. Experiment with additional feature selection and extraction techniques.
4. Incorporate real-time data for live predictions and trades.

---

## **Contact**
Feel free to reach out if you have any questions or suggestions:
- **Email**: woodychang891121@gmail.com
- **GitHub**: [WoodyChang21](https://github.com/WoodyChang21)

