# Time Series Forecasting Using Facebook Prophet

This project presents a comprehensive analysis and forecasting of weekly sales using the **Facebook Prophet** time series model. It includes data preprocessing, model fitting, future forecasting, and result visualization with detailed explanations of the components involved.

## 📄 Project Overview

The aim of this project is to forecast future weekly sales for a retail store using Prophet, a robust additive model designed to handle seasonality and trend changes.

## 📁 Files Included

- `prophet_sales_forecasting_paper_with_descriptions_final.docx`  
  ➤ A complete research paper detailing the methodology, model, visualizations, and interpretations.

- `forecast_plots/`  
  ➤ Folder containing all generated plots used in the research paper.

- `sales_forecasting_prophet.ipynb` *(optional if you want to include code)*  
  ➤ Jupyter Notebook with Python code used for the analysis.

## 📊 Forecasting Model

Facebook Prophet was used with:
- **Yearly** and **Weekly** seasonality enabled
- Custom seasonality and changepoint prior scales for better control
- Forecast horizon: **365 days**

## 📌 Key Components Explained

- **Blue Line**: Predicted trend or component estimate.
- **Shaded Area**: 95% confidence interval around the prediction.
- **Trend Plot**: Shows the overall direction of sales (increase/decrease).
- **Seasonality Plots**: Visualizes recurring patterns by week and year.

Each plot in the document includes captions and interpretations for clarity.

## 🛠️ Requirements

- `pandas`
- `matplotlib`
- `prophet` (formerly `fbprophet`)
- `cmdstanpy` (backend dependency for Prophet)

## 🧪 Usage

To replicate the analysis or apply it to your own data:

```bash
pip install prophet pandas matplotlib

IF YOU DON'T UNDERSTAND THIS CODE, YOU CAN CHECK THE RESEARCH REPORT IN THIS COMPOSITORY
