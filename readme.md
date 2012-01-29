Single Thermocouple Shield
==========================

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a>
	
Designed By:

*	Ryan McLaughlin <ryan@ryanjmclaughlin.com>


Summary
-------

The thermocouple shield was based upon the original breakout board developed for the MAX6675.  While this is a great little chip it is a small surface mount part and therefore difficult to solder. The thermocouple shield helps with having the MAX31855 chip broken out to a simple 0.1" header, a direct interface the the shield, and also provides a PCB Thermocouple Connector to easily interface to a thermocouple. Thermocouple wires are not designed to be soldered and this provides a good solid connection, while also using the proper metals in the connector required for a thermocouple connection.

Connections to Arduino pins are through solder jumpers (normally-closed), however trace is easily cuttable to be able to re-map connections to different pins.  The TXB0104 level shifter to translates 5V Arduino signals to the MAX31855 (3.3V) so the shield can be used with 5V and 3.3V Arduino platforms. Arduino reset switch on the shield.  A secondary set of headers to breakout Arduino pins along sides of the shield to allow for easy prototyping or re-mapping of connections.


Tutorial
--------

It is simple to get everything up and running.

1.	Install a set of shield headers or shield stacking headers to the board
2.	(Optional) Cut solder jumpers if you need to connect the MAX31855 to different pins but adding jumpers between center header and shield pins.
3.	Connect a K-Type [Thermocouple](http://en.wikipedia.org/wiki/Thermocouple Thermocouple)
4.	Load one of the samples from the [[MAX31855 Arduino Library]] and you should see temperature information in the serial console.


Board Specs
-----------

*	Dimensions: Arduino Shield
*	Chip: MAX31855, TXB0104
*	Voltage: 5V, 3.3V
*	Header: 2 - 1x6 0.1" Pitch, 2 - 1x8 0.1" Pitch
*	Alternate Connection: 1x4 0.1" Pitch header
*	Fixturing: Matching holes to Arduino
*	Pin Connections
	*	13 - SCK
	*	12 - SO
	*	10 - CS1
	*	9 - LED1


Versions
--------

###v2.1

Initial release of a dedicated single channel board. The design follows the quad channel board. Other changes included:

* Initial release under Eagle 6.1 on Github
* Change to [[MAX31855]] chip
* Reduction to a single thermocouple channel
* Addition of prototyping space on all free areas of the shield
* Change solder jumpers to be normally-closed, however trace is easily cutable
* Added TXB0104 level shifter to translate 5V Arduino signals to the MAX31855
* Added Arduino reset switch
* Added secondary set of headers to breakout Arduino pins along sides of the shield
* Updated prototyping holes to fall on same 0.1" grid as Arduino headers

####Board Specs
* Dimensions: Arduino Shield
* Chip: MAX31855, TXB0104
* Voltage: 5V, 3.3V
* Header: 2 - 1x6 0.1" Pitch, 2 - 1x8 0.1" Pitch
* Fixturing: Matching holes to Arduino


Purchase
--------

[store.ryanjmclaughlin.com](http://store.ryanjmclaughlin.com). 


TODO
----

*	Do not route LED through level shifter
