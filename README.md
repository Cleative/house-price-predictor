# House Price Predictor
## Project purpose
Predict house prices in Rwanda using multiple linear regression.
## Dataset
Target: `House_Price_Million_RWF`. `House_ID` is excluded from predictors.
## Model
80/20 split with `random_state=42`; one-hot encoding for Neighborhood; LinearRegression pipeline.
## Performance
Test R²: 0.7879
Test RMSE: 22.94 million RWF
## Run locally
`pip install -r requirements.txt`
`streamlit run app.py`
## Live app
Add the Streamlit Community Cloud URL after deployment.
