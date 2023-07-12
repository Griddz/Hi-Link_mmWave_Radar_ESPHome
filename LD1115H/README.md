## HLK-LD1115H Connect Diagram
### ESP32:
LD1115H URX (RX) <----> ESP32 GPIOxx (TX)   
LD1115H UTX (TX) <----> ESP32 GPIOxx (RX)   
LD1115H GND <----> ESP32 GND   
LD1115H Vcc <----> 5V Source    
### ESP8266:
LD1115H URX (RX) <----> ESP8266 GPIxx (TX)   
LD1115H UTX (TX) <----> ESP8266 GPIxx (RX)   
LD1115H GND <----> ESP8266 GND   
LD1115H Vcc <----> 5V Source    
   
## Radar Setting
th1: movement sensitive   
th2: occupancy sensitive   
Clearance Time: Mov/Occ to Clearance waiting time   
Movement Time: Mov to Occ waiting time   

## YAML:

If any compile problem occur, try **Clean Build Files** first
