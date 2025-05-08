# Air Quality Prediction Using FB Prophet

This project uses Facebook's [Prophet](https://facebook.github.io/prophet/) library to forecast air quality metrics, specifically relative humidity (RH), based on historical environmental sensor data.

## 📊 Dataset

The dataset is from the [UCI Air Quality Data Set](https://archive.ics.uci.edu/ml/datasets/Air+Quality), which contains hourly averaged responses from a gas multisensor device in an Italian city over several months.

- CSV used: `AirQualityUCI.csv`
- Features include: CO, NOx, NMHC, C6H6, Temperature, RH, etc.
- Some preprocessing was done:
  - Semi-colon delimiters (`;`)
  - Comma decimal points converted
  - Missing values marked as `-200` replaced with column means

## 📌 Objective

Forecast **Relative Humidity (RH)** over the next 365 hours using time series modeling with Facebook Prophet.

## 🧰 Tools and Libraries

- Python 3.x
- pandas
- numpy
- matplotlib
- prophet

## ⚙️ Installation

Create a virtual environment (optional but recommended) and install the dependencies:

```bash
pip install -r requirements.txt
