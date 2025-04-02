# Poppy sorting line 
Poppy sorting line at one farm in Czech Republic build on PLR LOGO from Siemens. 

The aim of this line is to sort quality poppy seeds from poor quality and divide them into three quality grades using air from a fan and vibrations from a vibrator in a special sorting table.

I implemented the entire power electrical installation for all parts of the line on this line. From wiring the switchboard, designing the program for LOGO and final line tests.

Sorting table in building process: 

<p align="center">
  <img src="https://github.com/user-attachments/assets/0eb14221-6a0e-4182-8874-346d4412ae44" alt="Obrázek 1" width="800">
</p>



The line is controlled by a LOGO! 24RCE unit from Siemens, this unit controls the start-up of individual elements in the line, and also starts the belt, auger and elevator for feeding bulk material to the sorting table. Logo starts the entire line operation based on capacitive sensors that are located in the hopper on the table.
• These sensors determine whether the hopper is filled to the value MIN = MINIMUM, MID =MIDLE (MIDDLE) or MAX = MAXIMUM.
• Then there is a capacitive sensor in the hopper that can turn off the sorting table.
• The feed of material into the sorting table is always triggered by the switched MID and MAX sensors, MIN and the sensor in the hopper turn off the sorting table.

The MID and MAX sensors start the material supply to the table (the sensors are green). The MAX sensor turns off the supply if it is covered with material (it is red) and as soon as the material falls below the MID sensor (it is green), the material supply starts again. The MIN sensor and the Hopper switch the table on and off. The MIN sensor without material (it is green) turns off the table and with material it turns it on (the sensor is red). For the Hopper sensor, the following applies: a covered sensor (it is red) turns off the table to prevent further material supply and an uncovered sensor (it is green) starts the table.


<p align="center">
  <img src="https://github.com/user-attachments/assets/140a7ce9-e215-4871-ab2d-f31085c92783" alt="Obrázek 2" width="800">
</p>

Here are some pictures from realization:
<p align="center">
  <img src="https://github.com/user-attachments/assets/f55d116f-9864-4acd-942e-05cb58ac48e8" alt="Obrázek 3" width="300" >
  <img src="https://github.com/user-attachments/assets/fe9a46da-b5b2-4814-abf4-7d9d284433dc" alt="Obrázek 4" width="200" height="250">
</p>





