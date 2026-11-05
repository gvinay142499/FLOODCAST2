# FLOODCAST – Multi-Catchment River Flow Prediction

## Overview
FLOODCAST is a machine learning-based project designed to predict next-day river discharge and identify potential high-flow conditions across multiple river catchments in India.

## Objectives
- Predict next-day river discharge.
- Estimate the probability of high-flow conditions.
- Generate warnings when predicted high-flow probability crosses a selected threshold.
- Provide a simple dashboard for user inputs and predictions.

## Dataset
The project uses the CAMELS-IND dataset, containing hydrological, meteorological, and catchment-related information.

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Gradio

## Machine Learning Models
- HistGradientBoostingRegressor – river discharge prediction.
- HistGradientBoostingClassifier – high-flow probability prediction.

## Project Files
- `FLOODCAST_NEW_FINAL.ipynb` – Complete project notebook.
- `FLOODCAST_FINAL_BACKUP.zip` – Saved trained model files.

## How It Works
1. Collect weather and river-flow data.
2. Preprocess the data and create useful features.
3. Train regression and classification models.
4. Predict next-day discharge.
5. Estimate high-flow probability.
6. Display the result through a dashboard.

## Limitations
FLOODCAST is an academic prototype. It uses manually entered inputs and is not connected to live river monitoring systems. Its predictions should not be treated as official flood warnings.

## Future Improvements
- Integration with real-time weather and river data.
- Improved model validation.
- More catchment coverage.
- Deployment as a web application.

## Team
Developed as a student project.
