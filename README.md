# Gesture-Recognition-with-Leap-Motoion

## Project Overview

This project is part of my individual project submitted at Newcastle University for the academic year 2023-2024. The primary goal of this project is to build a real-time gesture recognition system based on Leap Motion, utilizing a range of technologies for efficient and accurate gesture detection and recognition. Additionally, the system is deployed on a Raspberry Pi and includes functionality for uploading data to an IoT platform.

## Tech Stack

The main technologies used in this project include:

- **C++**: Core programming language for performance-critical sections of the project.
- **Python**: For rapid prototyping, data processing, and machine learning integration.
- **Machine Learning**: Algorithms and models for gesture recognition.

Additional tools and frameworks:

- **Computer Vision Libraries**: 
  - **OpenCV**: For image processing and tracking hand gestures.
- **Deep Learning Frameworks**: 
  - **TensorFlow** or **PyTorch**: For training and deploying deep learning models.
- **Data Management**: 
  - **Pandas**: For managing and processing large datasets.
  - **SQLite**: For lightweight, structured data storage.
- **Signal Processing Tools**:
  - **SciPy**: For signal filtering and noise reduction to enhance gesture signal accuracy.
- **Real-Time Processing Frameworks**: 
  - **ROS (Robot Operating System)**: To support real-time data handling from Leap Motion.
- **Leap Motion SDK**: Essential for accessing and interpreting data streams from the Leap Motion sensor.

### Raspberry Pi and IoT Integration

- **Raspberry Pi**: The entire system is deployed on a Raspberry Pi, enabling local data recording, model training, and real-time predictions.
- **IoT Platform Integration**: The system includes functionality for uploading data to an IoT platform for remote monitoring and analysis.
- **Edge Computing**: Local model training and prediction on the Raspberry Pi allow for reduced latency and increased data privacy.

These technologies collectively enable the development of a robust, responsive, and scalable gesture recognition system with IoT capabilities.
