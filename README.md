# Communication Made Possible: A Comprehensive Web Application for Two-Way Sign Language Conversion

> Published in IARJSET (International Advanced Research Journal in Science, Engineering and Technology)  
> Volume 11, Issue 4, April 2024  
> Authors:Prerana P, Priyaanca J, Puneetha M Deshmuk, Nithyashree M, Divyashree M

---

## About

This project presents a **Two-Way Sign Language Converter Web Application (TWSLCW)** — a real-time, bidirectional communication system that bridges the gap between sign language users and non-signers.

Traditional communication tools for the deaf and hard-of-hearing community rely on human interpreters or pre-written data, which are slow, expensive, and often inaccurate. This system addresses that by using state-of-the-art machine learning to enable instant, automated translation in both directions.

---

## How It Works

The application supports two-way conversion:

**Sign Language → Text**
- Webcam captures hand gestures in real time
- Video frames are converted to images and processed
- A CNN model trained on sign language datasets classifies the gesture
- Output is displayed as text or converted to speech

**Text / Audio → Sign Language**
- User types text or speaks via microphone
- Speech is converted to text using ASR (Automatic Speech Recognition)
- Text is tokenized and mapped to corresponding sign language gestures
- Animated gesture output is displayed on screen

---

## Architecture

The system is built around three core deep learning components:

- **3D-CNN** — extracts spatiotemporal features from video gesture sequences
- **LSTM** — models temporal relationships across gesture frames
- **SoftMax classifier** — outputs gesture class probabilities

---

## Features

- Real-time gesture recognition via webcam
- Audio input via microphone with speech-to-text conversion
- Animated sign language output for text/audio inputs
- User authentication (Sign Up / Login)
- Clean, accessible web interface
- Support for both individual alphabets and common words

---

## Dataset

Two datasets were used for training:

- **Alphabet dataset** — labeled hand gesture images for A–Z
- **Word dataset** — gesture clips for common words including: Baby, Brother, Friend, Help, House, Like, Love, Make, and more

Training involved separating non-overlapping train/test splits to prevent overfitting, with diverse gesture samples across multiple classes.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Machine Learning | CNN, RNN (LSTM), SoftMax |
| Computer Vision | OpenCV, MediaPipe |
| Speech Recognition | ASR (Web Speech API) |
| Frontend | HTML, CSS, JavaScript |
| Backend | Python |
| Deep Learning Framework | PyTorch |

---

## Publication

This work was peer-reviewed and published in **IARJSET** — indexed by Google Scholar, Mendeley, Crossref, Scilit, and UGC approved (2017).

**Cite this work:**
