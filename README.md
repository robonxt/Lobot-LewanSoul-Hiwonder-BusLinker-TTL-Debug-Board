# Lobot-LewanSoul-Hiwonder-BusLinker-TTL-Debug-Board
Collection of information about the Lobot/LewanSoul/Hiwonder BusLinker/TTL Debug Board

## Schematic 
![Schematic](<official_documentation/Buslinker v2.5 TTL Debugging Board Schematic.jpg>)
_BusLinker v2.5 Schematic - Retrieved on 2025.06.09_


## Documentation
- `/official_documentation` - PDFs and other official documentation
- `/unofficial_converted_documentation` - Converted documentation from `/official_documentation`
- `/unofficial_robonxt_cleaned_documentation` - robonxt's cleaned up version of the official documentation

## Notes:

Buslinker library notes:
- Seems like it wants 5V logic, so a stepup circuit is needed for ESP32s and RP2040s
- Essential for proper readings from servos powered at 7-12V

madhephaestus/lx16a-servo notes:
- Requires logic stepup for ESP32s and RP2040s
- Compatible with 74HC126 circuit and buslinker
- One-pin setup incompatible with logic stepup
- Movement range: 0-240000 (?)
