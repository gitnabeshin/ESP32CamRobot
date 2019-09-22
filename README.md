# ESP32CamRobot

![IMG_2347](https://user-images.githubusercontent.com/52347942/64022883-175a1280-cb72-11e9-898f-c5745106345f.jpg)

## Overview
* Original Robot using ESP32-CAM.
  * Body: Tamiya CamRobot [https://www.tamiya.com/japan/products/70227/index.html]
  * Main Controller: ESP32-CAM
  * Motor Controller: L9110S H-Bridge motor driver module (Controlled via GPIO 12,13,14,15) 
  * 2 Blue LEDs for Eyes
  * 1 Battery (5000mAh Output 5V 2.1A)
* Web UI Controller
  * Provides WiFi access point and Fixed IP address by ESP32 SoftAP Mode
  * stop, forward, backward, turn right, turn left
  * Flash LED ON/OFF (ESP32-CAM buildin)

![IMG_2352](https://user-images.githubusercontent.com/52347942/64023013-60aa6200-cb72-11e9-97f0-252137971a61.jpg)

## Movie on twitter
* https://t.co/VGJg1DwRf6

## Reffered from followings
* arduino-esp32 v1.0.3
  * https://github.com/espressif/arduino-esp32/tree/master/libraries/ESP32/examples/Camera/CameraWebServer
* https://github.com/espressif/esp-who/blob/master/examples/single_chip/camera_web_server/main/www/index_ov2640.html
* https://gist.github.com/me-no-dev/f137a950ce6dedb641d427d8db6355d2
