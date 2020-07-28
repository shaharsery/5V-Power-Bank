# 5V rechargeable power bank

This project is a 5V rechargeable power bank, intended for use with 1 Li-ion / Li-Pol 3.7V rechargeable battery cell.

The design supports up to 1A of charge and output currents.

The exact specification of this design are strongly related to the battery used and other elements such as components used, enclosure, wall adapter etc. 

This is an open source hardware (OSHW) project, licensed under the Creative Commons Attribution Share Alike 4.0 International license.
 
For more information read the LICENSE file in the master branch, and visit [creativecommons.org](https://creativecommons.org/)

## Specifications 

#### Nominal ratings and parameters: 

Input Voltage: 5V

Output Voltage: 5V

Battery Cell: Li-ion / Li-Pol 3.7V 

Charge Current: 1A MAX (Adjustable)

Output Current: 1A MAX

#### Features:

The features below are based on the full BOM (except for NC components), changing values of components and / or unplacing components may cause other behaviors.

\- Input connectors: USB Type-B Micro, solder pads.

\- Output connectors: USB Type-A female, solder pads. 

\- Battery cell protections: Overcharge voltage, overdischarge voltage, overcharge current, overdischarge current, over-temperature operation, ESD protection and reverse polarity protection.

** THIS DOESN'T MEAN NOTHING CAN GO WRONG, ALWAYS MAKE SURE YOU CONNECTED EVERYTHING CORRECTLY, BATTERIES CAN EXPLODE, BURN AND HARM YOU IF NOT PROPERLY USED **

\- Adjustable charge current by changing resistor value (R5)

\- 2 indication LEDs:
	
	* Green LED to indicate charge completed (the green LED will turn off once the battery cell entered 2nd charge cycle).
	
	* Blue LED to indicate input power to the PCB. 

	Both LEDs will turn off when the power bank is removed from the wall adapter.


## Notes

\- The design was created as an entry level design project, it was designed to allow for others to learn, work with and create. I wanted to keep the design pretty simple and to mkae it 'hand-solderable', that's why all passive components' packages are 0603 or larger and all ICs have lead pins that could be hand soldered using a solder iron and some basic skills.

**Please take caution when using this desing, at this stage it has not been tested at all and may not work and even create damage or harm you, by using this design you are doing it at your own risk**
