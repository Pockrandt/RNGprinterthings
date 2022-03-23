# How to control Neopixel on Stock Ender 3v2 MCU


1. solder not more than a few neopixels in a daisy chain according to the label
2. crimp a 5 port  JST-XHP that goes into the BLtouch port, see picture (GND to GND, 5V to 5V [red], Data to PWM [yellow])
3. Get an LED klipper config from command ref or Voron SB repo
4. Use `pin: PB0` with `color_order: GRBW`

