# liblux

This is a LuXeria library for EAGLE.

## Design Rules
Any standard SMD component (as chip resistors, SOIC etc.) has to follow the 
IPC-SM-782 (Surface Mount Design and Land Pattern Standard).

## Naming
Every part has a unique name, that also gives information about it. 
The prefix is given by the class of the part. 

For instance a 1206 chip resistor is called 'r1206'.

### Classes

| Prefix   | Description           |
|----------|-----------------------|
| diode    | Diode - Rectifier, GP |
| schottky | Diode - Schottky      |
| zener    | Diode - Zener         |
| res      | Resistor              |
| cap      | Capacitor             |
| led      | Light Emitting Diode  |
| opamp    | Operational Amplifier |
