# Simple EQ (w/JUCE)

This is a simple Equalizer (EQ) audio plugin built with the JUCE framework.
It was made following the next tutorial made by matkatmusic -> https://www.youtube.com/watch?v=i_Iq4_Kd7Rc&t=655s


## Features

- Equalization Controls: Low cut, Peak and High Cut. You can change the Slope for the cuts, Q for the Peak, and Gain for every control.
- Spectrum Analyzer: Visualize the frequency content of a signal. It provides a graphical representation of the amplitude of different frequency components within a given range.
- Bypass Buttons: To disable the effect of the equalization controls.

## Requirements

- [JUCE Framework](https://juce.com/) installed.
- MacOSX

## Build Instructions 

- Download the .zip file 
- You'll find the VTS3, AU and Standalone App in builds/MacOSX/build/debug
- Save the components in their respective folders in your Library/Audio/Plug-ins folder.
- Open it with your respective DAW.
- Enjoy!

## Known Issues

- Cannot use when connected to bluetooth to Galaxy Buds Live headphones: I suppose it's because the headphonse enter "call mode" and somehow bugs the app.

![Captura de Pantalla 2023-12-30 a la(s) 12 59 11](https://github.com/IsaacGC95/SimpleEQ/assets/155248312/69e0d02c-9b6f-4e9d-bef2-cf6821329494)
