# X-RTC add-on module

<img src="https://github.com/Darkone83/ModXo-Basic/blob/main/Images/team-resurgent.png" width="180"> ![alt text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/DC%20logo.png?raw=true)

<img src="https://github.com/Darkone83/ModXo-Basic/blob/main/Addons/X-RTC/Board.png" width=300>

This is based on Team Resurgent's and Andr-Zero's work on the X-RTC board. Minor changes have been made to adapt it to the ModXo-Basiv board

For more information on Team Resurgent and their projects please visit: https://github.com/Team-Resurgent/

For more information on Ander-Zero's X-RTC please visit: https://github.com/Andr-Zero/X-RTC

## Builders Note

The value of L1 is a 200ohm ferrite bead in a 0805 footprint. This version of the board ONLY supports a CR2032 and not a LR2032. Rechargeable batteries will not work with this board nor will any revisions be made to include said functionality. If you plan on mounting the PCB to the shield of the XBOX be sure to trim the leads on the battery holder flush and insulate the back of the PCB to prevent shorts if you plan on mounting it to the XBOX's RF Shield.

# Where can I get one?

Pre-assembled boards and blank PCB's can be purchased at <a href="https://www.darkonecustoms.com">Darkone Customs</a> or you can feel free to build your own!

Pre-assembled board: <a href="https://www.darkonecustoms.com/store/p/x-rtc-add-on-for-modxo-basic-assembled">Darkone Customs</a>

Blank PCB: <a href="https://www.darkonecustoms.com/store/p/x-rtc-add-on-for-modxo-basic-pcb">Darkone Customs</a>

# Installation
#### Installation images are based off of Andr-Zero's initial images

<img src="https://github.com/Darkone83/ModXo-Basic/blob/main/Addons/X-RTC/Install.png" wisth=300>

3.3V Standby points

Run a short wire from the console's 3.3v standby outlined in red to the 3.3V_StdBy pad on the add-on board. Mount and plug the 6P SH 1.0 cable from CN1 to the EXP connector on the ModXo-Basic (if you have another add-on board installed connect to the EXP connector on that board).  Lastly, install 3v battery in the coin cell holder.

## 1.0 & 1.1

<img src="https://github.com/Darkone83/ModXo-Basic/blob/main/Addons/X-RTC/1011Board.png" width=300>

## 1.2 & 1.4

<img src="https://github.com/Darkone83/ModXo-Basic/blob/main/Addons/X-RTC/1214Board.png" width=300>

## 1.6 Notes

3.3V_StdBy wire is not required. Mount and plug in the 6P SH 1.0 cable from CN1 to the EXP connector on the ModXo-Basic (if you have another add-on board installed connect to the EXP connector on that board).  Lastly, install 3v battery in the coin cell holder.

# Software

Cerbios 2.4.0 or higher is required to use X-RTC.

> Enables Automatic Time Sync With Optional RTC Hardware Connected to SMBus
>
> RtcEnable = True

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
