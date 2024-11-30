# ModXo-Basic

![alt text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/logo.png?raw=true) <img src="https://github.com/Darkone83/ModXo-Basic/blob/main/Images/team-resurgent.png" width="180"> ![alt text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/DC%20logo.png?raw=true)

A carrier board designed for ModXo V1.X

This is designed around Team Resutgents and Shalx's work on ModXo an open-source modchip for the OG XBOX

For more information on the software side of things and the ModXo project please visit: https://github.com/Team-Resurgent/Modxo

The BOM and IBOMS are included for ease of assembly

#### Builders note

LED1 and R1 are optional and not required for the PCB to work as expected

## Navigation

Root: BOM and IBOM are located here

Images: All images, branding, PCB renders, and schematics are located in this folder

PCB: Gerbers and pick and place files are located in this folder

## Port pinouts

DISP:

![alt_text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/DISP.png?raw=true)

EXP:

![alt_text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/EXP.png?raw=true)

RGB:

![alt_text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/RGB_EXP.png?raw=true)

To enable the RBG EXP port you will need to manually install a jumper on the lower left pin of the RGB LED to the RBP pad on the carrier board. At this time RGP expansion is not currently enabled. See the example below for connecting the RGB pad

![alt_text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/RGB_EN.png?raw=true)

LPC:

![alt_text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/LPC.png?raw=true)
