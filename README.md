# solar-energy-production-prediction
## 🌞 Overview
This project builds a machine learning model to predict the estimated annual PV energy production (in kWh) for solar power projects using metadata like location, developer, and utility details. It helps improve solar planning, ROI estimation, and grid integration.

## 📊 Dataset
- Source: [Confidential or Private]
- Size: 218,000+ projects
- Features include:
  - Developer, City, County, Zip, Utility
  - System Size (kWdc/kWac), Metering Method
  - Interconnection Date, Annual Production

## 🛠️ Methodology
- Data cleaning & preprocessing
- Feature engineering (e.g., system efficiency)
- Exploratory analysis
- Model training using Random Forest Regressor
- Evaluation (MAE, RMSE, R²)

## 🎯 Results
- Final model R²: 0.736 (no leakage)
- Enables project planning without using technical system specs

## 📈 Visuals
See `/images/` folder or generated from notebook

## 🔮 Future Improvements
- Add solar irradiance/weather data
- Use deep learning for complex pattern detection
- Build full dashboard for client use

## 📁 Folder Structure
- `notebooks/` – Jupyter notebook analysis
- `images/` – Visuals for slides or reports
- `reports/` – PPT or PDF report
- `src/` – Optional Python scripts

## 🤖 Tools Used
- Python (Pandas, Scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebook
