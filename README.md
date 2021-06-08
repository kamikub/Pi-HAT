# PiHat_Group18

This is Group 18's Git repo, containing all relevant documentation, schematic, PCB and simulation files for the design of our PiHat.

The PiHat we designed is a frequency tuner: the user will be able to select a desired sound-frequency or pitch to listen for via a series of push buttons and through the operation of an onboard microphone, instrumentation op-amp and code written to the Pi, the PiHat will indicate whether the desired frequency is acquired or not (using LED's and a buzzer).

This repo includes all schematics, PCB, simulations and other relevant documentation that went into the design of this PiHat. For the most part, this was a modular design process – our PiHat was broken down into three submodules: power supply, LED/buzzer interface and operational amplifier. These submodules were individually designed and simulated on LTSpice and KiCad. The integration of all three submodules was developed on KiCad by means of a final PCB design of the PiHat as a whole.
