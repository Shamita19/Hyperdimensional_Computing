# Seizure Detection System using Hyperdimensional Computing (HDC) and EEG Analysis

## Overview
This project implements a Seizure Detection System using Hyperdimensional Computing (HDC) to analyze EEG signals. The system leverages multiple feature extraction techniques, including Local Binary Pattern (LBP), Fourier Transform, and Wavelet Transform, to enhance signal processing and improve classification accuracy.

## Comparative study of feature extraction methods:
- LBP (93% accuracy)
- Fourier Transform (84% accuracy)
- Wavelet Transform (80% accuracy)

## Feature Extraction Methods:
- LBP (Local Binary Pattern): Achieved the highest accuracy (93%) by capturing spatial patterns in EEG signals.
- Fourier Transform: Provided frequency-domain analysis with an accuracy of 84%.
- Wavelet Transform: Extracted time-frequency features but resulted in a lower accuracy (80%).

## How It Works
1. Preprocess EEG signals to remove noise and standardize input.
2. Extract features using LBP, Fourier Transform, and Wavelet Transform.
3. Encode extracted features into high-dimensional vectors using HDC.
4. Train the system using labeled seizure and non-seizure data.
5. Classify new EEG data and detect seizures with optimized accuracy.

## Results & Performance
LBP outperformed other feature extraction methods, achieving 93% accuracy.
Fourier Transform and Wavelet Transform had lower accuracies at 84% and 80%, respectively.
The system demonstrates the effectiveness of HDC for EEG signal classification.

## Future Improvements
Integrate deep learning models for feature enhancement.
Optimize real-time processing for edge devices and IoT applications.
Expand testing with larger EEG datasets for improved generalization.
