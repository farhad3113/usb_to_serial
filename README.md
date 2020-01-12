## USB to Serial Module

USB to Serial module with CH340E core with built-in USB connector on PCB.

To downlaod CH340 datasheet [click here](https://github.com/farhad3113/usb_to_serial/blob/master/CH340.pdf).

### Level Shifting

CH340 chip supports 5V and 3.3V power voltage. When using 5V source power, the VCC pin input 5V
power and the V3 pin should connect with decoupling 100nF capacitor. When using 3.3V power voltage,
connects V3 with VCC, both input 3.3V power voltage, and the other circuit voltage which connected with
CH340 cannot exceed 3.3V.

You need just power the chip with 3v3 and jumper pins 7 to 10 (Which are specified in the PCB). 


### Support

Having trouble with module? Contact me.
