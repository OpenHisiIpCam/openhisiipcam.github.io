# Overview of HiSilicon`s SoCs for ip cameras

We splitted chips in groups, that we call *family*. Chips in a family have same CPU architecture, share same vendor SDK and 
usually differs in only video processing capability terms. 

Here you can find list of avalible chips. We point only to video encoding performance. 
Actually, chips not only different in video encoding performance, but also different in advanced encoding settings (like intra refresh), 
processing and video analytics capabilities.

## hi3515v100 family

* [Hi3515V100 brief datasheet](/hardware/briefs/hi3515v100.pdf).

ARM926, jpeg, mjpeg, h.264 (baseline, main). Ip camera / DVR combined SoC.


|Chip| |
|----|--|
|hi3515v100|1280x720@30fps encoding performance|


## hi3516cv100 family 

* [Hi3518av100 brief datasheet](/hardware/briefs/hi3518av100.pdf).
* [Hi3518ev100 brief datasheet](/hardware/briefs/hi3518ev100.pdf).
* [Hi3516cv100 brief datasheet](/hardware/briefs/hi3516cv100.pdf).

ARM926, jpeg, mjpeg, h.264 (baseline, main)

|Chip| |
|----|--|
|hi3516cv100|1920x1080@30fps encoding performance|
|hi3518cv100|1280x720@30fps encoding performance|
|hi3518ev100|same as hi3518cv100, but 32MB RAM embedded|
|hi3518av100|**???**|

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

## hi3559av100 family

* [hi3559av100[es] brief](/hardware/briefs/hi3559av100.pdf)
* [hi3559cv100 brief](/hardware/briefs/hi3559cv100.pdf)

2xMali-G71+1xCortex-M7+1xCortex-A53+(2xCortex-A73.2xCortex-A53) for hi3559av100[es], 2xCortex-A53 for hi3519av100

|Chip| | |
|----|---|--|
|hi3559av100|7680 x 4320@30fps encoding performance| 2xNNIE+4xDSP |
|hi3559av100es|7680 x 4320@30fps encoding performance| 1xNNIE+2xDSP |
|hi3559cv100| **???** | **???** |

Supported CMOSes:

* **Sony**: IMX290, IMX334, IMX377, IMX477

## hi3519av100 family

* [hi3519av100 brief](/hardware/briefs/hi3519av100.pdf)

Dual-core ARM Cortex-A53

|Chip| | |
|----|---|--|
|hi3519av100|3840 x 2160@60fps encoding performance| 1xNNIE+1xDSP |


## hi3516cv500 family

* [hi3516cv500 brief](/hardware/briefs/hi3516cv500.pdf)
* [hi3516dv300 brief](/hardware/briefs/hi3516dv300.pdf)

Dual-core ARM Cortex-A7@ 900 MHz

|Chip| | |
|----|---|--|
|hi3516cv500| 2MP@30 fps encoding | |
|hi3516dv300| 5MP@30 fps encoding | |


## Discounted

* **hi3519v100**

-----

Full list of HiSilicon\`s SoCs you can get from there website\`s [products page](http://www.hisilicon.com/en/Products).

