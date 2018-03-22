# Enabling CTCSS on TM721E

![TSU-6 from connector](images/tsu-6_view_from_connector.jpg)

![TSU-6 schematics](images/tsu-6_connector_schematics.jpg)

![tsu-6 tm-721 connections](images/tsu6_tm721e_connections.png)

![W7](images/w7.jpg)

![TSU-6 circuit](images/tsu-6_circuit.png)

W7    | TSU-6  | Notes
------|--------|-------
8:ET  | 10:ET  |
 7:DT |  9:DP  | Data
 6:CT |  8:CP  | Clock
 5:SDO|  7:SDO | Serial data out
 4:E  |  6:TO  |
3:5C  |  3:5C  |
2:CI  |  2:CI  |
1:E   |  1:E   |
 /    |  4:CO  |
 /    |  5: PTT|


In models with the CTCSS cable, there is a 33k resistor between E (GND) and TO

![TH-45 resistor](images/th-45_33k.jpg =100x) 


Pitch is the distance between pins.  
Common one or two rows pin headers are .1" (2.54mm)

http://tech.mattmillman.com/info/crimpconnectors/
