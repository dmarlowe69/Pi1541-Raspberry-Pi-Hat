# Pi1541-Raspberry-Pi-Hat
Raspberry Pi Hat for the Commodore 1541 disk drive emulator from Steve White (https://cbm-pi1541.firebaseapp.com)

![Alt text](image.png "3D Model from KiCad")
 
Steve White has presented a wonderful project on his website (https://cbm-pi1541.firebaseapp.com/), which reproduces a Commodore Floppy 1541 cycle exactly. 

My project here is an essay for the Raspberry PI to provide the necessary interfaces and controls.

# The whole thing is still in beta status and a replica is at your own risk!


I put the necessary Gerber files to create a board here. The parts list (BOM)looks like this:

D1              LED 3mm<br/>
J1              PinSocket RM2,54, 2x20pins, Isolation Height: 11.05mm<br/>
J2, J3          DIN 6pins Socket Lumberg 010599<br/>
Piezo1          Piezo TDK PS1240P02BT<br/>
Q1, Q2, Q3, Q4  BS170 Transistor<br/>
R1 - R5         10k Resistor 1/4W, 5%, 0207<br/>
RN1             Resistor Array SIP5, 10k<br/>
SW1 - SW5       SPST Angled PTS645Vx83<br/>
 
