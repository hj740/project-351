# project-351
Project 351 is a project repository for the GNU Radio Companion Problem Set. 

## Software and Installation
This project was created using GNU radio software. This is a free software development toolkit that can be downloaded here: (https://github.com/ryanvolz/radioconda?tab=readme-ov-file#Download:~:text=MacOSX%2Darm64.pkg-,Windows,radioconda%2DWindows%2Dx86_64.exe,-Install)

## Authors and Acknowledgments
This project was completed by Hannah Driscoll and Jacob Hyman. We would like to acknowledge Kristina Collins and David Kazdan for giving us a good grade.

### Problem Description
This project aims to simulate the Phase Lab previously completed for the class. The aim is that the user can vary the amplitude, frequency, and phase of a signal while seeing the time domain and phasor view in real time. 

### Problem Approach, Difficulties, and Solutions
Our initial approach was to use the Signal Source connected to the GUI Time Sink block with a float signal to see the output. Then, variables were created to adjust the amplitude, frequency, and phase. We then changed the source to output a complex signal for the GUI Constellation Sink to correctly output the phase view. Due to this complex signal, we used a Complex to Float block to change the Signal Source's output to read the cosine signal with the GUI Time Sink. 

## Usage
This project when run, will display two graphs. The top display is the Time Domain representation of the signal, and the bottom display is the phase view representation of the signal. There will be three sliders to affect the amplitude, frequency, and phase of the signal. These parameters can be adjusted to whatever the user wants to see. 

### Visuals
Here are some visual images of the project in use with diffferent parameters chosen:
