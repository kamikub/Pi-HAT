Frequency Tuner
---------------------------------------------------------------------
The products intended use is as a frequency tuner allowing a user to 
tune their desired instrument in an efficient manner. It can also
be used as a vocal trainer when fine tuning pitch.

---------------------------------------------------------------------

Features and accesories
-The instrumentation amplifier will be a small uPiHat, conforming to
 the HAT basic requirements which are described next.
-A board can only be called a HAT if:
 1. It conforms to the basic add-on board requirements
 2. It has a valid ID EEPROM (including vendor info, GPIO map and 
    valid device tree information).
 3. It has a full size 40W GPIO connector.
 4. It follows the HAT mechanical specification
 5. It uses a GPIO connector that spaces the HAT at least 8mm from the
    Pi (i.e. uses spacers 8mm or larger)
 6. If back powering via the GPIO connector the HAT must be able to
    supply a minimum of 1.3A continuously to the Pi.

----------------------------------------------------------------------    

Description of main submodules

- Power regulator submodule responsible for powering the microphone and
  acting as one of the inputs to the amplifier submodule.
- LED, Buzzer, and Headers submodule acting as interfaces for the
  intended use. (LED's light up as confirmation, buzzer sounding off as
  confirmation, headers to coonnnect to PI)
- Amplifier responsible for amplifying microphone signal (to get a better
  reading of the information) before being passed to the ADC.

---------------------------------------------------------------------- 

Safety Warnings
- Since we are using the 5V GPIO header we need to make sure it is safe
  to do so.
- The input signal from the mic should not exceed 1V.
- Output of power regulator should not vary too much from 2V to protect
  microphone.
- Add a safety diode according to the design guide of the PI

----------------------------------------------------------------------

Technical Specifications
- Use 3 different coloured LED’s and a buzzer.
- A text file that can be edited on the Pi which will contain six
  frequencies that the user wants.
- Use 6 push buttons configured in a matrix.
- Buck switching regulator should output 2V given a 3V input.
- Weight of the microHAT should be taken into account when considering
  that the total weight should not exceed 10kg
- Make sure that after the integration of the subsystems, the board
  still conforms to the basic add-on board requirements

-----------------------------------------------------------------------

Contact Details
- ZLLJUL001@myuct.ac.za
- KMLSAL001@myuct.ac.za
- BTJLUK001@myuct.ac.za
