# 🌧️ Rainfall Prediction in Indian Regions Using Machine Learning

This project analyzes historical rainfall data across Indian subdivisions and districts to **predict future rainfall** using machine learning models. It uses regression techniques including **ElasticNet**, **Support Vector Regression (SVR)**, and a **1D Convolutional Neural Network (CNN)** for monthly rainfall forecasting.

---

## 📌 Key Features

- 📊 Visualizes historical monthly rainfall (1901–2015) for Indian subdivisions and districts
- 🔍 Data analysis with correlation heatmaps, bar charts, and trends
- 🤖 Implements multiple regression models:
  - ElasticNet Regression
  - Support Vector Regression (SVR)
  - Convolutional Neural Network (Keras)
- 📉 Evaluates model performance using:
  - MAE (Mean Absolute Error)
  - Predicted vs Actual rainfall graphs
  - Standard Deviation and Mean comparisons
- 📍 Focuses on **Telangana**, **Hyderabad**, and **Andhra Pradesh**

---

## 📂 Project Structure

Rainfall_in_india_1901-2015.csv # Monthly rainfall data (subdivision-level)
District_wise_rainfall_normal.csv # Monthly averages (district-level)
Rainfall_prediction.ipynb # Main notebook with all models and plots
README.md # Project documentation
Requirements.txt # Required Python packages

---

## 📈 Data Sources

- **Subdivision-level Rainfall Data**: Monthly rainfall values from 1901 to 2015 across 36 regions.
- **District-wise Rainfall Normals**: Normalized long-term averages per district.

---

## 🛠️ Models Used

| Model         | Application                | Example MAE (approx) |
|---------------|----------------------------|----------------------|
| ElasticNet    | Baseline linear regression | ~31–60 mm            |
| SVR           | Non-linear regression      | ~59–116 mm           |
| CNN (1D)      | Deep learning approach     | ~37–61 mm            |

---

## 📊 Sample Visuals

- Monthly rainfall histograms and line plots over years
- Seasonal bar plots (Jan–Feb, Mar–May, etc.)
- Heatmaps of feature correlations
- Predicted vs Actual rainfall for:
- Telangana: 2005, 2010, 2015
- Hyderabad and Andhra districts

---

## 🚀 How to Run

### 1. Clone the Repository

git clone https://github.com/yourusername/indian-rainfall-prediction.git
cd indian-rainfall-prediction

2. Install Dependencies
pip install -r requirements.txt

4. Run the Notebook
jupyter notebook rainfall_prediction.ipynb
Or open it in Google Colab.

📬 Contact
For questions or contributions, feel free to open an issue or submit a pull request.

📄 License
This project is open-source under the MIT License.
---

## ✅ `requirements.txt`
numpy==1.24.3
pandas==1.5.3
matplotlib==3.7.1
seaborn==0.12.2
scikit-learn==1.2.2
keras==2.13.1
tensorflow==2.13.0
