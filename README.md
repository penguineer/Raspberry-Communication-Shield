# Raspberry-Communication-Shield
A communication shield for the Raspberry Pi+

Idea: Create a shield for the Raspberry Pi+ that contains common channels such as
* I2C
* RS485
* 433 MHz wireless
* GPIO Port Multiplexer

The project contains of two main parts: The hardware shield and the software/driver for the RPi to efficiently use the shield.

The shield should be modular, i.e. not all areas have to be populated if a certain operation is not needed. However, the PCB design is common, allowing for "mass production" (e.g. Oshpark produces in quantities of three).
