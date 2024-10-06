# Planetary Seismology Signal Detection

## Overview
This project aims to analyze seismic data from the Apollo missions and the Mars InSight Lander to identify and classify seismic events. Given the constraints of planetary missions, where high-resolution seismic data transmission to Earth requires significant power, the goal is to develop algorithms that can distinguish scientifically valuable signals from noise.

## Objectives
- Develop a system to process and analyze seismic data from planetary missions.
- Implement the Short-Term Average/Long-Term Average (STA/LTA) algorithm to detect seismic events.
- Utilize machine learning techniques, particularly Random Forest classifiers, to separate noise from seismic signals.
- Visualize the results, including filtered seismic data, detection performance, and classification metrics.

## Data Sources
- Seismic data from the Apollo missions.
- Data from the Mars Interior Exploration using Seismic Investigations, Geodesy, and Heat Transport (InSight) Lander.
- Example datasets provided for training and testing purposes.

## Methodology

### Data Preprocessing
- Load seismic data and perform necessary cleaning.
- Apply a bandpass filter to isolate relevant seismic frequencies.

### Event Detection
- Implement the STA/LTA algorithm to identify potential seismic events in the filtered data.
- Mark detected events for further analysis.

### Machine Learning Classification
- Extract features from the data, such as amplitude and energy.
- Train a Random Forest classifier to distinguish between noise and signal.
- Evaluate model performance using metrics like precision, recall, and F1-score.

### Visualization
- Plot the filtered seismic data with detected events.
- Generate confusion matrices and precision-recall curves to assess model performance.

## Results
- The model successfully identifies seismic events within the noisy data.
- Visualizations provide insight into the model's performance and the characteristics of the seismic signals.
