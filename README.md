🚀 Overview

The goal of this project is to predict future sales for multiple stores using historical data. The model takes into account various factors such as:

    Holidays and events
    Oil prices
    Store information
    Transaction history



    Store Sales Prediction (time series)
├── app.py                  # Streamlit app to display predictions
├── Dockerfile              # Docker configuration
├── main.ipynb              # Jupyter Notebook for data exploration and model training
├── requirements.txt        # Python dependencies
├── xgb_model.pkl           # Trained XGBoost model
├── average_sales.csv        # Processed average sales data
├── holidays_events.csv      # Holiday and event data
├── oil.csv                  # Oil price data
├── oil_df_filled.csv        # Cleaned oil price data
├── stores.csv               # Store details
├── transactions.csv         # Transaction history
├── train.csv                # Training data
├── test.csv                 # Test data
├── sample_submission.csv    # Sample submission file



🛠️ How to Run
1. Build Docker container:

docker build -t my-app .

2. Run Docker container:

docker run -p 8501:8501 my-app
