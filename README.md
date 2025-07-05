# 📈 Stock Market Analysis and Microsoft Stock Prediction

This project involves analyzing stock market data and predicting Microsoft stock prices using an LSTM deep learning model. It consists of exploratory data analysis and time series forecasting with a saved trained model.

---

## 📁 Project Structure

| File Name                          | Purpose |
|-----------------------------------|---------|
| `Stock_Analysis.ipynb`            | Performs data exploration and visualization of historical stock prices. Helps understand patterns and trends before modeling. |
| `Microsoft_Stock_Prediction.ipynb`| Builds and trains an LSTM model using TensorFlow/Keras to predict Microsoft stock prices. Evaluates performance using metrics like MAE/RMSE. |
| `my_model.keras`                  | Saved trained LSTM model for future predictions or deployment. |

---

## 🔧 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- TensorFlow / Keras
- Scikit-learn

## 📌 Key Features

- Visual analysis of stock price behavior
- LSTM-based sequence prediction model
- Model persistence using `.keras` format
- Scaled and prepared dataset with proper train-test split
- Performance evaluation with real-time prediction visualization

## 📌 Future Improvements

- Integrate additional features like volume, moving averages, and technical indicators  
- Hyperparameter tuning and model optimization  
- Deploy model via Streamlit dashboard or web API
