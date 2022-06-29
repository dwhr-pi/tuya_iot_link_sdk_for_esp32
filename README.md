# Tuya Link SDK for ESP32 Sample application

Mehr Anleitungen zu googeln mit: "esp32 tuya". 

[Blink an LED on ESP32 board with Tuya Link SDK(https://www.cnx-software.com/2021/12/13/blink-an-led-on-esp32-board-with-tuya-link-sdk/)]. 



Tuya Link SDK ESP32 port.

Espressif ESP-IDF checkout release/v4.2 branch

## How to use example

### Hardware Required

This example can be executed on any ESP32 board, the only required interface is WiFi and connection to internet.

### Configure the project

* Open the project configuration menu (`idf.py menuconfig`)
  
    Example Connection Configuration  --->
    * Set WiFi SSID under Example Configuration
    * Set WiFi Password under Example Configuration


### Build and Flash

Build the project and flash it to the board, then run monitor tool to view serial output:

```
idf.py -p PORT flash monitor
```

(To exit the serial monitor, type ``Ctrl-]``.)

See the Getting Started Guide for full steps to configure and use ESP-IDF to build projects.
