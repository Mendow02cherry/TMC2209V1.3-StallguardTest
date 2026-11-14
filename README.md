Controller: Teensy4.1 (should work on Arduino)
Driver: TMC2209 v1.3 by BIGTREETECH
code: C++

-change/see pins in the code before testing
  >>also use the wiring_diagram_stallguard4test.svg for a correct setup

-Stallguard detection works, but reading the StallGuard value is not working yet

-if the motor is not starting properly, try to change the values under "ramp/state" in the code

-if you're having problems causing a proper stall, try change the SGTHRS and motorspeed values, during a testrun
