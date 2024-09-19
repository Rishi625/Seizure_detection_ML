# Data set link - https://physionet.org/content/chbmit/1.0.0/
# Seizure Detection using LSTM

This project develops a Long Short-Term Memory (LSTM) neural network model to detect seizures using EEG (Electroencephalogram) data. The goal is to classify EEG segments as either seizure or non-seizure events.

## Contents

1. **Data Preprocessing**
   - Loading EEG data
   - Extracting features from raw EEG signals

2. **Feature Engineering**
   - Extracting time-domain features
   - Calculating frequency-domain features

3. **Model Development**
   - Implementing LSTM neural network
   - Model compilation and training

4. **Model Evaluation**
   - Performance metrics calculation (accuracy, precision, recall, F1-score)
   - Confusion matrix visualization

## Key Features

- **Time-domain features**: Statistical measures of EEG signals
- **Frequency-domain features**: Power spectral density in different frequency bands
- **LSTM architecture**: Utilizes sequential nature of EEG data
