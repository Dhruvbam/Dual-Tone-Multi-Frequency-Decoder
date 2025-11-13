
# Dual Tone Multi Frequency (DTMF) Decoder

![Project Image](https://github.com/Dhruvbam/Dual-Tone-Multi-Frequency-Decoder/blob/main/Images/dtmf.jpg)

The DTMF Decoder is a Python based program that explores how to interpret dual-tone multi-frequency (DTMF) audio signals, the foundation of touch tone telephony and modern telecom signaling, transforming dial tones into their corresponding digits and symbols. Developed for the Computational Thinking & Data Science course, this project walks users through the entire digital audio pipeline: synthesizing tones, converting analog audio to digital and performing detailed frequency analysis, all developed in Python using Jupyter. By applying Fast Fourier Transform (FFT) and using advanced Python libraries like NumPy, pandas, and SciPy, the decoder reads audio as WAV files and decodes each key press’s unique dual tone frequencies, accurately mapping telephone keypad tones to digits (0-9, *, #). Employing advanced Digital Signal Processing (DSP) and robust noise filtering techniques ensures 100% accuracy even in the presence of background noise. This project demonstrates technical depth in advanced scientific Python workflows and a hands-on approach to modern telecom signaling, visually driven experimentation and comprehensive data science.

## Features & Technical Details

- **Real World Audio Decoding:** Accurately decodes telephone keypad dial tones from WAV files and maps it to digits and symbols (0-9, *, #).
- **Fast Fourier Transform (FFT):** Utilizes Fast Fourier Transform to analyze frequency spectra for each audio segment, matching detected tones to DTMF standards.
- **Noise Filtering:** Implements advanced digital signal processing and noise filtering techniques to reliably identify tones, even in noisy recordings.
- **Audio Pipeline:** Covers audio synthesis, analog to digital conversion, detailed frequency analysis, and digit mapping.
- **Hands On Jupyter Workflow:** Step by step code in Python Notebooks encourages experimentation and interactive learning.
- **Data Science Focus:** Integrates visualizations, robust data handling and reinforcing experimentation and analytical debugging in a data science throughout the project.

## Built With

- <a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" width="36" height="36" alt="Python" /></a> **Python**: Primary language for audio processing workflows.
- <a href="https://numpy.org/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" width="36" height="36" alt="NumPy" /></a> **NumPy**: For FFT implementation and numerical operations.
- <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" width="36" height="36" alt="pandas" /></a> **pandas**: For data manipulation and table handling.
- <a href="https://scipy.org/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" width="36" height="36" alt="SciPy" /></a> **SciPy**: For low-level digital signal processing and filtering.
- <a href="https://jupyter.org/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" width="36" height="36" alt="Jupyter" /></a> **Jupyter Notebooks**: Interactive development and step-by-step demonstration.


## Installation
To get a local copy up and running, follow these steps:
1. Clone the repo
   ```sh
   git clone https://github.com/Dhruvbam/Dual-Tone-Multi-Frequency-Decoder
   ```
2. Ensure you have Python and the necessary libraries installed.
3. Run the Jupyter Notebooks (`DTMF - Part 1 - Final.ipynb` through `DTMF - Part 4 - Final.ipynb`) in sequence to experience the encoding, decoding, and analysis process.

## Screenshots/Demo
![Screenshots](https://github.com/Dhruvbam/Dual-Tone-Multi-Frequency-Decoder/blob/main/Images/ss.png).
![Screenshots](https://github.com/Dhruvbam/Dual-Tone-Multi-Frequency-Decoder/blob/main/Images/ss2.png)
