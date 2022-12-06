Student: Oleksandr Bokhonko Group: CE 48 Subject: CSDT
Project name: chrome dragon game 
HW interface: SPI
Data driven format: XML

How to run project?
There are two ways to start a project:

1)With connection through SPI (Two Arduino boards are required)
2)Without connection through SPI (One Arduino board is required)

With connection through SPI:
1)Connect 2 Arduino to PC
2)Open SPIServer/SPISlave.ino in Arudino IDE and upload script to first Arduino board
3)Open SPIServer/SPIMaster.ino in Arudino IDE and upload script to second Arduino board
4)Connect (MOSI, MISO, SCK, SS) pins of the first Arduino with the same pins of the second Arduino board
5)Change COM Port

Without connection through SPI:
1)Connect Arduino to PC
2)Open NotSPIServer/Server.ino in Arudino IDE and upload script to Arduino board
3)Change COM Port
