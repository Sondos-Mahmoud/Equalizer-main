# Signal Equalizer Desktop Application
## Team 4

1. **Sondos Mahmoud**
2. **Fatma Ehab**
3. **Mai Mohamed**
4. **Noura Osama**
## Overview

Signal Equalizer is a Python desktop application built using PyQt5 that serves as a fundamental tool in the music and speech industry. It finds applications in various fields, including biomedical use for hearing aid abnormalities detection.

## Description

The application enables users to open a signal and adjust the magnitude of specific frequency components using sliders, subsequently reconstructing the modified signal. It offers multiple working modes:

1. **Uniform Range Mode:**
   - Divides the total frequency range of the input signal into 10 equal ranges, each controlled by a dedicated slider in the UI.

2. **Musical Instruments Mode:**
   - Allows each slider to control the magnitude of a specific musical instrument in the signal.

3. **Animal Sounds Mode:**
   - Permits each slider to control the magnitude of specific animal sounds in a mixture of frequencies.

4. **ECG Abnormalities Mode:**
   - Empowers each slider to control the magnitude of arrhythmia components in the input signal.

In addition, the application employs four multiplication/smoothing windows (Rectangle, Hamming, Hanning, Gaussian) when multiplying the frequency range with the corresponding slider value.

Users can easily switch between modes through a combobox in the UI.

## Features

- **Cine Signal Viewers:**
  - Two linked cine signal viewers for input and output signals.
  - Full set of functionality panel (play/stop/pause/speed-control/zoom/pan/reset) respecting all boundary conditions.
  - Synchronous playback of signals in time.

- **Spectrograms:**
  - Two spectrograms for input and output signals.
  - Real-time reflection of changes made through equalizer sliders.
  - Option to toggle show/hide of the spectrograms.



## Getting Started

To run the application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url.git
   ```

2. Run the application:
   ```bash
   python equalizer.py
   ```
