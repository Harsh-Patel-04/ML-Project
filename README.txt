# 🌞 Renewable Energy Production Forecasting System

This project predicts solar radiation using weather parameters like temperature, humidity, wind speed, etc., using machine learning (XGBoost). It helps in forecasting renewable energy production, especially for solar energy systems.


# 📂 Dataset

- Source: SolarPrediction.csv
- Features Used:
  - Temperature
  - Pressure
  - Humidity
  - Wind Direction (Degrees)
  - Wind Speed
- Target:
  - Solar Radiation (kW/m²)


# 💡 Project Structure

ML-Project/
├── data/
│   └── SolarPrediction.csv
├── notebooks/
│   └── renewable_energy_forecasting.ipynb
├── models/
│   └── (optional saved models)
├── docs/
│   └── ML PROJECT.pdf
├── requirements.txt
├── README.txt


# 🚀 How to Run

1. Clone this repository:
   git clone <your-repo-url>
   cd ML-Project

2. Create a virtual environment (optional but recommended):
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows

3. Install dependencies:
   pip install -r requirements.txt

4. Launch Jupyter Notebook:
   jupyter notebook notebooks/renewable_energy_forecasting.ipynb


# 📊 Results

- Model Used: XGBoost Regressor
- Metrics:
  - RMSE (Root Mean Squared Error)
  - R² Score


# 📌 Example Prediction

You can input a new set of weather conditions to get predicted solar radiation.


# 📚 License

This project is open-source and free to use for educational purposes.
