# esp8266-LEDMatrix
A simple program for displaying an animated message with an ESP8266 and a WS2812 (neopixel) matrix

## Using the program
This program depends on the following items:
1. An ESP8266. In this case, I used a NodeMCU board.
2. A WS2812B (neopixel) 32 x 8 LED Matrix plugged into pin D6 on the NodeMCU pinout
3. The Arduino IDE setup for programming an ESP8266
4. Either an SSID to connect to, or the board will create a network named `LED Matrix` with a password of `12345678`.

After uploading the program, the board will start scrolling its IP Address across the screen.
