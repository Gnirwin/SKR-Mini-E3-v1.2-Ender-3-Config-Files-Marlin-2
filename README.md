# Ender-3/SKR Mini E3 v1.2 Config Files

This repository contains Marlin custom config files for Creality Ender 3 printers with a BIGTREETECH SKR Mini E3 v1.2 motherboard.

##Installation guide for Printers with BL Touch

1. Get the latest Marlin bugfix-2.0.x from the BIGTREETECH github here: https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3.
2. Copy files from folder **\Marlin** in this repository to the folder **\Marlin** in your firmware root folder.
3. Compile the software and flash the board.

##The changes made to the Configuration.h file:

'#define Z_MIN_PROBE_USES_Z_MIN_ENDSTOP_PIN'

#define BLTOUCH

#define NOZZLE_TO_PROBE_OFFSET { -40, -8.6, 0 } 

#define XY_PROBE_SPEED 10000

#define AUTO_BED_LEVELING_BILINEAR

 //#define MIN_SOFTWARE_ENDSTOP_Z

#define Z_SAFE_HOMING

#define NUM_SERVOS 1




##The changes made to the Configuration.h file:

#define BLTOUCH_DELAY 500
#define BABYSTEP_MULTIPLICATOR  10


