# LED strip (WS2812 / NeoPixel)

RGB LED strip where each LED can have its own color. It uses MicroPython's built-in `neopixel` module, so there is no library to upload.

## Wiring

| Strip | Board |
|---|---|
| 5V | 5V (VBUS). Use a separate power supply for many LEDs |
| GND | GND |
| DIN | The pin set on the block (default GP16) |

## Blocks

1. **LED strip on pin … with … LEDs**: Put it at the start of your program to set up the strip once.
2. **set LED … to …**, **set all LEDs to …**: Set the colors (the first LED is 0).
3. **update the strip**: After setting the colors, update the strip to light up the LEDs.
