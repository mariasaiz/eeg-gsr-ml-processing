# eeg-gsr-ml-processing
# EEG and GSR Preprocessing for Multimodal Machine Learning

This repository contains preprocessing and feature extraction pipelines for multimodal physiological data (EEG and GSR/EDA), developed as part of the study:

"Emotion recognition from multimodal biosignals: a machine learning approach based on EEG and GSR"

## Overview

This project provides reproducible pipelines for processing multichannel physiological signals and extracting features for subsequent Machine Learning (ML) analysis. The approach integrates EEG and GSR/EDA data to support the analysis of cognitive and emotional processes in applied psychological contexts.

The repository is designed to support both:
- **Supervised ML** (prediction and classification)
- **Unsupervised ML** (pattern detection and clustering)
  
## Repository Structure
project/
│
├── data/
│ ├── raw/ # Input data (not included)
│ └── processed/ # Output data (generated automatically)
│
├── EEG_preprocessing_clean_EN.ipynb
├── GSR_preprocessing_clean_EN.ipynb
└── README.md

## Contents

- EEG preprocessing notebook (MNE-Python)
- GSR/EDA preprocessing notebook (NeuroKit2)

## Methods

### EEG Processing (MNE-Python)
- Band-pass filtering (1–45 Hz)
- Independent Component Analysis (ICA)
- Power Spectral Density (PSD)
- Frequency band extraction (Delta, Theta, Alpha, Beta, Gamma)

### GSR / EDA Processing (NeuroKit2)
- Signal cleaning and preprocessing
- Tonic and phasic decomposition
- Skin Conductance Response (SCR) detection
- Feature extraction (onset, peak, amplitude, latency)
- Event-based segmentation

## Installation

Install the required Python libraries:

```bash
pip install numpy pandas matplotlib mne neurokit2 scikit-learn
---

## Reproducibility

This repository supports the reproducibility of the preprocessing and feature extraction pipeline described in the associated publication.

## Contribution to Applied Psychology

This repository illustrates the potential of combining:

- Multichannel physiological signal recording  
- Machine Learning techniques (supervised and unsupervised)  

for the analysis of cognitive and emotional processes.

These approaches support:

- Pattern detection  
- Identification of inter-individual differences  
- Exploration of latent physiological profiles  

and are particularly relevant for applications in:

- Educational psychology  
- Clinical psychology  
- Personalised intervention design
