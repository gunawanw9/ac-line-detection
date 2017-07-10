# [AC mains/ Zero Crossing Detection Module](https://shop.edwinrobotics.com/sensors/960-ac-mains-zero-crossing-detection-module.html) #

![AC Mains Zero Crossing Detection PCB.JPG](https://bitbucket.org/repo/yp8ebL7/images/1635986630-AC%20Mains%20Zero%20Crossing%20Detection%20PCB.JPG)

The AC mains/ Zero Crossing Detection Module from Edwin Robotics is an optically isolated AC line-to-logic interface device. The AC line voltage is monitored by a rectifier and an optocoupler, which provides isolation between High Voltage (HV) and Low Voltage (LV) Side. An active AC power line drives the output gate of the optocoupler to a logic low condition and in the absence of an AC line the output remains HIGH. The board is designed solely for the use as an AC line monitor. By default the output of the optocoupler is connected to a 2.2uF capacitor to provide TTL output, in the event that zero crossing is required, a jumper trace on the back of the PCB will need to be cut. Check the hookup guide for more information. The board has an on board pull-up resistors for uses with microcontrollers with weak pull-up. 

**FEATURES:**

* AC mains & Zero Crossing detection.
* On board pull-up
* High voltage isolation between input and output.
* Logic level compatibility

**SPECIFICATION:**

* Input Voltage Range: 110-300 V AC
* Max. Output Voltage Range: 5V
* Logic Interface: VCC, GND, Signal
* Dimensions: 20x20mm

[Hookup Guide](http://learn.edwinrobotics.com/230v110v-ac-mains-detection-using-arduino-raspberry-pi-and-esp8266-thing/)