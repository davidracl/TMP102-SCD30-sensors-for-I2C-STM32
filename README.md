# TMP102

Sensor adress 0x48

Temperature register at 0x00

```
3V3 ---> V+
PB8 ---> SCL
PB9 ---> SDA
GND ---> GND
GND ---> ADD0
         ALERT (NC)
```
    
SCL and SDA pull-up resistor (5k) to 3.3V


# SCD30

Sensor adress 0x61

Get data ready 0x0202
Read measure 0x0300
Self recalibration 0x5306
```
3V3 ---> V+
PB8 ---> SCL
PB9 ---> SDA
GND ---> GND
```
