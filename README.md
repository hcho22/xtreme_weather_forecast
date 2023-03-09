# Extreme Weather Forecast

![](https://i.imgur.com/78b23qr.jpg)

This repository is a weather forecast model using LSTM. Extreme weather events are one of the biggest enviornmental problems in the world right now. These weather events have multiple impacts on agriculture, energy, transportation, as well as low resource communities and disaster planning in countries across the globe.

Accurate long-term forecasts of temperature and precipitation are crucial to help people prepare and adapt to these extreme weather events. The goal of this project was to predict the temperature over two-week period on specific region within the United States.  

# Dataset

The dataset can be downloaded in the following links:
- [Kaggle](https://www.kaggle.com/competitions/widsdatathon2023/data)

## Model 
The model was created using LSTM model from Tensorflow/Keras. Please refer to acknowledgements for additional reading.  
![](https://i.imgur.com/N3wLjrV.jpg)

## Test Results
The results from the training model. 

| Model       | Loss       | Val Loss   
| --------    | --------   | --------   
| LSTM        | 3.0360e-04 | 0.0021     

## Acknowledgements
- [Tensorflow LSTM](https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM)

### Limitations
Model 
- Currently the model was trained on one specific location of the region. Futher experiment is required to test on all or multiple regions.

### Resources
 - [Climate Change AI](https://www.climatechange.ai/)

