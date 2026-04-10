# Fabric Quality Detection System

## Overview

This project presents a computer vision-based system for automated fabric defect detection using machine learning techniques.

Fabric inspection is a critical step in textile manufacturing, where defects directly impact product quality, cost, and production efficiency. Traditional manual inspection is slow, inconsistent, and prone to human error, making automated solutions essential.

This work focuses on building a robust perception system capable of identifying defects in fabric images under real-world conditions.

---

## Problem

Fabric defect detection involves identifying irregularities such as:

* Holes
* Stains
* Misweaves
* Pattern distortions

Challenges include:

* High variability in fabric textures
* Subtle and small defects
* Lighting and environmental variations

Manual inspection methods are inefficient and do not scale for industrial production.

---

## System Approach

### Pipeline

* Image preprocessing and normalization
* Feature extraction from fabric images
* Machine learning / deep learning-based classification
* Model evaluation using standard metrics

---

### Models

* Convolutional Neural Networks (CNNs) for visual feature extraction
* Classical ML models for baseline comparison

---

## Challenges

* Complex and repetitive fabric textures
* Small defect visibility
* Class imbalance between defective and non-defective samples
* Generalization across fabric types

---

## Results & Observations

* Deep learning models effectively capture texture-based anomalies
* Performance depends strongly on data quality and preprocessing

> Most limitations arise from variability in fabric patterns rather than model architecture.

This highlights that defect detection is fundamentally a **perception problem under real-world variability**.

---

## Visual Results

### Sample Detection Output

<img width="1539" height="1181" alt="image" src="https://github.com/user-attachments/assets/c4cab8a1-f689-4dec-981e-d004ad8d5ce5" />

---

## Tech Stack

* Python
* TensorFlow / PyTorch
* OpenCV
* NumPy, Pandas

---

## Repository Structure

```
├── notebooks/
├── src/
├── data/
├── results/
├── requirements.txt
└── README.md
```

---

## Research Context

Automated fabric defect detection is an active research area in industrial AI and computer vision, aiming to replace unreliable manual inspection with scalable, real-time systems.

Modern approaches leverage deep learning models such as CNNs to improve detection accuracy and robustness.

---

## Future Work

* Real-time defect detection on production lines
* Object detection models (YOLO / Faster R-CNN)
* Multi-class defect localization
* Deployment in industrial inspection systems

---

## Author

Raif Tanjim
