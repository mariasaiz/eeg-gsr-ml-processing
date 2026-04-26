# eeg-gsr-ml-processing
# EEG and GSR preprocessing for multimodal ML

This repository contains preprocessing and feature extraction pipelines for multimodal physiological data (EEG and GSR), used in the study:

"Application of Machine Learning to Multimodal Physiological Data in Educational Contexts"

## Contents

- EEG preprocessing notebook (MNE-Python)
- GSR/EDA preprocessing notebook (NeuroKit2)

## Methods

### EEG
- Band-pass filtering (1–45 Hz)
- Independent Component Analysis (ICA)
- Power Spectral Density (PSD)
- Frequency band extraction (Delta, Theta, Alpha, Beta, Gamma)

### GSR / EDA
- Tonic and phasic signal decomposition
- Skin Conductance Response (SCR) detection
- Feature extraction (onset, peak, amplitude, latency)
- Event-based segmentation

## Reproducibility

This repository supports the reproducibility of the preprocessing and feature extraction pipeline described in the associated publication.
