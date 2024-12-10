# Gate Motor Controller

Built for a Centurion D5 Evo controller.

Credit: adapted from [wernerhp's implementation](https://github.com/wernerhp/esphome/tree/main/centurion-d5-evo).

<img src="assets/controls.png" />

## Features

* Control the gate motor (open, close).
* Partially open or close the gate.
* Engage the gate lock.
* Read and interpret the status LED (opening, closing, problems).
* Measure open/closed percentage.
* Simulate LED timings when connecting the sim pin to the status led pin.
* Includes a temperature sensor because that box gets hot!

## Components used

* ESP32 development board
* DC-DC Step-Down Buck Module (8-28V to 5V)
* 2x 5V Relay modules
* Dallas temperature sensor module
* Prototype board

## Photos

<img src="assets/front.jpg" />
<img src="assets/back.jpg" />
<img src="assets/top.jpg" />
