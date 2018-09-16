# Hardware explained

## Components on PCBA

|Front side|Back side|
|----|---|
|[![](/hardware/images/explained_f_2.jpg)](/hardware/images/explained_f_2.jpg)|[![](/hardware/images/explained_b_2.jpg)](/hardware/images/explained_b_2.jpg)|

1. CMOS
1. Sysytem on Chip
2. RAM
3. SPI NOR Flash
4. Ethernet PHY
5. Quartz
6. Ethernet transformer

Other components are R, L, C and some ICs (DC-DC convertors for example).

Typical module requires 12v input (power consumption ~200mA).

## Interfaces

Usually on the PCB you can find:

* UART
* 100Mbit ethernet
* IR cut control (H-bridge for DC motor)
* USB 2.0 host
* Audio in
* Audio out
* Alarm in
* Secondary UART (typically with convertor to RS232/RS485)

## Software stack

Boot order:

* Registers init
* U-boot
* Linux kernel
* Rootfs

Fortunately these chips is very easy to run, comparing to something like MediaTek SoCs for android smartphones, where typically you will
need 2-3 steps boot process. All modules comes with original vendor software, the best choice for beginners is to keep vendor\`s 
u-boot bootloader (with registers init, that is mostly related to RAM chip installed on the PCB).

