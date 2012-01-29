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


Board Specs
-----------

*	Dimensions: Arduino Shield
*	Chip: MAX31855, TXB0104
*	Voltage: 5V, 3.3V
*	Header: 2 - 1x6 0.1" Pitch, 2 - 1x8 0.1" Pitch
*	Alternate Connection: 2x5 0.1" Pitch header
*	Fixturing: Matching holes to Arduino


Versions
--------

###v2.1

* Initial release under Eagle 6.1 on Github
* Shield designed for Arduino platform
* All blank space with 0.1" prototyping holes
* Built in level shifter for direct use with 5V Arduino


Purchase
--------

[store.ryanjmclaughlin.com](http://store.ryanjmclaughlin.com). 


TODO
----

*	Do not route LED through level shifter
*	Add 3.3V connection to center 2x5 header
