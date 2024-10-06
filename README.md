# Planetary Seismology Signal Detection

## Overview

This project focuses on the analysis of seismic data from the Apollo missions and the Mars InSight Lander to detect and classify seismic events. As planetary seismology missions encounter significant challenges in transmitting high-resolution seismic data back to Earth due to power constraints, our goal is to develop algorithms that effectively distinguish scientifically valuable signals from background noise.

The **primary objectives** of this project include:

- **Data Preprocessing**: Cleaning and filtering raw seismic data to isolate relevant frequency ranges. This step is crucial for enhancing the visibility of seismic signals and reducing the effects of noise.

- **Event Detection**: Implementing the Short-Term Average/Long-Term Average (STA/LTA) algorithm to identify potential seismic events within the noisy dataset. By analyzing energy differences across short and long segments of data, the STA/LTA algorithm provides a robust method for detecting seismic activity.

- **Machine Learning Classification**: Utilizing machine learning techniques, specifically a Random Forest classifier, to further refine the separation of noise from signals. This involves extracting key features from the seismic data, such as amplitude and energy, to train a model that can accurately predict whether a given segment is a signal or noise.

- **Visualization**: Providing clear visualizations of the filtered data, detected events, and model performance metrics. This aids in understanding the characteristics of the seismic signals and evaluating the effectiveness of the detection algorithms.

By effectively processing and analyzing seismic data, this project aims to contribute valuable insights into planetary seismology while optimizing data transmission for future missions. The methodologies developed here could be crucial for ensuring that only the most relevant seismic data is transmitted back to Earth, thereby conserving power and bandwidth in space exploration.
