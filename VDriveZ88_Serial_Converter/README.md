# VDrive Serial Interface Converter for Z88
Refer to [Ben Vyre's project page](https://benryves.com/products/vdrivez88) and [Github](https://github.com/benryves/VDriveZ88/) for the background.

## RS232 Serial Pinouts
Note that this design uses the Z88's non-standard DE9 RS232 pin numbering.<br>
For [standard RS232 pin numbering](https://cambridgez88.jira.com/wiki/spaces/UG/pages/35913795/Appendix+B+-+Serial+port+and+transfer+protocols):<br>
|Standard DE9|Z88 DE9|
|------------|-------|
| DCD (pin 1) | pin 8         |
| RXD (pin 2) | pin 3         |
| TXD (pin 3) | pin 2         |
| DTR (pin 4) | not connected |
| GND (pin 5) | pin 7         |
| DSR (pin 6) | pin 8         |
| RTS (pin 7) | pin 4         |
| CTS (pin 8) | pin 5         |
| RI  (pin 9) | not connected |

## BOM
- 1 x MAX232
- 1 x 2.2KΩ pullup resistor
- 5 x 1µF ceramic capacitors (2.5mm pitch)
- 1 x 9-way 2.54mm pitch pin header for Z88 serial
- 1 x 8-way 2mm pitch pin header for VDrive interface
- 1 x 2-way 2.54mm pin header for +5VDC power input
- 2 x M2 screws for mounting the PCB

Note that pin headers are optional - you could just directly solder the wires to the PCB.<br>

![Serial interface board](VDriveZ88_Serial_Interface_3D.png)

## Status
9-Aug-2025: This design is currently untested
