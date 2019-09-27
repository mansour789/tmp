# Sample Pseudo Code For A Thermostat
```

get target_temperature
target_temperature = 22
repeat forever,
    current_temperature = get target_sensor_reading
        if target_temperature => current_temperature                     
            turn_off_air_conditioner
        if target_temperature < current_temperature,                     
            turn_on_air_conditioner

```       
