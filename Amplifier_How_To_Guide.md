Author: Luke Baatjes
Date: 10 June 2021

--------------------------------------------------------------------------------------------------------------

How to connect and use subsystem 3, the amplifier stage of the micro PIHat.

This How-to guide serves to simplify the users task in implementing the amplifier stage in the microPIHat.
The guide will be short as the amplifier is simple to use and the steps are easy to implement.
This guide applies to the user (mainly musicians who need help in tuning their instruments or correcting
pitch while doing vocal training).
It is important that the user at least understands what an amplifier does in order to fully understand the
context of the How-to.

All subsystems are directly interconnected and have no connections via connector pins therefore there is
no individual need to connect one subsystem to the next.
The integration of all 3 subsystems simplifies the use of the microPIHat and therefore requires no
extra help from the user in the PIHat's primary use case.

For the PIHat's secondary use case where the gain of the amplifer can be changed to produce a desired
output value, the following simple steps apply:

Step 1:
	If the user should notice that the tuner does not produce the optimum sound for the note after
	tuning then the user should turn the potentiometer (on the amplifier) anti-clockwise to decrease
	the gain resistor and therefore increase the gain of the amplifier.

Step 2:
	Repeat Step 1 if necessary or if necessary turn the potentiometer clockwise accordingly.
