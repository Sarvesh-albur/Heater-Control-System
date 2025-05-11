 Heater Control System
An Arduino-based heater controller using a DHT22 sensor, LED, buzzer, and simulated BLE output via Serial.

View Simulation on Wokwi:-https://wokwi.com/projects/430641840975312897

Features:-
5 heating states: IDLE, HEATING, STABILIZING, TARGET_REACHED, OVERHEAT

Temperature input via DHT22

Heater relay control

LED and buzzer feedback

BLE state simulated via Serial monitor

Temperature updated every 2 seconds (Timer1)

Pin Connections:-
Component	Arduino Pin:-

1)DHT22	(D7)
2)Heater	(D3)
3)Buzzer	(D4)
4)LED	(D5)

Requirements:-
1)Arduino UNO or compatible board

2)DHT sensor library (Adafruit)

Example Output:-
 
Temperature: 26.00 °C - State: Stabilizing
BLE Advertise: STATE=Stabilizing
