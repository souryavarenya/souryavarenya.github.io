---
layout: project
date: 01 January 2020
title: AMZ Driverless
caption: Autonomous Driverless Racing
description: >
    Developing a fully autonomous electric vehicle for racing at FSG
image: /assets/img/project/amzdv.png
screenshot:
    src: /assets/img/project/amzdv.png
    srcset:
        1920w: /assets/img/project/amzdv.png
        960w: /assets/img/project/amzdv.png
        480w: /assets/img/project/amzdv.png

featured: true
accent_color: "#ee682a"
accent_image: /assets/img/sidebar-bg.jpg
---

### Software Infrastructure

_Oct 2019 - Aug 2020_

I began here as a core member of software infrastructure module where I was tasked with coordinating autonomous software development and maintaining FSSIM - our in-house built simulator. My work started with porting our autonomous codebase from ROS Kinetic to Melodic. To make the process of installing dependencies smoother and to achieve other repository management tasks like installing linter, I created amz-tool - a command line utility. This tool has undergone several upgrades and is still being actively developed by me, as of Jan 2021.

<!-- ![amz ci](amzci.jpg){:.lead} -->

As a part of this sub-team, I also gained first-hand experience of setting up self-managed servers and networks. I also setup Jenkins on our server for performing continuous integration on our autonomous software repository.

### Ground Truth Mapping Device

_Oct 2019 - Aug 2020_

Ground truth is a valuable piece of information for developing autonomous software, to evaluate performance against a ground reference. We have been previliged to have access to RTK services and I was tasked with re-designing ground truth mapping device (GTMD). Gained experience working with RTK(Real Time Kinematic) services while helping generate some valuable track data by tagging cones with 1cm accuracy.

![gtmd](gtmd.png){:.lead}

### Lead, Software and Data Analysis

_Sep 2020 - Mar 2021_

I am currently heading software infrastructure packages - ROS-CAN interface, repository management and track tools. I have also been active in adding features to amz-tool, expanding its capabilities to evaluation of KPIs and other useful functions.

![amz-tool](amztool.jpg){:.lead}

On the sidelines, I'm also engineering a lightweight web app for data analysis from our rosbags - called AMZ Playground. It is still in it's infancy and involves several verticals of software development

### Miscellaneous work

Apart from the technical work, I have also involved myself in some media work where I shot and edited a couple of videos for recruitment and sponsorships purpose. I also crafted a roll-up for recruitment drive.

![amz pipeline artwork](amzpipeline.png){:.lead}
