# BMI Neural Decoding Project

### Project Overview
This project was part of a neural decoding competition as part of my MSc program. The goal was to develop a neural decoder capable of predicting the trajectory of a monkey's hand based on neural spike train data. The project focused on real-time analysis and model accuracy, making it relevant for applications in brain-machine interfaces and neural prosthetics.

### Objectives
- Develop a causal neural decoder to predict hand trajectory from neural spike train data.
- Achieve low error rates in trajectory predictions using Root Mean Squared Error (RMSE) as the primary evaluation metric.
- Explore the effectiveness of various machine learning and data processing techniques in neural decoding.

### Techniques and Methods
The project used a combination of traditional and advanced machine learning techniques to process and analyze neural data:
- **Principal Component Analysis (PCA)** for dimensionality reduction.
- **Ridge Regression** as a linear baseline model.
- **Long Short-Term Memory (LSTM) networks** for sequence prediction and handling temporal dependencies in the data.
- Models were evaluated using **RMSE**, aiming for a minimal error in trajectory predictions.

### Results
The final model achieved an **RMSE below 8 cm**, demonstrating high accuracy and potential applications in neural prosthetics. The combination of PCA for dimensionality reduction and LSTM networks for sequence modeling proved to be effective for this task.

### Key Takeaways
- Effective dimensionality reduction using PCA was essential in handling high-dimensional neural data.
- Temporal dependencies in neural spike data could be efficiently modeled using LSTMs, providing accurate trajectory predictions.
- Real-time decoding models have significant potential in applications such as brain-controlled prosthetics, where prediction accuracy is crucial.

### Disclaimer
Due to university and competition rules, the original data and code used in this project cannot be shared publicly. This repository contains an overview of the project goals, methods, and results. 
