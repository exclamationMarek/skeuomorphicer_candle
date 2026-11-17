# Basic Skeuomorphicer Candle
Most recommended design

# UNTESTED!
As of releasing this repo, this exact PCB design is NOT TESTED. It might be all wrong. I'm still waiting for this revision of PCBs to arrive to my lab.

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

# PCB configuration:
* 2-layer
* 1.0mm thick
* 35um (1oz) copper foil
* Basic FR4 TG135 (The candle is a bad idea and fire hazard no matter what material you pick)
* Soldermask colour may affect performance due to different emissivity. I used black to make it look like a wick.

# Assembly manual (light bulb configuration)
* Bridge Jumper JP1
* Skip D1
* Place 1.5V bulb on D2
* Use 3v3 out regulator for U1
* Populate all other components as listed in the schematic
* Find a value of R1 that makes candle work well. REDUCE if hard to blow out, INCREASE if does not stay on
* Supply from 2xAA or 2xAAA batteries
* Technically should also work with 1xAA

# Assembly manual (LED configuration)
* Use a 5V out regulator for U1
* Open Jumper JP1
* Place 2x LEDs on D1 and D2
* Populate R2 and R3 with 47-100R. Higher value produces dimmer light, but also less heat for the heat detection circut
* Populate all other components as listed in the schematic
* Find a value of R1 that makes candle work well. REDUCE if hard to blow out, INCREASE if does not stay on
* Supply from 2x or 3x AA or AAA batteries
* Technically should also work with 1xAA
* The 'custom' variant of the PCB separates the heaters from the LED current limiting resistors, which allows for dim light and reliable heat control
