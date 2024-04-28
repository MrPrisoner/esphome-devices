# ESP Home

Projects built with [ESP Home](https://esphome.io/).

## Garage Door Controller

[View Code](https://github.com/MrPrisoner/esphome-devices/tree/main/source/garage-door)

A simple relay controller.

* Control the garage door motor (open, close).
* Read the door position using reed switches (TODO).

Components used:

* ESP8266 Wemos Mini D1 development board.
* DC-DC Step-Down Buck Module (8-28V to 5V)
* 3V Relay module.
* 2x Magnetic door switches.
* Small prototype board.

## Gate Motor Controller

[View Code](https://github.com/MrPrisoner/esphome-devices/tree/main/source/gate-controller)

Built for a Centurion D5 Evo controller.

* Control the gate motor (open, close).
* Engage the gate lock.
* Read and interpret the status LED.
* Simulate LED timings when connecting the sim pin to the status led pin.
* Includes a temperature sensor because that box gets hot!

Components used:

* ESP32 development board
* DC-DC Step-Down Buck Module (8-28V to 5V)
* 2x 5V Relay modules
* Dallas temperature sensor module
* Prototype board

Credit: adapted from [wernerhp's implementation](https://github.com/wernerhp/esphome/tree/main/centurion-d5-evo).

## Water Tank Level Sensor

[View Code](https://github.com/MrPrisoner/esphome-devices/tree/main/source/water-tank)

Measure the water level inside a tank using an ultrasonic distance sensor.

* Measure the distance from the top of the tank to the water level.
* Calculate the height of the water level from the ground.
* Calculate how full the tank is.
* Note that this sensor is installed in 2 connected tanks, thus the calculations are adjusted accordingly.

Components used:

* ESP32 Wemos Mini D1 development board.
* Waterproof ultrasonic distance sensor module.