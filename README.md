# Pi1541-Raspberry-Pi-Hat
Raspberry Pi Hat for the Commodore 1541 disk drive emulator from Steve White (https://cbm-pi1541.firebaseapp.com)

![Alt text](image.png "3D Model from KiCad")
 
Steve White has presented a wonderful project on his website (https://cbm-pi1541.firebaseapp.com/), which reproduces a Commodore Floppy 1541 cycle exactly. 

My project here is an essay for the Raspberry PI to provide the necessary interfaces and controls.

# The whole thing is still in beta status and a replica is at your own risk!


I put the necessary Gerber files to create a board here. The parts list (BOM)looks like this:

|Name|Component|Package|Value|
--- |--- | --- | ---
|D|LED red|3mm|-|
|J1|PinSocket Isolation Height: 11.05mm|2,54mm|2x20pins|
|J2, J3|DIN 6pins Socket Lumberg 010599|-|-|
|Piezo1|Piezo TDK PS1240P02BT|-|-|
|Q1 - Q4|BS170 Transistor|TO92|-|
|R1 - R5|Resistor 1/4W, 5%|0207|10k|
|RN1|Resistor Array|SIP5|10k|
|SW1 - SW5|SPST Angled PTS645Vx83|-|-|
|SW6|SPST Angled PTS645Vx39|-|-|

Soon I will also publish the KiCad project for this board. 

Direct links to order PCBs:<br/>

<a href="https://oshpark.com/shared_projects/hk2rCPFI"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>
<br/>
<a href="https://aisler.net/p/SNNWFCDJ"><img src="https://cdn.aisler.net/assets/logo-67a94d00e0bac52f9776e025bd2197e499f0afd705a0927474d9b1370dec35a4.png" alt="Order from Aisler"></img></a>
<br/>
<a href="https://www.pcbway.com/project/shareproject/W113176ASH8_Pi1541_Ad_on_Board.html"><img src="https://www.pcbway.com/project/img/images/frompcbway.png" alt="PCB from PCBWay"></img></a>
