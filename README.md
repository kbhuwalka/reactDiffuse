#Reaction Diffusion Simulation
This is a basic simulation written for reaction-diffusion reaction.
##Usage
In order to run the simulation, open [index.html](index.html) in a JavaScript enabled browser. Changes to the parameters for the equation can be made in the [sketch.js](sketch.js) file. There parameters are detailed below:
-**dA**: Diffusion rate for A
-**dB**: Diffusion rate for B
-**feed**: Feed rate scaled by (1-A) to ensure A doesn't exceed 1.0
-**k**: Scaled Kill rate (subtracted from B) to ensure B doesn't fall below 0.0
-**time**: Change in time each iteration. All variables are scaled according to this.
##Example
Some typical values for the reaction parameters are given below:
-**dA**: 1.0
-**dB**: 0.5
-**feed**: 0.55
-**k**: 0.62
-**time**: 1.0
##License
The contents of this repository are shared under [MIT License](license.md)
