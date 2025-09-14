🌦️ Weather Prediction using Machine Learning

This project predicts temperature using Machine Learning. Weather data (temperature & humidity) is fetched automatically from the Open-Meteo API (no CSV file required).

🚀 Features

Fetches real historical weather data (temperature, humidity) via API.

Trains a Linear Regression model to predict temperature.

Evaluates model performance with Mean Squared Error (MSE).

Visualizes actual vs predicted temperature trends.

📂 Project Structure
├── weather_prediction.ipynb   # Jupyter Notebook with full code
├── README.md                  # Project documentation

🛠️ Installation

Clone this repo:

git clone https://github.com/K010208/weather-prediction.git
cd weather-prediction


Install required libraries:

pip install requests scikit-learn matplotlib pandas

▶️ Usage

Open the Jupyter Notebook:

jupyter notebook weather_prediction.ipynb


Run all cells.

By default, the code fetches weather data for New Delhi (India):

latitude = 28.6139
longitude = 77.2090


You can change latitude & longitude for your city.

📊 Results

The model outputs:

Mean Squared Error (MSE) → model accuracy

Graph comparing actual vs predicted temperature

Example visualization:

📚 Technologies Used

Python

Open-Meteo API – free weather data

scikit-learn – Linear Regression model

matplotlib – visualization

pandas, numpy – data handling

📌 Future Improvements

Use LSTM (Deep Learning) for sequence forecasting.

Add more weather features (wind speed, rainfall, pressure).

Build a Streamlit web app for real-time predictions.

👤 Author

GitHub: K010208
