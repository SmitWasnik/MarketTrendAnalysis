# Random Forest Regressor Prediction Model

This project implements a **Random Forest Regressor Model** to predict stock market trends based on historical stock price data.  
It was developed and tested in **Google Colab**, and the code is now hosted on GitHub.

---

## 📌 Project Overview
- Uses **Random Forest Regressor** for prediction tasks.  
- Data is fetched directly from **Yahoo Finance (`yfinance`)**.  
- Built in **Python** with libraries such as `pandas`, `numpy`, `yfinance`, `scikit-learn`, and `matplotlib`.  
- Runs on **Google Colab** and can also run locally.  
- Beginner-friendly implementation for stock trend prediction.

---

## ⚙️ How It Works
1. **Data Fetching**: Stock price data is fetched using the `yfinance` library.  
2. **Data Preprocessing**: The data is cleaned and organized into features (X) and target values (y).  
3. **Model Training**: A **RandomForestRegressor** model from `sklearn.ensemble` is trained on the dataset.  
4. **Prediction**: The trained model predicts stock prices for given input features.  
5. **Visualization**: Actual vs Predicted values are plotted using `matplotlib` for easy comparison.

---

## 🚀 Running the Code

### Option 1: Run in Google Colab
1. Upload the notebook to Colab.  
2. Run all cells step by step.  
3. The trained model will generate predictions.

### Option 2: Run Locally (Windows)
1. Clone this repository:
   ```bash
   git clone https://github.com/SmitWasnik/MarketTrendAnalysis.git
   cd MarketTrendAnalysis
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python script or notebook.

---

## 📊 Example Output
After training, the model predicts values for the given input dataset. Example:

```
Input: Stock Price Features (X)
Predicted Output: Future Stock Prices (Y)
```

A sample visualization:

- **Blue Line** → Actual Stock Prices  
- **Red Line** → Predicted Stock Prices  

---

## 📂 Project Structure
```
project-folder/
│── model.py / notebook.ipynb   # Code for training and prediction
│── requirements.txt            # List of dependencies
│── README.md                   # Project documentation
```

---

## 🧑‍💻 Author
- **Smit Wasnik**  
Pursuing *Minor in AI (IIT Ropar)* | Mechanical Design Engineer  
