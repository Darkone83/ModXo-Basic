# X-RTC add-on module

<img src="https://github.com/Darkone83/ModXo-Basic/blob/main/Images/team-resurgent.png" width="180"> ![alt text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/DC%20logo.png?raw=true)

This is based on Team Resurgent's and Andr-Zero's work on the X-RTC board. Minor changes have been made to adapt it to the ModXo-Basiv board

For more information on Team Resurgent and their projects please visit: https://github.com/Team-Resurgent/

For more information on Ander-Zero's X-RTC please visit: https://github.com/Andr-Zero/X-RTC

## Builders Note

The value of L1 is a 200ohm ferrite bead in a 0805 footprint. This version of the board ONLY supports a CR2032 and not a LR2032. Rechargeable batteries will not work with this board nor will any revisions be made to include said functionality. If you plan on mounting the PCB to the shield of the XBOX be sure to rim the leads on the battery holder flush and insulate the back of the PCB to prevent shorts

# Where can I get one?

Pre-assembled boards and blank PCB's can be purchased at <a href="https://www.darkonecustoms.com">Darkone Customs</a> or you can feel free to build your own!

Pre-assembled board: Coming Soon!

Blank PCB: Coming Soon!

# Installation

Will be updated after initial testing has been completed 

# Software

Cerbios 2.4.0 or higher is required to use X-RTC.

; Enables Automatic Time Sync With Optional RTC Hardware Connected to SMBus

RtcEnable = True

Using a Chip that can use PrometheOS: Version 1.4.0 or higher is able to set the time, enable RTC in PrometheOS Settings. (Rebooting recommended)

TSOP or Other: Download the X-RTC.xbe into your Apps folder, within you can set the time.

Once the time is set and Cerbios is configured. The time on the console will set automatically on boot.

# Port pinouts

CN1

![alt_image](https://github.com/Darkone83/ModXo-Basic/blob/main/Addons/X-RTC/CN1.png?raw=true)

# Thanks

All thanks and credit goto the following parties

Team Resurgent for the idea, PrometheOS, and the XBE.

Cerbios team for including functionality into their BIOS.

Andr-Zero for their work on X-RTC
