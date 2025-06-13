# driver_fatigue_detection
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tanusree03/driver_fatigue_detection/blob/main/driver_fatigue_detection.ipynb)

Multimodal deep learning model for driver fatigue detection using eye images (ViT), EEG, and HRV data. Uses late fusion with a meta-classifier to combine visual and physiological features. Built in PyTorch and Colab for real-time fatigue monitoring.

## Overview
This project aims to detect driver fatigue using a combination of visual and physiological data sources. A late fusion strategy is adopted to integrate outputs from multiple models handling:
- Eye images using Vision Transformer (ViT)
- EEG signals representing brain activity
- HRV (Heart Rate Variability) metrics indicating stress levels
The fused output is classified using a meta-model to improve overall prediction performance.

## 🧠 Technologies Used
- Python, Google Colab
- PyTorch
- Scikit-learn
- NumPy, Matplotlib

## 📊 Dataset
This project uses multimodal data including:
- Eye images: [NTHU Drowsy Driver Detection Dataset](https://www.kaggle.com/datasets/banudeep/nthuddd2)
- EEG and HRV data: The EEG and heart rate variability datasets used in this project were obtained from publicly available research repositories. Due to uncertainty about the original source names, direct links have not been provided.

> Note: If you are replicating this work, you may use any similar EEG or HRV dataset publicly available on platforms like Figshare, PhysioNet, or Kaggle.
