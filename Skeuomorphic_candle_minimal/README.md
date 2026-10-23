# Minimal Skeuomorphicer Candle
Does not work great, but uses very few parts

# UNTESTED!
As of releasing this repo, this PCB design is NOT TESTED. It might be all wrong.

# Part list (light bulb configuration)
* 1x 1.5V miniature tungsten bulb. Should draw about 100-130mA at 1.5V
* 1x SI2302 N-MOS (or similar)
* 1x 100k NTC in 0603 package
* 2x 33R resistors in 0603 package
* 1x 6.8k resistor in 0603 package
* 1x battery holder for 2xAA
* 2x AA battery (NiMH rechargable works great)

# Assembly manual (light bulb configuration)
* Populate all components as listed in the schematic
* Find a value of R1 that makes candle work well. REDUCE if hard to blow out, INCREASE if does not stay on
* Note that as the batteries are discharged, the threshold will shift, making it more likely that the candle does not stay on
* Therefore, tune R1 with full batteries, and make it so that it is barely possible to blow out the candle
* Supply from 2xAA batteries