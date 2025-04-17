# project-351
Project 351 is a project repository for the GNU Radio Companion Problem Set. 

## Software and Installation
This project was created using GNU radio software. This is a free software development toolkit that can be downloaded here: (https://github.com/ryanvolz/radioconda?tab=readme-ov-file#Download:~:text=MacOSX%2Darm64.pkg-,Windows,radioconda%2DWindows%2Dx86_64.exe,-Install)

## Authors and Acknowledgments
This project was completed by Hannah Driscoll and Jacob Hyman. We would like to acknowledge Kristina Collins and David Kazdan for giving us a good grade.

## Problem Description
This project aims to simulate the Phase Lab previously completed for the class. The Phase Lab's main goal is to familiarize the user with signal phase and phase differences between signals. This project aimed to allow the user to vary the amplitude, frequency, and phase of a signal while seeing the time domain and phasor view in real time. 

### Problem Approach, Difficulties, and Solutions
Our initial approach was to use the Signal Source connected to the GUI Time Sink block with a float signal to see the output. Then, variables were created to adjust the amplitude, frequency, and phase. We then changed the source to output a complex signal for the GUI Constellation Sink to correctly output the phase view. Due to this complex signal, we used a Complex to Float block to change the Signal Source's output to read the cosine signal with the GUI Time Sink. 

## Usage
This project when run, will display two graphs. The top display is the Time Domain representation of the signal, and the bottom display is the phase view representation of the signal. There will be three sliders to affect the amplitude, frequency, and phase of the signal. These parameters can be adjusted to whatever the user wants to see. 

### Visuals
Here are some visual images of the project in use with diffferent parameters chosen:

This is our flow diagram:
![image](https://github.com/user-attachments/assets/1c6eec6e-d539-47c9-89b7-c2b4601f0df5)

This is the graphs of the time and phase domain for where the frequency is set to 57.3 Hz, the Phase is set to zero, and the Amplitude is set to one:
![Screenshot 2025-04-16 235021](https://github.com/user-attachments/assets/f9be1135-87c2-4b71-9760-dcdde1406f17)


In this graph the frequency is set to zero, the amplitude is set to one, and the phase is set to three. You can see that the phase dictates where the dot is located.
![image (2)](https://github.com/user-attachments/assets/70ea3228-901f-4a8e-adf4-a622fd14d765)

Moving the sliders allows you to adjust the phase, frequency, and amplitude to recreate these graphs

