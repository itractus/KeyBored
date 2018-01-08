# KeyBored
KeyBored is the name of a custom dream keyboard with every feature I could possibly want. Custom made and from scratch, this keyboard will be a bespoke tool adjusted to my needs.

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
For the LED's I might be able to use the [WS2811][1] from adafriut for individual LED control.  

I have no idea on how to interconnect these chips, so the next step is creating a sketch in KiCAD and troubleshooting with the hivemind
The goal is to have programmable LEDs. The Seperate Caps, Scroll, Num -lock keys will need to be programmed seperate, if that is even possible.
Maybe using an arduino to prototype all features is a good idea.
# Layout
![The current layout][2]
For the exact details on the planned layout of the keyboard you can look at Keybored.kbd.json in the Layout folder and import it in [ijprest's Keyboard layout Editor][3] or click [Here][4]

# Credits
https://github.com/XenGi		for his teensy KiCAD files.

https://github.com/ijprest/keyboard-layout-editor	For a wonderfull tool that helps me a lot with this project.


[1]: https://cdn-shop.adafruit.com/datasheets/WS2811.pdf
[2]: https://ptpimg.me/xa2t9y.png

[3]: http://www.keyboard-layout-editor.com/
[4]: http://bit.ly/2CwxKNn
