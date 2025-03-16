# MATLAB with Arduino
## Overview

Using an Arduino UNO for this demonstration required a little modification from that which the demo is set up for by default (a variant of the Arduino MEGA)




## Demonstration

Here is a [Project Demo Video](https://youtu.be/MjN_Oio2keA) of the project in operation

Here we see the basic Setup of the project, with a single pulse, being sent to pin 13 (the LED) of the Arduino:

![](media/pic2.png)

After building the project, we get a code generation report from MATLAB, which can be used to our advantage when we need to look into some of the details.

![](media/pic3.png)

When veiwing the Data Inspector, we can monitor the pulses:

![](media/pic.png)

These pulse values could be modified from the Simulink application, by modifying them in the Pulse Generator settings, even while the Arduino was still running.

## Development Environment

This project was developed using MATLAB, as well as several Add-Ons, such as:
- The MATLAB Support Package for Arduino Hardware
- MATLAB Coder
- Simulink
- Simulink Coder
- Simulink Support Package for Arduino Hardware

Additionally, this project was tested on the Arduino UNO

## Conclusion

MATLAB is a useful tool not just for simulating on a single device, but also for incorporating embedded devices into the process, allowing MATLAB to be an even more powerful tool.