# Sonar microcontroller software

## Parts (expected)

* COM-08635 Electret microphone (x6) with filter and op amp buffers
* MPC3008 8-channel 10-bit ADC or similar
* Microcontroller for signal acquisition and processing (Arduino Mega-ish or dedicated DSP), drives the ADC over SPI
* Concentric Neopixel rings as display
* Second microcontroller for driving display based on serial data from the first one
* Power supply
