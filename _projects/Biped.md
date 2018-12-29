---
layout:       project
date:         18 Dec 2018
title:        Biped Test Bench
caption:      Research Project
description:  >
  An exploratory research project on serial redundant manipulator
image:        /assets/img/project/biped.png
screenshot:
  src:        /assets/img/project/biped.png
  srcset:
    1920w:    /assets/img/project/biped.png
    960w:     /assets/img/project/biped.png
    480w:     /assets/img/project/biped.png

featured:     true
#accent_color: '#ee682a'
#accent_image: /assets/img/sidebar-bg.jpg
---
This is a project on building a test platform for bipedal robot research. The objective is to set up a hardware and software framework for implementing various walking algorithms.

The class of bipedal robots we wish to build are known as underactuated robots. These have lesser motors/actuators than the degrees of freedom, making them challenging to control. This robot is meant to have pointed feet, just like a ballet dancer.

Over the span of two months I designed 3 variants of the biped and initiated the fabrication. Most of it is based on sheet-metal processing which makes it much faster and inexpensive to manufacture. You can see the design in the following pictures.

![design](fullren.png)

Currently, I am working on setting up the necessary hardware for the robot. Assembly is expected to happen over the next month.

I am also developing a simulation model for [V-REP](http://www.coppeliarobotics.com/) and a seamless integration with the hardware for interfacing with Python and MATLAB.
![design](vrep.jpg)
