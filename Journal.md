# TVC Gimbal Dev Journal

## 10/27/26

*Objective

Determine PWM limits for MG90S servos on wowki and begin CAD drafting for the inner gimbal ring for the bearings.

*Action and Data

Coded a test script for the teensy through wowki using an esp32 as a standin for the Teensy 4.1 that will be used 
Found stable PWM boundaries 'MIN_PULSE = 500', 'MAX_PULSe = 2400'. This allows a 180 deg sweep without jitter.
Mapped servo sweeping to restrict physical deflection to +-8 deg to prevent linkages from binding together
Started CAD work for inner rung, using a publicly available TVC gimbal mount as a reference

*Next steps:
Finish the inner ring of the gimbal mount, start 3d printing, and establish tolerances for printing
Integrate +-8deg servo limits onto actual teensy 4.1 when parts arrive
aim for static testing around 12/1/26
