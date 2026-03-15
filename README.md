# ECG Signal Processing and Heart Rate Detection
This project implements a basic ECG signal processing pipeline to detect heartbeats and estimate heart rate using Python.

## Dataset
MIT-BIH Arrhythmia Database  
A publicly available ECG dataset widely used in biomedical signal processing research.

## Methods
The ECG analysis pipeline includes:
1. Reading ECG signals using the WFDB library
2. Applying bandpass filtering to remove noise
3. Detecting R-peaks using signal processing algorithms
4. Calculating heart rate from RR intervals

## Tools
- Python
- NumPy
- SciPy
- Matplotlib
- WFDB

## Result
- The algorithm successfully detects R-peaks from the ECG signal and calculates heart rate.
- Average heart rate from the sample recording: **75.78 BPM**

## Visualization
The ECG waveform and detected R-peaks are visualized using Matplotlib.
