Detecting Correct Helmet Use with Deep Learning

This repository contains the implementation and analysis for the project “Detecting Correct Helmet Use with Deep Learning”, developed as part of the Deep Learning course at National Chengchi University (NCCU).
The goal of the project is to automatically determine whether a motorcycle rider is wearing a helmet correctly or incorrectly using image classification techniques. The work focuses on the half-face helmet subset of the HelmetML dataset (Patil et al., 2024), which represents the most commonly used helmet type in Taiwan.

📌 Project Overview

Motorcycle safety is a significant public concern in Taiwan. While helmet use is required by law, incorrect wearing—such as loose straps, poor coverage or improper positioning—remains common. This project explores whether deep learning can be used to assist road-safety monitoring by automatically recognizing correct versus incorrect helmet use from images.

Two modelling strategies are implemented:

1. Fine-Tuned MobileNetV2 (Transfer Learning)

A pretrained MobileNetV2 model is fine-tuned on the half-face HelmetML subset.
This model achieves 99.27% accuracy, confirming the strong performance of transfer learning for this task.

2. Custom CNN Models (Trained from Scratch)

Two convolutional neural networks were built and trained entirely from scratch:

Baseline CNN – a simple 3-layer architecture

Refined CNN – a deeper and more effective 4-layer architecture

The refined CNN achieves 93.16% accuracy, providing insight into what performance is achievable without ImageNet pretraining.
