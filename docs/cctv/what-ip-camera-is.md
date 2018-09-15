# What ip camera is

## What types of cameras are

There are a lot of different types of security surveillance cameras. But we can split them in several groups.

- analog ( [composite](https://en.wikipedia.org/wiki/Composite_video) output interface)
- advanced analog ( custom vendor solutions in some sense similar to analog, but allow to transmit better quality video on longer distance)
- SDI ([Serial Digital Interface](https://en.wikipedia.org/wiki/Serial_digital_interface) output interface)
- ip cameras (ethernet output interface)

Analog cameras gives us 25/30 fps video with resolution like VGA (640x480). 
Custom advanced analog like AHD gives us 720p HD video. 
SDI cameras gives typically 1080p FullHD video.
All these 3 types of cameras outputs *uncompressed* raw signal.
Ip cameras are not limited in resolution (you can find solutions from 720p30 up to 8K30 with new **hi3559av100** chip from HiSilicon) 
as they outputs compressed video (that cause some delay unfortunately).

## What camera consis of

All of these types of cameras mostly consist of CCD or CMOS (now it will be CMOS for 90%) image capture sensor and System on a Chip.
SoC has input and output interface. Image sensor is connected to SoC`s input interface. SoC is capturing images from sensor, do some 
image processing and pass video to output interface. All other components that you can see on the camera module is just needed to turn on
the sensor and SoC (more about it you can read on [hardware explained](/hardware/hardware-explained/) page). 
SoC incapsulate mostly all things needed to capture, process and output video. ***So, you can recognize camera as a pair CMOS+SoC***.

## What we can influence 

SoC itself is a small computer. If we are talking about analog, AHD or SDI cameras than such computer 
is based on CPU like [Intel 8051](https://en.wikipedia.org/wiki/Intel_MCS-51). There will be some program that such CPU runs.
Such program is configuring internal components of the SoC and implements some user control via buttons or even rs-232.
Not very interesting, as there is no ability to run tons of existing software and mostly nothing to control, 
all available functions of SoC are implemented by camera module manufacturer already.

If we are talking about ip cameras, than it means that SoC is based on **full featured ARM cpu running GNU/Linux**. 
Actually, you can compare it with something like **Raspberry Pi** mini computer 
(main difference from first look will be absence of HDMI video output, 
interesting that SoCs themself support such interface, but manufacturers don\`t include it in hardware, as it usually doesn\`t needed).

In this case there are tons of existing software that we can run on camera module, moreover comparing to other arm based mini computers 
we will have advanced video processing ablities in our hands. Also typically there are USB host interface, audio in/out interfaces and even
some low level interfaces like UART, SPI, I2C. That means we can connect a lot of exiting external devices 
(like WiFi modules, 4G modems, temperature sensors, etc).

## Conclusion

!!! Important
    ***Mostly everything you need to know about ip camera, that it is just simple arm based computer connected to CMOS sensor placed on same PCB running GNU/Linux :thumbsup:.***



