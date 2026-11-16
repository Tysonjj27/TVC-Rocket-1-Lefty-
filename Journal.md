# TVC Gimbal/ Engine Progress Journal
# Phase 1
## 10/27/26

*Objective

Determine PWM limits for MG90S servos on wowki and begin CAD drafting for the inner gimbal ring for the bearings.

*Action and Data

-Coded a test script for the teensy through wowki using an esp32 as a standin for the Teensy 4.1 that will be used 
-Found stable PWM boundaries 'MIN_PULSE = 500', 'MAX_PULSe = 2400'. This allows a 180 deg sweep without jitter.
-Mapped servo sweeping to restrict physical deflection to +-8 deg to prevent linkages from binding together
-Started CAD work for inner rung, using a publicly available TVC gimbal mount as a reference

*Next steps:
-Finish the inner ring of the gimbal mount, start 3d printing, and establish tolerances for printing
-Integrate +-8deg servo limits onto actual teensy 4.1 when parts arrive
-aim for static testing around 12/1/26

## 11/7/26

*Updates
-Got access to an ender 3 pro 3d printer, calibrated printer and printed bearing test for TVC mount to find printing tolerances 
-Got all materials for TVC gimbal mount/engine.

*Objective
-Finish Cad drafts for gimbal mount and start printing first renditions of gimbal

*Next Steps
- Start work on coding microcontroller/IMU for telemetry, datalogging and PID controller for TVC control to be stable
- Finish gimbal mount and have it printed by next week (11/15/26)


##11/16/26

*Updates 
-Printed a motor slip ring test and a dummy motor to test tolerances before modeling final gimbal
-Did not finish gimbal mount by this week, will try to rush it for middle of next week (11/24/26)

*Objective
-Learn how to program on a teensy 4.1 microcontroller 
-Model and Print TVC gimbal

*Next steps
-Still aiming for staic testing in december
-print gimbal parts throughout week
