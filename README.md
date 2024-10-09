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
![image](https://github.com/user-attachments/assets/2821cd6b-f5be-410f-9f09-1c45095d1aed)

2. **Musical Instruments Mode:**
   - Allows each slider to control the magnitude of a specific musical instrument in the signal.
     ![image](https://github.com/user-attachments/assets/32b92f42-75cd-4e1a-8528-fa6f2e4b0155)


3. **Animal Sounds Mode:**
   - Permits each slider to control the magnitude of specific animal sounds in a mixture of frequencies.
   ![image](https://github.com/user-attachments/assets/3f907c9b-2962-40e3-98df-f213fa194442)


4. **ECG Abnormalities Mode:**
   - Empowers each slider to control the magnitude of arrhythmia components in the input signal.
   ![image](https://github.com/user-attachments/assets/89180631-28f8-4a74-947f-0f5e58d3e0e0)


In addition, the application employs four multiplication/smoothing windows (Rectangle, Hamming, Hanning, Gaussian) when multiplying the frequency range with the corresponding slider value.
![image](https://github.com/user-attachments/assets/623814fc-15ce-4a70-bc28-10640e057041)


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
