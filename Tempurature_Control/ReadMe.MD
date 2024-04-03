To understand the concept of Super cooling please refer to:
https://proskillservices.com/hvac-plumbing-heating-blog/2018/03/01/save-money-with-super-cooling/

Note: Following actions can be nested in one action like following
  - type: device.command.ThermostatSetMode 
      thermostatMode: cool
      devices: 
        - Living Room Thermostat - Living Room
        - Loft Thermostat - Loft
  
But I observed failures. At times, only one of the thermostats were changed. 
Therefore I included sleep of 5 for every operation
