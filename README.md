# ST7789_BMPviaSerial
Photo slideshow via serial interface on Arduino and ST7789 240x240 IPS

YouTube video:
https://youtu.be/vQY5ILjSZBc


## Purpose
To check LCD features (colors reproduction, brightness, contrast) and you need it quick without playing with SD card modules, libraries, etc.
Project code can be easily modified for any LCD, the only required function is drawPixel()

## How to use
- Convert photos to 240x240 24-bit Windows Bitmap (use Irfanview)
- Start CoolTerm and set 115200bps serial port speed
- Use "Send TextFile" to send photos to Arduino

## Improved version
https://github.com/cbm80amiga/ILI9163C_BMPviaSerial_Scroll
