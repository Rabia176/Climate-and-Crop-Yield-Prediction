# Climate-and-Crop-Yield-Prediction
# Climate and Crop Yield Prediction (Wheat)

**Project type:** Data analysis / predictive modeling (toy dataset)

## Description
This project demonstrates how to predict wheat yield (tons/ha) from climate variables (temperature, rainfall, and solar radiation).
The provided data is synthetic and for demonstration purposes; replace with FAO crop yields and NASA POWER climate data for a full study.

## Files
- `data/crop_yield_wheat.csv` — sample wheat yields (2010, 2015, 2020)
- `data/climate_annual.csv` — sample climate variables (annual averages)
- `data/merged_crop_climate.csv` — merged dataset
- `climate_crop_yield_prediction.ipynb` — Jupyter notebook with EDA, regression, and Random Forest

## How to run
1. Clone repo and ensure files are in `data/` folder.
2. Install requirements: `pip install -r requirements.txt`
3. Open and run the notebook: `jupyter notebook climate_crop_yield_prediction.ipynb`

## Next steps / Improvements
- Use real FAO and NASA POWER datasets.
- Add soil and management variables.
- Try panel regression and time-series forecasting.
- Deploy results with Streamlit for an interactive demo.
