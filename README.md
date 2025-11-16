# GPS System for Rocket
Commercially available GPS systems are not available for rockets.  
Therefore, we have created a full-scratch system.  

## Specification
- GPS Antenna
    - Use commercially available active antennas.
- [GPS Front End](https://github.com/ishi-kai/GPS4Rocket#GPS_FrontEnd)
    - MAX2769B-based GPS front-end board
- [Navigation Message Processor](https://github.com/ishi-kai/GPS4Rocket#Navigation_Message_Processor)
    - Operator to process IO data and navigation messages

![GPS_System](/images/GPS_system.png)


## [GPS Front End Board](/GPS_FrontEnd/)
This is the hardware that handles the GPS front end. And This was created with KiCAD 9.  

![GPS_FrontEnd_schematic](/images/GPS_FrontEnd_schematic.png)
![GPS_FrontEnd_artwork](/images/GPS_FrontEnd_artwork.png)
![GPS_FrontEnd_board](/images/GPS_FrontEnd_board.jpg)


## [Navigation Message Processor](/Navigation_Message_Processor/)


