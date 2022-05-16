# Power-Supply-Card

This power supply card was designed to be used in a bench power supply. 4 Cards would be used and digitally controlled via a DAC + MCU. The card is designed to take in a 34VDC input. This input is bucked down by a DC-DC switching pre-regulator which is set to be 2.5V higher than the desired output voltage to minimize power loss in the linear regulators. The final regulation is handled by two LT3081 linear regulators in parallel. These are used to eliminate any switching noise. The final output is adjustable from 0-30VDC with an adjustable current limit of 0-3A.

![PCB Top](https://user-images.githubusercontent.com/11001357/168534881-71c658d8-7534-4f93-8033-23d634d0ec49.png)

![PCB Bottom](https://user-images.githubusercontent.com/11001357/168534934-ff18ff21-3333-4816-aafa-b8faa5038e63.png)

