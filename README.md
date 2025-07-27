# 🪙 Gold Price Prediction

This project applies machine learning to predict the price of gold based on historical data and related economic indicators. It demonstrates a data science pipeline from data exploration to model training and evaluation.

## 📁 Project Structure

gold_price_prediction/
├── gold_price_prediction.ipynb # Jupyter notebook with code, analysis, and model
├── data/ # Folder for datasets (not included in this repo)
│ └── gold_price.csv # Dataset used for training/testing
└── README.md # Project documentation

markdown
Copy
Edit

## 📊 Dataset

The dataset includes historical values for gold prices and various economic indicators like:

- USD/INR exchange rate
- Crude oil prices
- Stock market indexes (e.g., S&P 500)
- Interest rates
- Inflation rate

Ensure you place your dataset (e.g., `gold_price.csv`) in the `data/` directory before running the notebook.

## 🔍 Exploratory Data Analysis (EDA)

- Checked for missing values and data types
- Visualized feature correlations using heatmaps
- Analyzed trends in gold prices and economic indicators

## 🧠 Machine Learning Model

- **Algorithm**: Linear Regression (and optionally others like Random Forest, SVR)
- **Libraries Used**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`
- **Evaluation Metrics**:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

## 📈 Results

The model was trained and tested with a train-test split and achieved good predictive performance using selected features. The results were visualized with actual vs. predicted plots.

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/gold_price_prediction.git
   cd gold_price_prediction
Install required packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook gold_price_prediction.ipynb
🛠 Requirements
Python 3.7+

pandas

numpy

matplotlib

seaborn

scikit-learn

jupyter

📌 Future Improvements
Incorporate more recent data sources

Try advanced models like LSTM for time-series prediction

Deploy as a web app using Streamlit or Flask

📄 License
This project is open-source and available under the MIT License.

Author: Mohamed rasooldeen
