Ex02_DashboardTempSensor
========================

A simple dashboard displaing temperature data.

### HW
* Main Platform: Jupiter Model A (https://www.jupitersystem.it/product-page/jupiter-model-a)
* Sensor: Thermo 3 Click (https://www.mikroe.com/thermo-3-click)

### SW
* Node-RED
* Dashboard package
* I2C package

### Description
This simple flow acquire the temperature data from a temperature click (Thermo 3 clcik) and plots the data on a local web dashboard,
accessible from the following address <host_ip>:1880/ui. A gauge and a chart are plotted. The data is acquired through i2c interface at a rate of 1 second.
