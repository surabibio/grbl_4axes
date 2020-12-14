This is fork of Grbl for OpenPnP fromGRBL_VERSION "1.1h"GRBL_VERSION_BUILD "20190830"

-------------
Hardware
This runs on a plain Arduino Uno (with a atmega328p Device).
It supports a 4th  axis: the C_AXIS

C_Axis Step pin is Uno Digital Pin 12
C_Axis Direction pin is Uno Digital Pin 13

Spindle Enable is moved to Uno Analog Pin 3 - It can be used for Vacum Solenoid Valve On/Off
Spindle Direction and Variable Spindle Speed are not available

Z Axis Limit switch is moved to Uno Digital Pin 11

Hence with minimal hardware rewiring you should get your 3-Axis Desktop Mill that was running original Grbl to perform Pick And Place.

Supports all G-Codes as in Grbl v1.1 with:
 - Additiona Non-Command Word: C
 
-------------
This work is an integration of Bob Beattie's OpenPnP-Grbl with the Offical Grbl
While Bob Beattie's port runs on AtMega2560 this runs on Arduino Uno with Atmega328p

-------------
Grbl is an open-source project and fueled by the free-time of our intrepid administrators and altruistic users. If you'd like to donate, all proceeds will be used to help fund supporting hardware and testing equipment. Thank you!

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CUGXJHXA36BYW)
