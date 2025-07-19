# NuTremo
 A light-activated trèmolo circuit

CERN Open Hardware Licence Version 2 - Strongly Reciprocal

Copyright (C) [GolemMilk] [2025]

This source describes Open Hardware and is licensed under the CERN-OHL-S v2.
You may redistribute and modify this documentation and make products using it under the terms of the CERN-OHL-S v2.

You should have received a copy of the CERN-OHL-S v2 along with this source.
If not, you can obtain it at https://ohwr.org/cernohl

This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY,
INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE.
Please see the CERN-OHL-S v2 for applicable conditions.

This circuit gives the guitar a trèmolo effect. The JFET gate is energized according to the resistance value that varies with the flickering of the light.


Most of the parts are control units. The R7 constant is responsible for adjusting the trèmolo speed.

NE555P emits PWM, but is connected to the LED anode of U1 through an integrator and three LPFs. Adjusting U1 is the most difficult. I think that the most beautiful trèmolo can be achieved by placing a pink high-brightness LED and a CDs cell close together, handmade.

The C13 is set at 4700p for a mellow frequency for tremolo.
