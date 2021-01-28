# Required Tools and parts
For the upgrade you should have good tools to suceed. Specially good soldering equipment and a steady hand!
You will need:
* BGA Rework station (alternatively a Hot-air Station and a preheater)
* Temperature controlled soldering iron
* A set of tweezers to install the smd components
* Solder paste and dispenser
* Solder wick to clean the board after removing the original CPU
* And of course flux!

## Choosing a processor
If you do the upgrade it is recommended to choose the 1400Mhz version of the processor.  
But because they get expensiver i recommend to use a 1000Mhz or 1200Mhz CPU to practice and continue with the expensiver CPU once you succeeded.  
  
Here's a list of tested CPUs:
| SSPEC Number | Clock speed | Cache |  
| --- | --- | --- |  
| SL5XL | 1400Mhz |  512Kb |  
| SL6BY | 1400Mhz |  512Kb |  
| SL5VX | 1333Mhz |  256Kb |  
| SL6BZ | 1333Mhz |  256Kb |  
| SL5LW | 1266Mhz |  512Kb |  
| SL5VX | 1200Mhz |  256Kb |  
| ... | ... | ... |  
  
Basically any Socket 370 Pentium 3 with 133Mhz FSB will work. The tualatin core CPUs are recommended as the heatspreader allows for easier heatsink attachment and they have 512kKB Level 2 Cache!

## SMD Components
You can buy the components from the vendor of your choice. 

| Reference | Qty | Description | Part Number | Manufacturer | Digikey part number |  
| --- | --- | --- | --- | --- | --- |  
| R6 | 1 | Res 0Ohm, 0603 |  |  |  |  
| RN1 | 1 | Res 1KOhm, 0603x4 |  |  |  |  
| R2, R8 | 2 | Res 1KOhm, 0603 |  |  |  |  
| C5 | 1 | Cap 1nF, 0603 |  |  |  |  
| C45 | 1 | Cap 1uF, 0603 |  |  |  |  
| C14-C17,C19,C20,C23,C33,C34,C37,C38,C42 | 12 | Cap 4.7uF, 0805 |  |  |  |  
| C3,C4 | 2 | Cap 10pF, 0603 |  |  |  |  
| C7 | 1 | Cap 10uF, 0805 |  |  |  |  
| R5 | 1 | Res 15Ohm, 0603 |  |  |  |  
| R1 | 1 | Res 33Ohm, 0603 |  |  |  |  
| R7 | 1 | Res 100Ohm, 0603 |  |  |  |  
| C1,C2,C6,C8-C13,C18,C21,C22,C24-C32,C35,C36,C39-C41,C43,C44,C46 | 29 | Cap 100nF, 0603 |  |  |  |  
| R3 | 1 | Res 330Ohm, 0603 |  |  |  |  
| R4 | 1 | Res 470Ohm, 0603 |  |  |  |  
| D1 | 1 | LED Green, 0603 |  |  |  |  
| U2 | 1 | IC NC7SZ32, SOT23-5 |  |  |  |  
| U1 | 1 | IC NC7WZ07, SC70 |  |  |  |  
| OSC1 | 1 | OSC SG3030B |  |  |  |  
 
## Starting the install
First thing to do is reball the CPU Adapter. You need The 0.76mm leaded solder balls, flux and the reball stecil.  
Not going into details how to reball such a pcb here. You should be able to find instructional videos for it on youtube.  
<img src="./Images/IMG4947.jpg" alt="removed CPU" width="100%"/>  

## Remove the original CPU
First thing to do on the motherboard is to fire up your bga rework station and remove the original CPU.  
Clean the remaining solder off the motherboard using solder wick and flux. After a cleanup you should have a nice and tidy looking board.
The final result should look like this:  
<img src="./Images/IMG_4949.jpg" alt="reballed" width="100%"/>  


