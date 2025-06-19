# Z88 Serial Port Converter
The Cambridge Computers Z88 has a DE9 serial port with the following [pinout](https://cambridgez88.jira.com/wiki/spaces/UG40/pages/14024777/Appendix+B+-+Serial+port):
- Pin 1: +5V, do not use
- Pin 2: TxD, transmitted data
- Pin 3: RxD, received data
- Pin 4: RTS, request to send
- Pin 5: CTS, clear to send
- Pin 6: unknown, do not use
- Pin 7: GND, signal ground
- Pin 8: DCD, data carrier detect
- Pin 9: DTR, data terminal ready

To connect to a device with a DB25 plug we need to through-connect the DE9 pins to the equivalent on the DB25 side.  Additionally, we need to connect DB25 pin 6 (DSR, data set ready) to the DCD signal.<br>

Note that DB25 pin 1 is Protective Ground (PG) and must not be connected to signal ground.

![Z88 DE9 converter board](Z88_Serial_DE9-to-DB25.png)
