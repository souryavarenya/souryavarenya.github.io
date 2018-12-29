---
layout:       project
date:         30 Nov 2017
title:        Indoor Trilateration
caption:      Project for the course - Field Robotics
description:  >
  Project on indoor trilateration using inexpensive ESP8266 boards
image:        /assets/img/project/tril.png
screenshot:
  path:       /assets/img/project/tril.png
  srcset:
    1920w:    /assets/img/project/tril.png
    960w:     /assets/img/project/tril.png
    480w:     /assets/img/project/tril.png
coupro: true
---
This simple project demonstrates how indoor trilateration can be done with inexpensive ESP8266 modules.

The setup had 3 ESP8266 beacons and communicated to the central computer through sending GET requests sending RSSI data. The correlation between RSSI value has been established experimentally by fitting a logarthmic function on the measured data.

![pic2](pic2.png)

Then, we tested two algorithms - weighted centroid and least square error for localizing the master device. Moving average was then used to smoothen out the output. The results as you can see in the title picture were fairly accurate but further testing has to be carried out to establish statistical significance.
