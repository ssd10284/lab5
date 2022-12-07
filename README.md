# Sensor Lab 5
This labs goal was to connect and read from sensors using the MSP430FR2355. I chose to use the built in Temperature Sensor and built in Light Sensor as they were already connected and easy to interface with.

For the first part of the lab the Temperature Sensor was read from and used. For the second part of the lab the temperature sensor and the light sensor was used.


## Install and Run
To run this code, you will need a matching MSP430FR2355 Launchpad which is sold by TI (Texas Instruments). Then you will need to use an C IDE of your choice. MSP430 is directly supported by the CCS IDE or Code Composer Studio, so this is what was used to develop the programs. Simply add the code to a project, and upload to the board. 

Once the code is uploaded use the debugger to graph the two variables that hold the sensor values.

## References
Temp code is based off the temperature sensor adc code given with the MSP430.
Light code is based off the light sensor adc code given with the MSP430.
