Very experimental RTTY code for PecanPico4 hardware (that can be used instead of the APRS version)
This code is heavily borrowed from James Coxon (with modifications from Anthony Stirk)

In this version of the software the FSK is generated digitally and must be transferred from the ATMega (PD4) to the Si4464 GPIO0 pin.
Ideally use a XO or TCXO instead of a VCXO or hard wire the VCXO with a resistor divider to its middle frequency.
