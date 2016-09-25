# docker-pi-odroid-cloud
A Docker Cloud built with Raspberry Pi and ODroid hosts.

# Why

Building a private infrastructure for exploring Docker capabilities. Example of such setup is in the following:

* http://blog.hypriot.com/post/how-to-setup-rpi-docker-swarm/
* http://blog.hypriot.com/post/deploy-swarm-on-chip-with-docker-machine/

# Systems Architecture

* 1 ODroid-C2 Host: http://www.hardkernel.com/main/products/prdt_info.php
 * Running Ubuntu 16.04 (Mate): https://ubuntu-mate.org/
 * Amlogic ARM® Cortex®-A53(ARMv8) 1.5Ghz quad core CPUs
 * 2Gbyte DDR3 SDRAM
 * Storage with 200GB microSD
 * On/Off USB Connector
* 6 Raspberry Pi 3 Hosts: https://www.raspberrypi.org/products/raspberry-pi-3-model-b/
 * Running HypriotOS: http://hypriot.com
 * 32GB microSD
 * On/Off USB Connector
* Netgear Wifi Range Extender
 * Wifi ac
