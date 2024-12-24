---
title: "Audio Cleaner"
description: "A robust audio noise reduction tool using advanced signal processing techniques for clear, high-quality audio."
dateString: Sept 2022
draft: false
tags: [Data Analysis, audio cleaner, signal processing, Fourier Transform, noise removal, SciPy, Spectral Gating, digital signal processing]
showToc: false
weight: 60
cover:
    image: "projects/audioCLeaner/soundCLeaner.jpeg"
---

### 🔗 [View GitHub Repository](https://github.com/divyansh-tripathi7/SpeechProcessing)

## Project Overview

The **Audio Cleaner** is a powerful tool designed to enhance audio quality by removing unwanted noise. Using advanced **digital signal processing** (DSP) techniques, this project applies **Fourier Transform** and **spectral gating** to effectively identify and remove noise from audio recordings.

### Key Features:
- **Noise Removal**: Utilizes Fourier Transform to convert audio into the frequency domain, making it easier to isolate and remove noise.
- **Spectral Gating**: Identifies noise components in the spectrogram and applies a smoothing filter to remove them, preserving the original audio signal.
- **Customizable Output**: Users can upload any audio file, and the tool will process the file, offering a clean, noise-free version of the original recording.
- **Real-Time Processing**: The algorithm works efficiently to ensure minimal delay in processing, offering near real-time noise removal.
  
### Use Cases:
- **Podcast Creators**: Clean up background noise in podcasts for professional-quality audio.
- **Audio Engineers**: Provide a tool for pre-processing audio recordings, making it easier to work with clean data.
- **Content Creators**: Enhance the quality of recordings for videos, presentations, and voiceovers.
- **Research**: Clean up recorded data for speech-to-text applications or audio analysis in machine learning models.

### Technologies Used:
- **Fourier Transform**: For transforming audio into the frequency domain.
- **Spectral Gating & Smoothing Filter**: For removing unwanted noise while preserving the desired audio signal.
- **SciPy, Librosa, Matplotlib**: For processing and visualizing the audio data, along with implementing the noise reduction algorithms.

This project leverages powerful DSP techniques to provide an essential tool for anyone looking to enhance audio quality, whether it's for podcasts, recordings, or research.

### Category: **GenAI | Data Analysis**
