![alt text](https://github.com/Dhruvbam/Dual-Tone-Multi-Frequency-Decoder/blob/main/dtmf.jpg)
# Dual Tone Multi-Frequency (DTMF) Decoder

## Overview
This project presents a Dual Tone Multi-Frequency (DTMF) Decoder developed in Python. Aimed at decoding telephone keypad digits, our team of three utilized data science and machine learning libraries alongside Python scripting to analyze audio files. By employing Fast Fourier Transform (FFT), we accurately decoded WAV format tones into their corresponding numeric digits.

## Features
- **DTMF Encoding & Decoding**: Generates frequencies for dial tones and decodes them back to digits.
- **Audio File Processing**: Analyzes WAV audio files to slice each tone and decode digits.
- **FFT Implementation**: Utilizes FFT to match audio frequencies with predefined number database.

## Technologies Used
- Python for scripting and automation.
- Libraries: NumPy for FFT, pandas for data manipulation, and SciPy for signal processing.

## Getting Started
To run this project:
1. Clone the repository.
2. Ensure you have Python and necessary libraries installed.
3. Run the Jupyter Notebooks (`DTMF - Part 1 - Final.ipynb` through `DTMF - Part 4 - Final.ipynb`) in sequence to see the encoding, decoding, and analysis process.

## How It Works
The decoder takes an audio file, slices each tone, and uses FFT to compare frequencies against a database, identifying the corresponding digit for each tone sequence.
