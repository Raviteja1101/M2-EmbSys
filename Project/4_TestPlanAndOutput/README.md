# Test Plan:
|Test Id|Description|Expected I/P|Expected O/P|Status|
|-------|--------|----------|-----------|----------|
|T_01|If the person seated in car|1|1|PASS|
|T_02|After passenger and seated, the user needs to enable the heater sensor|Heatsensor On|Heatsensor On|PASS|
|T_03|Enabling both button and heater sensor, LED will be ON|LED On|LED On|PASS|
|T_04|Temperature Sensor|Temp=0|Heater=off|PASS|
|T_05|Temperature Sensor|Temp <= 209|Heater = 20degree|PASS
|T_06|LED On|Button=1 && Heater=1|LED=1|PASS|
|T_07|LED OFF|Button=0 && Heater=0|LED=0|PASS|
|T_08|LCD Display|Temperature = 33degree celsius|Temperature = 33degree Celsius|PASS|
