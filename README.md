# Pi1541-Raspberry-Pi-Hat
Raspberry Pi Hat for the Commodore 1541 disk drive emulator from Steve White (https://cbm-pi1541.firebaseapp.com)



# Update 20. May 2018: Now that the assignment of the GPIOs has been determined, I have created a new version of the Pi1541 Hat.

A TXS0108E from Texas Instrument is used as driver. You can solder it as TSSOP-20 SMD component on the board, OR (!!!!) use one of the finished modules.


![Alt text](image.png "3D Model from KiCad")
 
Steve White has presented a project on his website (https://cbm-pi1541.firebaseapp.com/), which reproduces a Commodore Floppy 1541 cycle exactly. 

My project here is an essay for the Raspberry PI to provide the necessary interfaces and controls.

This is the back of the board:

![Alt text](back.png "3D Model from KiCad")


I put the necessary Gerber files to create a board here. The parts list (BOM)looks like this:

|Name|Component|Package|Value|
--- |--- | --- | ---
|J1|PinSocket ESQ-120-34-G-D|2,54mm|2x20pins|
|J2, J3|DIN Socket Lumberg 010599|-|6pins|
|Piezo1|Piezo TDK PS1240P02BT|-|-|
|U1|TI TXS0108E|TSSOP-20|-|
|C1 - C2|Ceramic Capacitor|0805|0,1µF|
|C3 - C8|Ceramic Capacitor|0805|10nF|
|D1|LED|3mm|-|
|R1|Resistor|0805|220|
|SW1 - SW5|SPST Angled PTS645Vx83|-|-|
|SW6|SPST Angled PTS645Vx39|-|-|

Soon I will also publish the KiCad project for this board. 

Direct links to order PCBs:<br/>

<br/>
<a href="https://www.pcbway.com/project/shareproject/W113176ASH10_Pi1541_Ad_on_Board.html"><img src="https://www.pcbway.com/project/img/images/frompcbway.png" alt="PCB from PCBWay"></img></a>
<br/>
<a href="https://oshpark.com/shared_projects/2puKZ2N1"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>
