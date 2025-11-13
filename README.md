# COVID-19 Cross-Country Forecasting

This repository contains the complete forecasting pipeline used in the peer-reviewed publication:

## 📄 Scientific Publication 

**Smoothing Techniques for Improving COVID-19 Time Series Forecasting Across Countries**  
Published in *Computations (MDPI)* - **Scopus Q2**  
🔗 Article link: https://www.mdpi.com/2079-3197/13/6/136

This repository reproduces all experiments, figures, and evaluation results described in the paper.

---

## 📊 Project Overview

This project analyzes the impact of smoothing techniques on COVID‑19 forecasting accuracy.  
We compare **four smoothing methods** and **four forecasting models** across **four European countries**:

### 🌍 Countries
- Ukraine  
- Bulgaria  
- Slovenia  
- Greece  

### 🔧 Smoothing Methods
- Rolling Mean  
- Exponential Weighted Moving Average (EWMA)  
- STL Trend extraction  
- Kalman Filter  

### 🤖 Forecasting Models
- Temporal Fusion Transformer (TFT)  
- LSTM  
- XGBoost  
- LightGBM  

### 📈 Forecast Horizons
- 3‑month forecasting  
- 6‑month forecasting  

### 🧪 Metrics
- RMSE  
- MAE  
- MAPE  
- log-MAPE stability  

---

## 📂 Repository Structure

```
├── data/
│   ├── WHO-COVID-19-global-daily-data.csv
│   ├── smoothing_methods_four_countries.csv
│   └── smoothing_methods_four_countries_3_monthes.csv
│
├── smoothing_methods.ipynb        # Full experiment notebook from the paper
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run Experiments

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Open the experiment notebook:
```bash
jupyter notebook smoothing_methods.ipynb
```

3. Run all cells to reproduce:
- Smoothing transformations  
- Model training  
- Forecasting  
- Heatmaps  
- Boxplots  
- Statistical tests  

---

## 📬 Contact

Author: **Uliana Zbezhkhovska**  
If you use this repository, please cite the MDPI publication linked above.

