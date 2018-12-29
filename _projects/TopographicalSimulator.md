---
layout:       project
date:         30 Apr 2015
title:        Topographical Simulator
caption:      Project for the course - Virtual Reality Engineering
description:  >
  Project that lets any tablet mimic a simple surface
image:        /assets/img/project/topo.jpg
screenshot:
  path:       /assets/img/project/topo.jpg
  srcset:
    1920w:    /assets/img/project/topo.jpg
    960w:     /assets/img/project/topo.jpg
    480w:     /assets/img/project/topo.jpg
coupro: true
---
This project was done for the course AM5011 - Virtual Reality Engineering. The aim of the project was to come up with a device that could mimic a virtual surface. Based on the location of touch, the surface orients in such a way that the inclination of the surface matches with that of the virtual surface.

![design](components.jpg){:.lead}

As you can see in the above image, an android tablet has been used for taking the touch input and also for providing the pitch and roll angle feedback. This tablet connects to the microcontroller(Arduino Mega) over Bluetooth. At the end, the two servos which are attached to the frame control the pitch and roll angles. Due to the nature of the attachment, this setup works best while simulating a spherical surface. To achieve a complete simulating capability, we need to incorporate a vertical actuation (Z axis). Also, pairing this with a VR headset would result in an amazing immersive experience.

<div class="videowrapper">
  <iframe src="https://www.youtube.com/embed/aZKGbDbsQn8  ?rel=0" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen> </iframe>
</div>

<!-- style="width: 100%; height:100%;" -->
