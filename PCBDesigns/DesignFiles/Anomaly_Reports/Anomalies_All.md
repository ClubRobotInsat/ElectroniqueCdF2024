## Motor Driver V1.0:

- Encoder footprint has too narrow holes (Corrected in version V1.1 of the Motor driver board)
- Better silkscreen options to consider, such as the +12V pin vs GND pins

## Primary power supply card V1.0:

- Holes on PTN78020W power supply footprint are too narrow. Current solution: replaced pins with smaller ones.
- Battery connector footprint has +Vbatt and GND pins swapped. Current solution: put connector on bottom face of board.


## Herkulex Driver board V0.0
-Servo connector erroneously provides 3.3V , documentation states/specifies 5V min for servo operation  
(Corrected in Version V1.0 of Herkulex Driver Board)

## Sensor Board V0.0 :
Major problem with Time Of Flight sensors, more pins should be exposed in order to set up I2C


## All boards
- STM32 boards are supplied via Vin, Vin theoretically should be supplied with a voltage between 7V and 12V (which then feeds into a Low Dropout Regulator). However we supply Vin with 5V, they still work but we are not operating in optimal conditions.
- Rounded corners should be considered.
- Efforts should be made to reduce size of all boards.

-No protection circuit around the MCP2551, which should be considered since a slight shift in 5V supply can annihilate all MCP2551's in one go



