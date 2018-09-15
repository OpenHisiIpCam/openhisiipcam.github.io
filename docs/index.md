# Open source network camera firmware for HiSilicon based hardware 

## Introduction to the **OpenHisiIpCam** project

These days people across all over the world widely use security surveillance cameras. 
You can see them everywhere: on streets and roads, on subway stations, in offices, in houses.
People even use them not only for security tasks, but also for industrial control and machine vision.
Amount of such cameras can be recognized as hundreads of millions :astonished:! 

There are different types of cameras, but one of the largest type (by amount) is network type 
(more about different types of cameras and why ip cameras are most interesting [here](/cctv/what-ip-camera-is/)).

Unfortunately, if we will go deeper researching target area, we will that mostly all devices (especially in low-end and mid-end
segments) have some software issues:

* vendor\`s cloud locks or pushing device\`s owner to work only with vendors infrastructure
* broken streaming (some inconsistent with common standarts like RFC)
* lack of streaming protocols
* lack of network settings (for example no ability to up VPN)
* security problems (something like [this](https://pierrekim.github.io/blog/2017-03-08-camera-goahead-0day.html))
* tons of them, like disabling ability to change jpeg snapshot resolution (setting by default to something like 320x240)

People solves problems different ways, basic solution is to add additional computer for camera 
(we will be lucky of ot will be something like Raspberry Pi, usually it is small desktop...).
Some more advanced uses dumps software from cameras and embedd some additional software around existing vendor`s binaries.
People do it, becasue still they need to get their job done, but their hands tied by vendors.

Fortunately most popular ip camera hardware are made on HiSilicon`s chips (more about avalible chips [here](/cctv/hisilicon-chips/)) 
and everything is here to solve all these problems or at least try.

## Project targets

***Create configurable (build time and runtime) firmware for HiSilicon`s SoCs based hardware, that will
provide easy usage and integration with modern systems for tasks related to security and machine/technical vision areas***.

### Status

Project is at early stage. Mostly nothing is done yet :unamused:.
