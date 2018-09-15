# Overview of chinese cctv market

This overview doesn`t cover all video surveilliance market. It covers some part of market that is related to China, 
as China is largest supplier of such devices all over the world.
Big part of information was gotten from talks with Security Market ([HuaQuanBei](https://en.wikipedia.org/wiki/Huaqiangbei) area) sellers. 
Also some info came from security exhibitions in Shenzhen (Guangdong, China). 
Mostly information applicable to low-end and middle-end segments of market.

## Chip makers

**Chip maker** means company that develop and produce specialized System on Chips (or just chips). 
There aren`t so much such companies. Here's our list of companies whose chips we've seen.

- [Hisilicon](http://www.hisilicon.com/)
- [Texas Instruments](http://www.ti.com/) 
- [GrainMedia](http://www.grain-media.com/)
- [Ambarella](https://www.ambarella.com/)
- [XM](http://www.xiongmaitech.com/)

**Texas Instruments** DM365, DM368 modules were widely exist on the market about 5 years ago. 
Some their more advanced SoC DM8127 were used by [HikVision](https://www.hikvision.com/) in their exclusive hardware platforms.
Now seems they exist only in high-end segment.

**Ambarella** were exist on the market several years ago, but now seems moved their focus for action cameras and car DVRs. 
According their website they still have ip camera SoC, but seems they used not very widely and exist only in high end segment.

**GrainMedia** is a new player, they jumped in a few years ago with series of extreamly low-end solutions.

During late 2017/beginning of 2018 **XM** introduces camera modules based on their own SoC. There are no public technical info about it at the moment.

As about **HiSilicon**, that is part of Huawei corporation, their chips have firmly occupied low-end and middle-end segments. 
Сompared to competitors, HiSilicon doesn`t care much about hiding their SDKs and it can be obtain without NDA and other bullshit.  

## Camera modules manufacturers

Based on HiSilicon\`s reference design companies make camera modules. As mostly everything is included inside System on a Chip, there are no
area to creative ideas (we are really lucky:sweat_smile:). There are mostly nowhere developer of the camera PCB can implement his own
vision. The only thing that will be under developer\`s control is which interfaces to use on target module, like additional UART or 
USB host.

### Most known companies: 

- [XM](http://www.xiongmaitech.com/) - very popular one, if you will dissamble chinese ip camera most probably their module is inside.
- [JVT](http://www.jvt.cc/) - this one faster than others introduces solutions based on new chips.
- [TopSee](http://www.tpsee.com/) - another one, that has english version of website.
- There are others, search [taobao](https://taobao.com) to find some.

Usually such companies not only sell camera modules alone, but also offer modules inside cases with attached lens:point_down:.

## Camera as product for the end user

When normal people hear ip camera, they think about some box with optical lens. 
But still the end user camera is the same camera module inserted in metal (sometime plastic) case. 
Case itself performs function of lens holder and protection for PCB. 
Sometimes it is a bit more complicated when PoE comes into game or lens is motorized, but it is out of this article`s scope.

A lot of chinese companies buy components (cases, lens, camera module PCB, wires, screws), assemble all together, print logo and pack inside fancy box. 
Obvious that all such companies produce completely same devices, that just looks like different.

This is applicable to most HiSilicon based devices.
