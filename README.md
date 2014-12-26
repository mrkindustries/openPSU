openPSU
=============

## Open source lab power supply unit

openPSU is a *0-30V, 0-3A* linear power supply unit. There are similar schematics and layout files all over the internet, but few of them come with proper design files and project documentation.

A linear power supply has less HF noise than a switching supply and has a better response to quick load changes. And most important, it is so simple that you can repair it yourself. I've been using the same one for over 10 years.

It is desgned to be connected to a transformer, fine/coarse/current pots and those cheap 7 digit displays. An all-digital board could be stacked on top to provide programmable control and datalogging.

## Schematic
![Alt text](/hardware/doc/images/openPSU_schematic.png?raw=true "3D view")

## 3D views
![Alt text](/hardware/doc/images/3d_front.png?raw=true "3D view")

![Alt text](/hardware/doc/images/3d_back.png?raw=true "3D view")

This board was designed using kicad, you can find the CAD files in the /hardware/design folder
http://www.kicad-pcb.org

Download the schematic

[openPSU_schematic.pdf](/hardware/doc/openPSU_schematic.pdf?raw=true)

Order the BOM directly from Digikey, no parts uploading required.

http://www.digikey.com/short/747hq8

**Warning:** untested until the first prototype arrives