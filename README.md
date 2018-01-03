# Keybored
A brand new Keyboard with all you need and more!

# Wishlist

	- USB Type C connector
	- WRGB LED backligt
	- seperate LED for Caps, Scroll, Num -lock
	- N-key Rollover
	- 105 Key ISO
	- USB Hub
	- Volume knob
	- Media controls seperate
	- OLED programmable display

# Vision
For prototyping purposes I will be using a ATmega32u4 to connect all switches. There are loads of people who did this before, so this is well documented. 
For the LED's I might be able to use the WS2811 from adafriut for individual LED control.  [https://cdn-shop.adafruit.com/datasheets/WS2811.pdf]

I have no idea on how to interconnect these chips, so the next step is creating a sketch in KiCAD and troubleshooting with the hivemind
The goal is to have programmable LEDs. The Seperate Caps, Scroll, Num -lock keys will need to be programmed seperate, if that is even possible.

Maybe using an arduino to prototype all features is a good idea.
# Credits
https://github.com/XenGi		for his teensy KiCAD files