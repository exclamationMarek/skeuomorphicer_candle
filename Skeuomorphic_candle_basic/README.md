# Basic Skeuomorphicer Candle
Most recommended design

# UNTESTED!
As of releasing this repo, this PCB design is NOT TESTED. It might be all wrong.

# Part list (light bulb configuration)
* 1x 1.5V miniature tungsten bulb. Should draw about 100-130mA at 1.5V
* 1x SI2302 N-MOS (or similar)
* 1x ETA1061V33 boost converter with 3.3V output
* 1x 2.2uH inductor in 1008 package
* 2x 4.7uF capacitors in 0603 package
* 1x 100k NTC in 0603 package
* 2x 33R resistors in 0603 package
* 1x 6.8k resistor in 0603 package
* 1x battery holder for 2xAA
* 2x AA battery (NiMH rechargable works great)

# Assembly manual (light bulb configuration)
* Bridge Jumper JP1
* Skip D1
* Place 1.5V bulb on D2
* Use 3v3 out regulator for U1
* Populate all other components as listed in the schematic
* Find a value of R1 that makes candle work well. REDUCE if hard to blow out, INCREASE if does not stay on
* Supply from 2xAA or 2xAAA batteries