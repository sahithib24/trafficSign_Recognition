# Traffic Sign Recognition using CNN and YOLOv8

## 📌 Overview

This project focuses on detecting and classifying traffic signs using a combination of **YOLOv8** (for detection) and a **Convolutional Neural Network (CNN)** (for classification). The model helps improve autonomous driving systems by accurately identifying road signs in real-time.

## 🚗 Problem Statement

* **Objective**: Build a pipeline for traffic sign detection and classification using the **GTSDB** and **GTSRB** datasets.
* **Detection**: Use **YOLOv8** to locate traffic signs within images.
* **Classification**: Use a **CNN** to classify each detected sign into one of 43 categories.
* **Goal**: Improve road safety and aid intelligent transportation systems through automated sign recognition.

## 🧠 Workflow

1. **Dataset Preparation**

   * Use **GTSDB** for detection tasks (with annotations).
   * Use **GTSRB** for training the classifier on labeled sign images.

2. **Detection with YOLOv8**

   * Trains on annotated images to detect traffic signs and draw bounding boxes.
   * High-speed and multi-sign detection capability.

3. **Classification with CNN**

   * Cropped images (from YOLO bounding boxes) are passed to the CNN.
   * The CNN assigns each image to one of 43 predefined traffic sign classes.

## 📊 Results

* **YOLOv8** achieves fast and accurate detection across various road conditions.
* **CNN Classifier** reaches high accuracy in classifying the detected signs into 43 categories.

## 🛠️ Requirements

* Python 3.x
* PyTorch
* OpenCV
* Ultralytics YOLOv8
* TensorFlow or Keras (for CNN)
