# LiquidCrystal_SWI2C
LiquidCrystal Arduino library for the DFRobot I2C LCD displays using Software I2C

I am using a Arduino Pro Mini 8 MHz 3.3V where the I2C pins are not exactly easily available

I had forked the original LiquidCrystal_I2C https://github.com/marcoschwartz/LiquidCrystal_I2C (commit 4bb48bd648c5e47f3f3c89e753924b4f2d021317) change all the functions to LiquidCrystal_SWI2C (in order to be used together without issues)

## Library dependancies
Requires the Software I2C library from https://github.com/felias-fogg/SoftI2CMaster

## I2C pinout
Pins are hardcoded in the file LiquidCrystal_SWI2C.cpp
* SDA is Arduino pin 7
* SCL is Arduino pin 6

You may change them to your liking
