# Driver Drowsiness Detection

A deep learning project that explores driver drowsiness detection using computer vision. The project focuses on identifying two common signs of drowsiness: **eye closure** and **yawning**.

## Overview

The original dataset contains four classes:

* Open
* Closed
* yawn
* no_yawn

To simplify the problem, the dataset was reorganized into two separate binary classification tasks:

* **Eye Detection:** Open vs. Closed
* **Yawn Detection:** Yawn vs. No Yawn

The eye detection model was trained using **MobileNetV2** with transfer learning in PyTorch.

## Dataset

This project uses the **Drowsiness Dataset** by Dheeraj Perumandla on Kaggle:

https://www.kaggle.com/datasets/dheerajperumandla/drowsiness-dataset

## Notebook

Google Colab notebook:

https://colab.research.google.com/drive/1JIqLMiTPYOoIUghMfIpDVAzKzgF8AP2d?usp=sharing

## What I Implemented

* Reorganized the original dataset into two independent tasks.
* Split each dataset into training, validation, and testing sets (80% / 10% / 10%).
* Applied image preprocessing and data augmentation.
* Built data loaders using PyTorch.
* Fine-tuned a pretrained MobileNetV2 model.
* Used early stopping during training to reduce overfitting.
* Evaluated the model on a separate test set.

## Technologies

* Python
* PyTorch
* Torchvision
* Google Colab
* MobileNetV2 (Transfer Learning)

## Future Work

* Combine both models into a complete driver drowsiness detection system.
* Perform real-time detection using a webcam and OpenCV.

## Author

**Yousra Chahinez Aidaoui**
