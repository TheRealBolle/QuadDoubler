# QuadDoubler Clone

This is a recreation of the QuadDoubler 68040 clock doubler accelerator for various Macintosh computers.
The schematics have been reverse engineered and new PCBs were created based on the schematics.
  
![fully populated board](/QuadDoubler_populated.jpg)

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

# Partlist

Part|Value|Package
---|---|---
C1|  10uF/10V |  C3216/A Case
C2|  10uF/10V|  C3216/A Case
C3|  100nF|  C1206
C4|  100nF|  C1206
C5|  100nF|  C1206
C6|  100nF|  C1206
C7|  100nF|  C1206
C8|  100nF|  C1206
C9|  100nF|  C1206
C10|100nF|  C1206
C11|100nF|  C1206
C12|100nF|  C1206
C13|100nF|  C1206
FAN|2-pin header for 5V fan|
P1|  PGA179 pin array|
R1|  1k|R1206
R2|  1k|R1206
R3|  1k|R1206
R4|  1k|R1206
R5|  1k|R1206
R6|  47|R1206
R7|  47|R1206
R8|  470k|R1206
R9|  330|R1206
R10|1k|R1206
U1|  GAL20RA10|PLCC28
U2|   socket/68040 CPU|PGA179
U3|  MC88916DW80 |    SO20W
