# voice-fingerprint-verification
# 🎙️ Interactive Voice Fingerprint Verification System

An end-to-end, lightweight speaker verification prototype optimized for zero-dependency cloud execution. This system extracts unique acoustic footprints from audio waveforms and calculates identity alignment percentages mathematically.

## 🚀 Live Interactive Deployment
You can run and test this software live in your browser without any local installation:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/himangshuborah0001/voice-fingerprint-verification/blob/main/Ai_voice_identification_system.ipynb)

*(Click the badge above to open the interactive UI form directly on your device)*

## 🧠 System Architecture & Methodology
The project bypasses heavy neural framework layers to eliminate runtime overhead and platform dependency mismatches, utilizing a robust mathematical approach:

1. **Audio Normalization:** Raw waveforms are ingested and stabilized via `librosa` at a uniform 16kHz sampling rate to eliminate microphone hardware variances.
2. **Feature Extraction:** Isolates 13 Mel-Frequency Cepstral Coefficients (MFCCs) to extract physical vocal cord and nasal resonance frequencies, flattening time-series frames into a static 1D feature vector array.
3. **Identity Alignment Matrix:** Computes a 1-to-1 matching confidence matrix using Cosine Similarity metrics via `scikit-learn`.

## 🛠️ Core Technologies Used
* **Language:** Python 3.12
* **Signal Processing:** Librosa
* **Vector Math & Matrix Alignment:** Scikit-Learn, NumPy
* **Interface & Cloud Runtime:** Google Colab Forms Architecture

Developed by **Himangshu Borah** as a technical internship evaluation project.

