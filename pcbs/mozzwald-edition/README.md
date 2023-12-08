# A8PicoCart mozzwald edition

# PCB

The addition of a schottky diode and two MOSFETS allows the Pi Pico to be connected to USB while still connected to the Atari. The Pi Pico "Lite" boards already have a schottky diode to prevent back powering the USB port and this additional schottkey diode prevents the USB port from back powering the Atari. Two N-MOSFETS are used on RD4 and RD5 to prevent the Pico from powering those lines if the Atari is turned off. I have rotated the Pi Pico so the USB-C port and Reset button are at the top for easy access. This PCB was designed with [Diptrace 3.3.1.3](https://diptrace.com). ENIG plating is recommended for the PCB as it prevents corrosion to the exposed cart pins.

# 3D

The case is designed to be printed with an independent dual-extruder 3D printer (IDEX) in two colors. The logo background is a different color than the rest of the case to make it stand out. A button was added to the back which activates the *BOOTSEL* button for easy firmware upgrades.

Also included is a 3D printable jig to hold the PCB for sanding which allows you to add a bevel on the cart edge. The jig will give you a 45 degree angle and the PCB hangs over the edge just enough so you can slide it back and forth on a piece of sand paper sitting on a flat surface giving you an even edge. The jig can be used on a cart with or without components installed.
