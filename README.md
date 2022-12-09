# Mainsail
Repository for my Mainsail config's.

This repository serves for personal use, as well as anyone wanting to configure their Klipper+Mainsail config.
I'm using PrusaSlicer, so initial gcodes are for that slicer as well.

PrusaSlicer *Start G-code*:
'M109 S0
M190 S0
start_print EXTRUDER_TEMP={first_layer_temperature[initial_extruder]} BED_TEMP={first_layer_bed_temperature[initial_extruder]}'
