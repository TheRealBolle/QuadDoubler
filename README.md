# QuadDoubler Clone

This is a recreation of the QuadDoubler 68040 clock doubler accelerator for various Macintosh computers.
The schematics have been reverse engineered and new PCBs were created based on the schematics.
  
![fully populated board](/Performer_populated.jpg)

There are three board versions available that are electrically identical.
The only difference between them is the orientation in which it fits into the host machines CPU socket.

Each version will physically fit into a selection of different Macintosh models:
1. Centris 650 (25MHz), Quadra 900
2. Quadra 660AV, Quadra 700, Quadra 900
3. LC475, Quadra 605, Centris/Quadra 610 (20MHz and 25MHz)

The provided PCB files are licensed under CC-BY-NC-SA - they are not intended for commercial use.  
  
  
  
# Notes on GAL
  
The original GAL has been reverse engineered. The provided JEDEC file is meant to be used with either a GAL20RA10 or PALCE20RA10.
The GAL/PALCE needs to have a speed rating of 10ns. Faster or slower parts have not yet been tested and might or might not work.
  
# Board Files
  
The provided gerber files have been generated using the JLCPCB EAGLE cam job files.  
