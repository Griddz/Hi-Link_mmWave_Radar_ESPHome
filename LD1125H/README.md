## HLK-LD1125H Connect Diagram
### ESP32:
LD1125H URX (RX) <----> ESP32 GPIOxx (TX)   
LD1125H UTX (TX) <----> ESP32 GPIOxx (RX)   
LD1125H GND <----> ESP32 GND   
LD1125H Vcc <----> 5V Source    
### ESP8266:
LD1125H URX (RX) <----> ESP8266 GPIxx (TX)   
LD1125H UTX (TX) <----> ESP8266 GPIxx (RX)   
LD1125H GND <----> ESP8266 GND   
LD1125H Vcc <----> 5V Source    

## Radar Setting   
mth1: 0 to 2.8m sensitive   
mth2: 2.8 to 8m sensitive   
mth3: above 8m sensitive   
rmax: max distance   
Clearance Time: Mov/Occ to Clearance waiting time   
Movement Time: Mov to Occ waiting time   

## YAML:

If any compile problem occur, try **Clean Build Files** first
