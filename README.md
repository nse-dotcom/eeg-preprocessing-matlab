# eeg-preprocessing-matlab
# Simple EEG Signal Preprocessing in MATLAB

This project provides a basic EEG signal preprocessing pipeline implemented in MATLAB. It includes steps such as bandpass filtering, artifact removal, power spectral density (PSD) computation, and band power feature extraction.

## 📦 Features

- Load EEG signal (`.mat` file)
- Bandpass filtering (1–40 Hz)
- Threshold-based artifact removal
- Power Spectral Density (Welch method)
- Band power feature extraction (Delta, Theta, Alpha, Beta)

## 📂 Folder Overview

- `code/`: MATLAB scripts
- `data/`: Sample EEG signal (simulated)
- `results/`: Output figures and features

## ▶️ How to Run

1. Generate dummy EEG data (or use your own `.mat` with `eeg_signal`, `fs`)
2. Run preprocessing:

```matlab
cd code
generate_dummy_eeg_data     % (Optional)
eeg_preprocessing
