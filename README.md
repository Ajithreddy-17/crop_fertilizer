
# Crop and Fertilizer Recommendation System using Machine Learning
This project aims to build a Crop and Fertilizer Recommendation System using machine learning models. The system recommends the most suitable crop based on soil properties and climate conditions, and also suggests fertilizers based on the crop type and soil composition.
# Project Overview
The system is built using Random Forest for crop prediction and simple rule-based logic for fertilizer recommendation. The system uses two datasets:
## Crop_recommendation:
Contains soil parameters and climate conditions for crop prediction.
## Fertilizer_Prediction: 
Contains information about the required fertilizers for specific crops.
# Dataset Details
## Crop_recommendation Dataset:
`Columns: ['N', 'P', 'K', 'temperature', 'humidity', 'ph', 'rainfall', 'label']`
## Fertilizer_Prediction Dataset:
`Columns: ['Temparature', 'Humidity', 'Moisture', 'Soil Type', 'Crop Type', 'Nitrogen', 'Potassium', 'Phosphorous', 'Fertilizer Name']`
## Installation
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
## Project structure
`│
├── Crop_recommendation.csv        # Crop recommendation dataset
├── Fertilizer_Prediction.csv      # Fertilizer prediction dataset
├── main.py                        # Main script to run the project
├── README.md                      # Project documentation
└── crop_recommendation_model.pkl  # Trained model (optional)`
