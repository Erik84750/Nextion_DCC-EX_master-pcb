# Nextion_DCC-EX_master-pcb
PCB for Nextion-DCC-EX_enclosures

1. INTRODUCTION


  a. this is a custom made pcb for the Nextion_DCC-EX enclosure series

  b. provided are the Gerber files and the schematic (pdf). Latest versions are v8a, v8b and v8c

  c. upgrade from versions 5 to verions 8: allow more space for the regulator heatsinks, remove level shifters, add FTDI plugin connector, corrections to ESP autoflash circuitry

  d. VERY important: read the schematics in pdf for last minute modifications !!

2. GERBER

The gerber files are produced with Elecrow Design Rules constraints ( http://tinyurl.com/53mj2er3 ). These DRC's require a manufacturer capable of producing high quality prints.

3. Recommended is the PCB fab Elecrow: https://www.elecrow.com/

  This fab uses very low rates (1 USD for ten 100x100mm boards). The Nextion_DCC-EX_master pcb is designed to fit 2 of these pcb's on one 100x100mm board.
  If you desire this output you need to specify your request to the manufacturer: aks for panelization of this pcb (2x 49x99mm pcb on one 100x100mm board).
The result then is 20 pcb's for the cost of 1 USD plus shipping.


4. DESCRIPTION:

  a. board version 7a: valid for Pro Mini (and HC-12), ESP8266-12 on basic module, ESP32 dev-kit (38pin, 1" pin row width), and ESP32 basic module

  b. board version 7b: valid for Pro Mini (and HC-12), ESP8266-12 on basic module, ESP32 dev-kit (38pin, 1" pin row width, and 23.5mm pin row width)

  c. board version 7c: valid for Pro Mini (and HC-12), ESP8266-12 NodeMCU and ESP32 basic module

5. Hardware description:

  a. ESP8266 basic module: https://tinyurl.com/y2z66jum

  b. ESP32 basic module: https://tinyurl.com/mrbd2m5m and https://tinyurl.com/3mrma4hk

  c. hardware required (connectors, pcb female pinheaders, ... : see BOM
