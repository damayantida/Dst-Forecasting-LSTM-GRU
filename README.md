# Dst Index Time Series Prediction using LSTM & GRU

## Overview
This project focuses on predicting the **Disturbance Storm Time (Dst) index**, a key measure of geomagnetic storm energy levels, using **Long Short-Term Memory (LSTM)** and **Gated Recurrent Unit (GRU)** models. These models, as specialized forms of Recurrent Neural Networks (RNNs), are well-suited for handling long-term dependencies in time series data.

## Dataset
- The dataset consists of **hourly historical Dst index data from 2014 to 2023**.
- Data was sourced from the **OMNI database** (King & Papitashvili, 2020) under **NASA's Space Physics Data Facility**.

## Objective
The aim of this study is to analyze and compare **LSTM and GRU** models for time series forecasting and determine their effectiveness based on **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)**.

## Results
- Both LSTM and GRU models **outperformed the baseline model**.
- The difference between LSTM and GRU performance was **not significant**.
- The GRU model exhibited a **slightly better RMSE** in test data predictions.

## Tech Stack
- **Programming Language**: Python
- **Libraries Used**:
  - TensorFlow (for building LSTM & GRU models)
  - scikit-learn (for preprocessing and evaluation)
  - NumPy & pandas (for data manipulation)
  - Matplotlib (for visualization)

## Contribution
Feel free to contribute by submitting issues, feature requests, or pull requests!

## References
- King, J. H., & Papitashvili, N. E. (2020). OMNI Data, NASA Space Physics Data Facility.

## License
This project is licensed under the **MIT License**.
