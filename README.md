# Real-Time Image Classification using MobileNetV2

A real-time image classification application built using **Python, OpenCV, NumPy, and TensorFlow/Keras MobileNetV2**.

The application captures live video from the webcam and uses a pre-trained MobileNetV2 model trained on the **ImageNet dataset** to classify objects in real time.

---

## Project Overview

This project demonstrates how a pre-trained Convolutional Neural Network (CNN) can be used for real-time image classification.

The system:

1. Opens the computer webcam.
2. Captures live video frames.
3. Converts the frame from BGR to RGB.
4. Resizes the image to `224 × 224`.
5. Preprocesses the image for MobileNetV2.
6. Performs classification using a pre-trained MobileNetV2 model.
7. Displays the predicted class and confidence score directly on the video frame.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- OpenCV
- NumPy
- ImageNet

---

## Model

This project uses:

**MobileNetV2**

The model is loaded with pre-trained ImageNet weights:

```python
MobileNetV2(weights="imagenet")