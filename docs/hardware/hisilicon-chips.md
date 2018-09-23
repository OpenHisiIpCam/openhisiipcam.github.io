# Overview of HiSilicon`s SoCs for ip cameras

We splitted chips in groups, that we call *family*. Chips in a family have same CPU architecture, share same vendor SDK and 
usually differs in only video processing capability terms. 

Here you can find list of avalible chips. We point only to video encoding performance. 
Actually, chips not only different in video encoding performance, but also different in advanced encoding settings (like intra refresh), 
processing and video analytics capabilities.

## hi3516cv100 family 

* [Hi3516cv100 brief datasheet](/hardware/briefs/hi3516cv100.pdf).

ARM926, jpeg, mjpeg, h.264 (baseline, main)

|Chip| |
|----|--|
|hi3516cv100|1920x1080@30fps encoding performance|
|hi3518cv100|1280x720@30fps encoding performance|
|hi3518ev100|same as hi3518cv100, but 32MB RAM embedded|

Supported CMOSes:

* **Sony**: IMX104, IMX225, IMX122/222/322, IMX236, IMX138, ICX692
* **Panasonic**: MN34041, MN34031
* **OmniVision**: OV9712
* **Aptina**: AR0330
* **ON**: AR0130, AR0140, 9M034
* **PixelPlus**: PO3100K
* **Himax**: HM1375
* **Silicon Optronics**: H22

## hi3516cv200 family

* [Hi3516cv200 brief datasheet](/hardware/briefs/hi3516cv200.pdf).
* [Hi3518ev200/201 brief datasheet](/hardware/briefs/hi3518ev200.pdf).

ARM926, jpeg, mjpeg, h.264(baseline, main, high)

|Chip| |
|----|--|
|hi3516cv200|`TBD` |
|hi3518ev200|`TBD`, 64MB RAM embedded|
|hi3518ev201|`TBD`, 32MB RAM embedded|

Supported CMOSes:

* **Sony**: IMX122/222/322
* **Panasonic**: MN34222
* **OmniVision**: OV2718, OV9712, OV9750, OV9732, OV9752
* **ON**: 9M034, AR0230, AR0130 

## hi3516cv300 family
* [Hi3516cv300 Brief datasheet](/hardware/briefs/hi3516cv300.pdf).
* [Hi3516ev100 Brief datasheet](/hardware/briefs/hi3516ev100.pdf).

ARM926, jpeg, mjpeg, h.264(baseline, main, high), h.265(main)

|Chip| |
|----|--|
|hi3516cv300|1920x1080@30fps encoding performance |
|hi3516ev100|1920x1080@20fps, 64MB RAM embedded|

Supported CMOSes:

* **Sony**: IMX307, IMX385, IMX290, IMX323
* **OmniVision**: OV2718
* **ON**: AR0237
* **SmartSens**: SC2235
* **UNKNOWN**: JXF22

## hi3516av100 family
* [Hi3516av100 brief datasheet](/hardware/briefs/hi3516av100.pdf).
* [Hi3516dv100 brief datasheet](/hardware/briefs/hi3516dv100.pdf).

Cortex-A7, jpeg, mjpeg, h.264(baseline, main, high), h.265(main)

|Chip| |
|----|--|
|hi3516av100|2560x1940@30fps encoding performance|
|hi3516dv100|2560x1940@15fps encoding performance|

Supported CMOSes:

* **Sony**: IMX123, IMX178, IMX117, IMX185
* **Panasonic**: MN34220
* **OmniVision**: OV4689, OV5658
* **Aptina**: AR0330
* **ON**: AR0230, AR0237

## hi3516av200 family
* [Hi3519v101 brief datasheet](/hardware/briefs/hi3519v101.pdf).
* [Hi3516av200 brief datasheet](/hardware/briefs/hi3516av200.pdf).

Cortex-A17.Cortex-A7, jpeg, mjpeg, h.264(baseline, main, high), h.265(main)

|Chip| |
|----|---|
|hi3519v101|3840x2160@30fps encoding performance|
|hi3516av200|2560x1940@30fps encoding performance |

Supported CMOSes:

* **Sony**: IMX226, IMX274, IMX290, IMX326
* **OmniVision**: OS05A10  

## Other

There is new, very powerfull chip **hi3559av100** ([brief](/hardware/briefs/hi3559av100.pdf)), but there are not real massive products based on it.
Also hardware development kit is still expensive at the moment. So, we will postpone it.

Also there is new **hi3516cv500** coming out, but still no official information.

-----

Full list of HiSilicon\`s SoCs you can get from there website\`s [products page](http://www.hisilicon.com/en/Products).
