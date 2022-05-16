# Power-Supply-Card

This power supply card was designed to be used in a bench power supply. 4 Cards would be used and digitally controlled via a DAC + MCU. The card is designed to take a a 34VDC input. This input is bucked down by a DC-DC switching pre-regulator which is set to be 2.5V higher than the desired output voltage. The final regulation is handled by two LT3081 linear regulators in parallel. These are used to eliminate any switching noise. 

