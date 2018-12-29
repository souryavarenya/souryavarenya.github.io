---
layout:       project
date:         07 Oct 2015
title:        Project Chronos
caption:      Suite of Smart Home Devices
description:  >
  A suite of connected smart home devices built for affordability and scalability
image:        /assets/img/project/chronos.png
screenshot:
  src:        /assets/img/project/chronos.png
  srcset:
    1920w:    /assets/img/project/chronos.png
    960w:     /assets/img/project/chronos.png
    480w:     /assets/img/project/chronos.png

coupro: true
#accent_color: '#ee682a'
#accent_image: /assets/img/sidebar-bg.jpg
---

This was one of the flagship projects of the robotics club at CFI, IIT Madras - that I did as a sophomore. Thanks to collaborators - Akshit Kumar, Sourav Debnath and Kushal Kakkad.

### Idea

Our idea is to automate the boring stuff by empowering the user with robust, affordable and scalable smart home solutions in terms of an end to end product integration of various peripheries which is driven by Internet of Things. We want to give the user the freedom in choosing whatever is relevant to his home, thereby providing him with increased flexibility. The following gives an overview of each vertical of the idea:

1. Smart Switch Board - The smart switch board will make the mechanical switches redundant, enabling the user to control all his devices from anywhere in the world. It shall be a plug and play non-invasive product with easy installation.
2. Sensor Board System - Smart sensor board which when integrated with the Smart Switch System would make a robust climate control system for the home along with giving notifications for cases of accidental fire and leakage of LPG
3. Energy Monitoring System - A marriage of a smart switch board along with the machine learning/artificial intelligence to make a more power/energy efficient home. It would enable the user to manage his electricity bills and enable capping the electricity usage in his/her home.
4. Universal Remote - To bring all the IR controlled devices under the control of a single remote which to achieve firmware independence of the device. Universal remote shall be able to control all IR operated devices in the house. For example, Television, Air conditioners, etc.

Animation
<div class="videowrapper">
  <iframe src="https://www.youtube.com/embed/36ZuRDEtNUY?rel=0" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen> </iframe>
</div>

Credits - Myself

Guess what? this animation was entirely made on PowerPoint.

### The Prototype

The prototype was a primitive one and is limited to basic operations such as switching of plug sockets. It featured Raspberry pi as the central unit and three sub-devices: switchboard, sensor board and universal remote.

The switchboard offers three plug sockets which are controlled using relays and a microcontroller inside it. It connects to the raspberry pi using Bluetooth. The switching can be controlled through a web application written in a popular web framework called Ruby on Rails. We have also added Simon, an intelligent personal assistant, who can take actions over your voice commands which makes use of Chrome’s Speech to Text API and uses a machine learning API to add intelligence to it. Additionally, the web app follows a hierarchy system. Certain user/s will have the power to control who can use certain devices in the same house.

![pic](shd.png)

The sensor board is basically a shield on the Arduino Uno which takes inputs from sensors and utilises wired I2C connection as a mode of communication. The universal remote is a direct attachment to the raspberry pi which offers a very low level control to the user.

Here's a demo:
<div class="videowrapper">
  <iframe src="https://www.youtube.com/embed/FEHcDMzxei4?rel=0" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen> </iframe>
</div>

This project was awarded a *gold medal* at the inter-IIT tech meet, conducted at IIT Mandi.
