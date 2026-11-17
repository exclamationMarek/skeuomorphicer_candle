# Minimal Skeuomorphicer Candle
Wokrs OK, not great, but uses very few parts

# Assembly instructions
![](../images/minimalistic_assembly.jpg)
* Populate all components as listed in the schematic
* Supply from 2xAA batteries (NiMH rechargable preferably)
* Test if behaves well
* If does not stay on, increase R1 (27k)
* If difficult to blow out, reduce R1 (27k)

# Sensitive to battery voltage
* This design is sensitive to battery voltage
* The lower the voltage, the more likely the candle will turn itself off
* Therefore, the candle will likely turn itself off even then there is plenty of energy left in the battery
* That is why it is best to use NiMH rechargables, otherwise you will be left with a buch of half-full batteries

# Part list (light bulb configuration)
* 1x 1.5V miniature tungsten bulb. 3-4mm size, should draw about 130mA at 1.5V
* 1x SI2302 N-MOS (or similar)
* 1x 100k NTC in 0603 package
* 2x 22R resistors in 0603 package
* 1x 27k resistor in 0603 package
* 1x battery holder for 2xAA
* 2x AA battery (NiMH rechargable works great)

