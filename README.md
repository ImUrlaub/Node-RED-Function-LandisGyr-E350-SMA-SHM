# Node-RED-Function-LandisGyr-E350-SMA-SHM
Reading energy consumption from an Landis and Gyr E350 D0 with Node-RED in parallel to an SMA Sunny Home Manager.

Curren setup:
Raspberry Pi 3
USB-Serial adapter
Connection between the RXD and GND of the serial adapter and green (GND) and white (TXD) cable of the SMA HM-D0-Meteradapter.

The Sunny Home Manager is polling the energy meter and we only listen to the answers and parse them.
