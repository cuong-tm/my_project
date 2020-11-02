# High_demand_suggestion
- Problem: At the driver's standing position,  when the order has not been received, the driver will wonder about her/his standing location that enables her/him to receive the order in n-minutes.   
- High demand suggestion is a solution that creates a heatmap showing the amount of single area's order demand in the next n minutes so that the driver can move to that area.
## Model: forecasting demand in the next n minutes
- We've tried several models: LightGBM, XGBoost,Long short-term memory (with Keras), ARIMA (and related ARIMA models), Prophet. In the end, LightGBM is the best. (file notebook)
## API: deploy model into api
- Use falcon,gunicorn,... 
## On production (img)

### Note: Due to corporate security, I cannot upload data and file build API here.