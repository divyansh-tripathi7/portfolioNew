---
title: "Audio CLeaner"
description: "Removes noise from audio using signal processing"
dateString: Sept 2022
draft: false
tags: [audio cleaner, Fourier Transform, smoothing filter, spectrogram, digital signal processing, SciPy, Spectral Gating]
showToc: false
weight: 60
cover:
    image: "projects/audioCLeaner/soundCLeaner.jpeg"
--- 
### 🔗 [GitHub](https://github.com/divyansh-tripathi7/SpeechProcessing)
<!-- ### 🔗 [Blog Post](../../blog/face-landmarks-detection) -->

## Description

The audio cleaner project is designed to remove noise from audio recordings using the **Fourier Transform** and a s**moothing filter**. The project uses a technique called **spectral gating** to identify and remove noise from the audio recording.

First, the audio recording is transformed into the frequency domain using the Fourier Transform. The resulting frequency representation is known as the **spectrogram**. The spectrogram is then analyzed to identify the presence of noise.

A **noise mask**is created using the spectrogram, which highlights the frequency components that are solely attributed to the noise. A smoothing filter is then applied to the audio recording using this noise mask, which removes the frequency components of the noise and recovers the original audio signal.

The project is implemented using digital signal processing techniques and libraries, such as **NumPy, SciPy,Librosa and Matplotlib**. The user can upload an audio file to the system and apply the noise removal algorithm to produce a cleaned version of the original audio.

