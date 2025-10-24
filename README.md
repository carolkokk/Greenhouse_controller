**Greenhouse_controller**

**Overview:**

The project implements a CO2 control system for a greenhouse. 
The controller maintains the CO2 level within the greenhouse defined by the user. If the level is below the setpoint, it would start injecting CO2. If CO2 exceeds 2000 ppm, the system would automatically start ventilation to reduce it back to the acceptable range. 

The cloud service via the RESTFUL API is included in the project. The user could check the monitored historical data and set the CO2 level remotely. 

**Hardware components:**

1. Produal MIO 12-V - Ventilation fan
2. Vaisala GMP 252 - CO2 Sensor
3. Vaisala HMP 60 - Temperature and humidity Sensor

The project is C++ project based on FreeRTOS. It is a group work build by 4 students from Metropolia of Applied Sciences - Carol, Julia, Qi, and Linh.
