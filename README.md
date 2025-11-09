# 🎧 Deep Learning–Based Emotion Detection from Speech  
### _OpenCV | ResNet | NumPy | Audio Augmentation | IoT Integration_  

> **Duration:** Jan – March 2025  
> **Focus:** Detecting and classifying **infant emotions** (hunger, discomfort, belly pain, tiredness) using **audio-based deep learning models**.

---

## 🧠 Project Overview

This project explores the use of **deep learning for emotion recognition** from **speech and cry audio data**.  
It focuses on understanding infant emotions through sound patterns, using **Convolutional Neural Networks (CNNs)** built on top of **ResNet architectures**.  

The end goal was to integrate this model into an **IoT-based smart cradle system** that can automatically respond to a baby’s needs — providing alerts and actions such as rocking or playing soothing sounds.

---

## 🚀 Key Features

- 🎯 **CNN-based deep learning model** trained to classify infant emotions such as _hunger_, _discomfort_, _belly pain_, and _tiredness_.
- 🔊 **Custom audio augmentation** including:
  - Time masking  
  - Frequency masking  
  - Rotation (time–frequency domain)
- 🧩 **Improved generalization** across diverse cry patterns by augmenting the dataset with realistic variability.
- 🌐 **Integration with IoT smart cradle system** that:
  - Detects emotion in real-time  
  - Sends **parental alerts**  
  - Triggers **automated cradle responses** based on detected emotional state
- 📈 Achieved **high classification accuracy** on custom-curated datasets.

---

## 🧰 Tech Stack

| Component | Technology Used |
|------------|----------------|
| **Programming Language** | Python |
| **Deep Learning Framework** | TensorFlow / Keras |
| **Audio Processing** | Librosa, NumPy |
| **Computer Vision Integration** | OpenCV |
| **Model Architecture** | Custom CNN based on ResNet |
---

## 🧪 Model Workflow
### Data Pipeline
1. **Collect** cry audio samples from open-source infant sound datasets.  
2. **Preprocess** signals (trimming, normalization, noise removal).  
3. **Extract features** (Mel-Frequency Cepstral Coefficients - MFCCs).  
4. **Apply augmentations** (time/frequency masking, rotations).  
5. **Train CNN model** and evaluate with confusion matrix, accuracy, and F1-score metrics.  
