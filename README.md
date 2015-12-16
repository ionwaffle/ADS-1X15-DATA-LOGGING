# ADS-1X15-DATA-LOGGING
Data-logging - Originally built for strain sensor measurements. 

This software is currently working progress for the characterisation of sensor devices during a PhD project.

Built in Python to run on a Raspberry Pi, the code is centered around collecting and processing data from the ADC (Analogue to Digital Converter) ADS1015. The code can be easily modified to run with the 16 bit ADS1115 if required. 
For the code to work the ADS1x15 folder should be downloaded from https://github.com/adafruit/Adafruit-Raspberry-Pi-Python-Code and stored in the same folder as the data logging code. 

The backbone of the datalogging has been based on this tutorial http://openlabtools.eng.cam.ac.uk/Resources/Datalog/RPi_ADS1115/ and some example code within the tutorial. 

The aim of this project is to build a gui where the user can log the data of the material they are measuring, the force being applied to the material and then datalog the resistance measurements coming off the strain sensor. 
