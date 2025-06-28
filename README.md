# Machine_learning_classification_Time_serie_data_seismic

# Seismic Signal Classification Using CNN

This project demonstrates how to generate synthetic seismic signals (earthquake and noise), train a 1D Convolutional Neural Network (CNN) to classify signal windows, and visualize classification results on a long mixed seismic signal.

---

## **Overview**

Seismic signals often contain noise and earthquake events that must be distinguished for monitoring and analysis. This repository provides a complete pipeline to:

- **Generate synthetic seismic signals** simulating earthquake bursts and noise.
- **Visualize sample signals** to understand class characteristics.
- **Train a CNN model** to classify fixed-length windows of seismic data as earthquake or noise.
- **Apply the trained model** to a long mixed signal and visualize the classification over time.

---

## **Features**

- Synthetic data generation with controlled noise and earthquake bursts.
- Labeled visualization of example earthquake and noise signals.
- 1D CNN architecture tailored for time-series classification.
- Model training with validation and test splits.
- Window-by-window classification of long seismic signals.
- Visualization of classification results with color-coded plots (red = earthquake, blue = noise).


