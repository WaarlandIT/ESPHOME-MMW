# ESPHOME-MMW
ESPHome Millimeter Wave presence sensor

Hardware details:
- LD2410 sensor
- ESP-01 (ESP8266-01) board
- 100 kohm resistor
- 18650 battery cell with holder
- some wire and hot glue

Diagram:
![image](https://github.com/WaarlandIT/ESPHOME-MMW/assets/53364386/e78c2bb9-6795-4658-a930-26932eae306c)

End result 
- In Home Assistant:
![image](https://github.com/WaarlandIT/ESPHOME-MMW/assets/53364386/52ec30a1-1041-4603-8e8c-f27ac0ce080f)

- On my phone while testing:
<img src="https://github.com/WaarlandIT/ESPHOME-MMW/assets/53364386/e8285566-12c5-4b20-aaac-d3ef026c81a5" width="100">

How to use this:
Build like in the diagram and use the yaml files to generate the binary and write it to the ESP-01 like described on https://esphome.io/
