# Coil Speedifyer
This circuit can be used to interrupt current into a coil and, by allowing the emf to peak to a tunable value, speed up the turn off.
The main limitations are:
1) Reduced duty cycle: that can be changed by using a different driver circuit for the MOSFET. It turns out it was not necessary for our application
2) Speed limited by the voltage rating of the MOS. This can be changed by selecting different MOSFET (Including SiC)
