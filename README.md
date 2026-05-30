# crop-disease-classification
Automated Crop Disease Classification Using Spectral Deep Learning
Team Members
Jana Abu-Jabal
Janna Alwekhyan
Ahmad Obeidat
Project Overview

This project classifies crop diseases using Hyperspectral (HS) and Multispectral (MS) images. Deep learning models based on ResNet18 were trained separately and then combined using a weighted ensemble approach.

Dataset

Beyond Visible Spectrum AI for Agriculture 2026

Classes:

Healthy
Rust Disease
Other Disease
Models
HS ResNet18 (125 spectral bands)
MS ResNet18 (5 spectral bands)
Weighted Ensemble
Results
HS Model Accuracy: 63.33%
MS Model Accuracy: 65.83%
Ensemble Accuracy: 70.83%
Requirements

Install dependencies:

pip install -r requirements.txt
Running the Project

Open and run the notebook:

jupyter notebook notebook47dcf5a362.ipynb

Run all cells sequentially.

Notes

The project demonstrates the use of multimodal spectral learning for crop disease classification and explores ensemble learning to improve prediction performance.
