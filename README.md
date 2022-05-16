# Power-Supply-Card

This power supply card was designed to be used in a bench power supply. 4 Cards would be used and digitally controlled via a DAC + MCU. The card is designed to take a a 34VDC input. This input is bucked down by a DC-DC switching pre-regulator which is set to be 2.5V higher than the desired output voltage to minimize power loss in the linear regulators. The final regulation is handled by two LT3081 linear regulators in parallel. These are used to eliminate any switching noise. 

![PCB Top](https://user-images.githubusercontent.com/11001357/168533343-9981a899-2734-477a-bf49-ef107f898f54.jpeg)

![PCB Bottom](https://user-images.githubusercontent.com/11001357/168533410-db3d3e4d-6aec-4ed2-a0bc-4824d818d597.jpeg)

