🪙 Gold Price Prediction
This project focuses on predicting gold prices using historical financial data and machine learning techniques. The model is trained using the Random Forest Regressor algorithm for high accuracy in regression tasks.

📊 Dataset
The dataset used is gld_price_data.csv, which contains features such as:

SPX (S&P 500 index)

GLD (Gold ETF prices)

USO (Oil ETF prices)

SLV (Silver ETF prices)

Others...

📌 Note: Ensure you have this dataset locally before running the notebook.

📌 Project Highlights
📥 Data loading and cleaning using pandas

📈 Exploratory Data Analysis (EDA) with matplotlib and seaborn

🧠 Model training using RandomForestRegressor from scikit-learn

🧪 Model evaluation using R² Score

📉 Actual vs Predicted plot for performance visualization

🔧 Requirements
Install the required Python libraries using:

bash
Copy
Edit
pip install numpy pandas matplotlib seaborn scikit-learn
🚀 How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/<your-username>/gold_price_prediction.git
cd gold_price_prediction
Make sure you have gld_price_data.csv in your project directory.

Run the notebook using Jupyter or Colab.

📈 Evaluation Metrics
The model’s performance is measured using the R² Score, which indicates how well the predictions match the actual gold prices.

python
Copy
Edit
from sklearn import metrics
r2 = metrics.r2_score(Y_test, test_data_prediction)
print("R² Score:", r2)
A higher R² score (close to 1) indicates a better fit.

📉 Sample Output
Evaluation Metric:

yaml
Copy
Edit
R² Score: 0.989 (example)
Visualizations:

Correlation heatmap

Line graph of actual vs predicted prices

📚 Future Improvements
Incorporate time-series forecasting models (ARIMA, LSTM)

Automate hyperparameter tuning

Use external market indicators

🧑‍💻 Author
Mohamed Rasooldeen
