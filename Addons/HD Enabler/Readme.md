# HD Enabeler Addon

<img src="https://github.com/Darkone83/ModXo-RP2040-Tiny/blob/main/Images/Nemesis.png" width=180> ![alt text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/DC%20logo.png?raw=true)

<img src="https://github.com/Darkone83/ModXo-Basic/blob/main/Addons/HD%20Enabler/Board.png" width=300>

This board is based on TeamUIX's Epimetheus with some slight modifications to interface with the ModXo-Basic board

For more information on Epimetheus visit: https://github.com/OfficialTeamUIX/Epimetheus

### Builders notes

The value for L1 is a 200ohm ferrite bead in a 0805 footprint, do not install R5 until after you have programmed your STM32

### Programming Notes

Once assembly is complete you can proceed to program your STM32 Review the NRST Harness diagram and temporarily install it for programming. The NRST wire will connect to the top pad of R5 (the one closest to the MCU) and the GND side to any viable GND source. Remove the NRST harness once you have verified and tested your firmware. Install R5 to complete the STM32 circuit. SDA is pulled directly from PIN 5 on the IN connector and SCL is pulled directly from PIN 2. Pinouts will be listed below. Proceed to Port assembly

#### Notice

We do not provide any firmware for the STM32. You will need to either code your own or obtain a firmware image legally!

## Where can I get one?

Pre-assembled boards and blank PCB's can be purchased at <a href="https://www.darkonecustoms.com">Darkone Customs</a> or your0 free to build your own (Listings removed due to DMCA)

Pre-assembled board: Link removed due to DMCA

Blank PCB: Link removed due to DMCA

# Installation

<img src="https://github.com/Darkone83/ModXo-Basic/blob/main/Addons/HD%20Enabler/Install.png">

Mount the add-on board and connect a 6P SH 1.0 cable from the IN connector to the ModXo-Basic board. Connect another 6P SH 1.0 cable from the OUT connector to your HDMI board. If you are installing an additional add-on module connect it to the EXP connector on the HD Enabler board.  

## Port pinouts

![alt_image](https://github.com/Darkone83/ModXo-Basic/blob/main/Addons/HD%20Enabler/HD%20Enabler%20Ports.png?raw=true)

NRST Harnes

![alt_image](https://raw.githubusercontent.com/Darkone83/ModXo-RP2040-Tiny/refs/heads/main/Images/NRST.png?raw=true)

