# Alcohol-detection-and-Vehicle-locking-system
IOT Project

This project aimed at the exiting efforts of accidents prevention system developments, in hope of implementing it in the real life to increase roads safety.

The driver’s breath is analyzed by the sensor for the presence of alcohol. 
If  the system sensors senses the amount of alcohol consumed by the driver and if it the particular threshold level , then the system must send a command not to turn on the engine.

The MQ6 module is used to detect the alcohol particle in the atmosphere which has reasonable sensitivity range around two meters. 
The microcontroller converts the analog signal of the gas sensor into digital and checks with threshold limit and perform the action accordingly. 
A buzzer connected in the system gives alert signal.
Then the 1-channel relay gets cut off ,  if  the alcohol level reaches the threshold or greater than that. 
