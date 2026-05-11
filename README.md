# Two-Way Sign Language Translation System

## Overview

This project presents a real-time, two-way sign language communication system designed to bridge the gap between sign language users and non-signers. The system leverages machine learning, computer vision, and speech processing to enable seamless translation between gestures, text, and audio.

This work is based on a **published research paper** in IARJSET.

## Publication

* **Journal:** International Advanced Research Journal in Science, Engineering and Technology (IARJSET)
* **DOI:** 10.17148/IARJSET.2024.11xx
* **Title:** Communication Made Possible: A Comprehensive Web Application for Two-Way Sign Language Conversion

## Key Features

* 🔁 Two-way translation:

  * Sign Language → Text
  * Text → Sign Language
  * Speech → Text
  * Text → Speech
* 🎯 Real-time gesture recognition using computer vision
* 🧠 Deep learning-based prediction using CNN + LSTM
* 🎤 Audio processing with speech-to-text and text-to-speech
* 🌐 User-friendly web interface for accessibility

## System Architecture

The system is composed of multiple modules:

### 1. Gesture Recognition Module

* Uses CNN-based models to detect and classify hand gestures
* Extracts spatial and temporal features from video input

### 2. Text-to-Sign Module

* Converts input text into sign representations
* Uses sequence modeling techniques (RNN/LSTM)

### 3. Speech Processing Module

* Converts speech to text using ASR
* Converts text to speech using TTS

### 4. Integration Layer

* Connects all modules into a unified web-based application

## Tech Stack

* **Languages:** Python, JavaScript
* **ML/DL:** CNN, RNN, LSTM
* **Libraries:** OpenCV, TensorFlow / PyTorch
* **Concepts:** Computer Vision, NLP, Speech Processing

## Dataset

* Custom dataset of sign language gestures (alphabets + words)
* Preprocessed using image normalization and feature extraction techniques

## Results

* Achieved high accuracy in gesture recognition tasks
* Successfully demonstrated real-time translation between modalities
* Improved communication accessibility for users in testing scenarios

## Demo / Screenshots

(Add your screenshots here)

## Future Improvements

* Expand dataset for more languages and gestures
* Improve model accuracy with transformer-based architectures
* Deploy as a scalable cloud-based service

## Author

Prerana Puttaswamy
