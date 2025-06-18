# Lobot-LewanSoul-Hiwonder-BusLinker-TTL-Debug-Board
Collection of information about the Lobot/LewanSoul/Hiwonder BusLinker/TTL Debug Board

## Schematic 
![Schematic](Buslinker%20v2.5%20TTL%20Debugging%20Board%20Schematic.jpg)
_BusLinker v2.5 Schematic - Retrieved on 2025.06.09_


## Notes:

Buslinker library notes:
- Requires logic stepup for ESP32s and RP2040s
- Essential for proper readings from servos powered at 7-12V

madhephaestus/lx16a-servo notes:
- Requires logic stepup for ESP32s and RP2040s
- Compatible with 74HC126 circuit and buslinker
- One-pin setup incompatible with logic stepup
- Movement range: 0-240000 (?)
