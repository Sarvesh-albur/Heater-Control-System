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
 
Temperature: 26.00 °C - State: Heating
BLE Advertise: STATE=Heating
[Note:- Adjust DHT22 to for different readings]

Function:-
Here LED Blinks when it is in heating state and buzzer sounds with low frequency
If State Is Over Heating LED Stops Blinking And Sounds with high pitch and with long delay.

Conditions 
IDLE State:- 0-0.2 ranges
Heating State:- <24 degrees
Overheat:- <40 degrees
