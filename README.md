Gold Price Prediction

This repository contains a machine learning project focused on predicting the price of gold using historical data and economic indicators. The goal is to develop an accurate predictive model using regression techniques.

Table of Contents

Project Structure

Dataset

Features

Technologies Used

How to Run

Future Enhancements

Author

Project Structure

gold_price_prediction/
│
├── gold_price_prediction.ipynb  # Main notebook with analysis and ML modeling
├── gold_data.csv                # Dataset containing gold price and indicators
└── README.md                    # Project documentation (this file)

Dataset

The dataset (gold_data.csv) includes daily data on:

Gold prices

US Dollar Index

Crude oil prices

Stock indices (e.g., S&P 500)

Interest rates

This data allows us to explore trends and correlations that influence gold prices.

Features

Data exploration and preprocessing using pandas

Visualization using matplotlib and seaborn

Handling missing values and correlation analysis

Feature selection and regression modeling

Model evaluation using:

R² Score

Mean Squared Error (MSE)

Residual plots

Technologies Used

Python

Jupyter Notebook

pandas

numpy

matplotlib

seaborn

scikit-learn

How to Run

Clone the repository:

git clone https://github.com/yourusername/gold_price_prediction.git
cd gold_price_prediction

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Open the notebook:

jupyter notebook gold_price_prediction.ipynb

Execute the notebook cells sequentially.

Future Enhancements

Integrate time series models (e.g., ARIMA, LSTM)

Fetch real-time data from financial APIs

Build a web app using Streamlit or Flask

Author

Mohamed Rasooldeen

Feel free to contribute or fork this project to build your own predictive model!

