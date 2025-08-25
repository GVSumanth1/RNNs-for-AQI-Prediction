# RNNs for AQI Prediction

Air quality is an important factor for health and environment. In this project, I tried to predict **Air Quality Index (AQI)** using **Recurrent Neural Networks (RNNs)**, as they are good at handling sequential and time-based data.

---

## Why I thought of using RNN
- AQI changes over time, so we need a model that remembers past values  
- RNN has a memory mechanism to use information from previous time steps  
- This helps in capturing **temporal dependencies** in data  

---

## Dataset I used
- Historical AQI data (with calculated AQI values)  
- Other features that can affect air quality like **temperature, humidity, wind speed, and rainfall** (planned for future use)  

---

## What I did

### Data Preprocessing
- Calculated AQI values  
- Converted data into sequences for model input  

### Model Workflow
1. AQI Calculation  
2. Sequence Creation  
3. Forecasting  
4. Model Training  
5. Evaluation of predictions  

### Forecasting
- Trained an RNN model with rolling sequences  
- Predicted future AQI values  

---

## What I learned
- RNN is useful when working with **time-series data**  
- Temporal dependencies can be captured better than traditional methods  
- Need to improve accuracy with advanced models  

---

## Future Improvements
- Try **hybrid models** and **stacked RNNs** for better accuracy  
- Automate the pipeline to **fetch, forecast, and publish AQI results**  
- Add more data sources like weather (temperature, humidity, rainfall, wind speed) for richer predictions  

---
