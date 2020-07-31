# 5V rechargeable power bank (Work in progress)

This project is a 5V rechargeable power bank, intended for use with 1 Li-ion / Li-Pol 3.7V rechargeable battery cell.

The design supports up to 1A of charge current and up to 1A of output current.

The exact specification of this design are strongly related to the battery used and other elements such as components used, enclosure, wall adapter etc. 

This is an open source hardware (OSHW) project, licensed under the Creative Commons Attribution Share Alike 4.0 International license.
 
For more information read the LICENSE file in the master branch, and visit [creativecommons.org](https://creativecommons.org/)

**Please note that this project has not yet been manufactured or tested! USE AT YOUR OWN RISK!**

## Specifications 

#### Nominal ratings and parameters: 

Input Voltage: 5V

Output Voltage: 5V

Battery Cell: Li-ion / Li-Pol 3.7V 

Charge Current: 1A MAX (Adjustable)

Output Current: 1A MAX

#### Features:

The features below are based on the full BOM (without NC components), changing values of components and / or unplacing components may cause unintended behaviors.

\- Input connectors: USB Type-B Micro, solder pads.

\- Output connectors: USB Type-A female, solder pads. 

\- Battery cell protections: Overcharge voltage, overdischarge voltage, overcharge current, overdischarge current, over-temperature operation, ESD protection and reverse polarity protection.

** THIS DOESN'T MEAN NOTHING CAN GO WRONG, ALWAYS MAKE SURE YOU CONNECTED EVERYTHING CORRECTLY, BATTERIES CAN EXPLODE, BURN AND HARM YOU IF NOT PROPERLY USED **

\- Adjustable charge current by changing resistor value (R5)

\- 2 indication LEDs:

- Green LED to indicate charge completed (the green LED will turn off once the battery cell entered 2nd charge cycle).
	
- Blue LED to indicate input power to the PCB. 

Both LEDs will turn off when the power bank is removed from the wall adapter.

\- If the device is connected to a wall adapter a battery and a load, the load will be powered from the wall adapter and the battery will keep on charging, this might not work properly if the wall adapter rated current is not high enough (for MAX currents, the wall adapter should be capable of driving at least 2A)


## Notes

\- The design was created as an entry level design project, it was designed to allow for others to learn, work with and create.
 I wanted to keep the design pretty simple and to make it 'hand-solderable', that's why all passive components' packages are 0603 or larger and all ICs have lead pins,
 that way all components can be soldered using a solder iron and some basic skills.
 
 \- Through the design process I was aiming for the use of 18650 Li-ion battery cells, though it should work with any Li-ion / Li-Pol 3.7V battery, I plan on testing other battery cell packages once I'll have the PCBs for prototyping.
 
 \- Though all the components used in this project can be easily sourced from Digi-Key and Mouser, I tried to use components that can also be sourced through LCSC, Ebay or AliExpress, try to find a reliable distributor that suits your costs and needs.
 
 \- A lot of modifications can be made to reduce the cost of this design, consider the necessity of components according to your own use.
 
 \- I know some people would prefer the input connector to be Type-C, I might add another version of this design with Type-C connector later.
 
 \- I plan on creating 2 types of PCBs, one roughly the dimensions of a 18650 package, and one compact design that might be more suitable for flat battery packages.
 
 \- Please feel free to contact me if you have any question or remark, or if you found any mistake. I'll try to reply as fast as I can but I can't promise anything.
 
 \- Keep being awesome and help the OSHW community grow!

## Disclaimer

**Before you work with this project in any way, please make sure you understand what you are doing, electronics and batteries can be harmful and dangerous when not used properly.** 

**By using this project in any way you agree that you are using it at your own risk and you can't hold any one else accountable for any damage or harm that might be caused due to your use of this project.**

**Please note that this project has not yet been manufactured or tested! USE AT YOUR OWN RISK!**
