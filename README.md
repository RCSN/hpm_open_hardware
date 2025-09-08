# 概述

主要收集先楫开发者自己基于先楫各类MCU的DIY开源硬件项目，有些可以在本仓库直接下载，有些需要在开发者自身仓库中下载。

# 板子介绍

## HPM6800_PI_V1

主要是基于HPM6800做的派板，可自行参考。文件在本仓库的HPM6800_PI_V1.zip

![](image/HPM6800_PI_V1_TOP.jpeg)

![](image/HPM6800_PI_V1_bottom.jpeg.jpeg)

## HPM6750IVM-EVK

基于hpm6750画的EVK板子，可用HPM6450等替换。文件在本仓库的HPM6750IVM-EVK.zip

![](image/HPM6750IVM-EVK_top.png)

![](image/HPM6750IVM-EVK_bottom.png)

![](image/HPM6750IVM-EVK_image.jpeg)

## HPM6800-DevKit

基于周立功的HPM6800核心板设计的HMI板子

仓库地址：[hpm68-hmi - 立创开源硬件平台](https://oshwhub.com/hasaki6/hpm68-hmi)

源码地址: https://github.com/starry-m/hpm6800-hmi

![](image/ZLG_HPM6800_CORE_board.png)

![](image/ZLG_HPM6800_CORE_board.jpeg)

## HPM6P41_BB

基于HPM6P41设计的数字电源

仓库地址：[Alipay1/HPM6P41_BB: 以HPM6P41为主控的电源开发板](https://github.com/Alipay1/HPM6P41_BB)

![](image/HPM6P41_BB.png)

## HSlink
基于HPM5301的DAP调试器
仓库地址：https://github.com/HSLink/HSLink_Hardware

![](image/hslink.png)

## HPM6360-测试板

基于HPM6360的开发板
仓库地址：[hpm6360-ce-shi-ban - 立创开源硬件平台](https://oshwhub.com/hasaki6/hpm6360-ce-shi-ban)

![](image/hpm6360-ce-shi-ban_top.png)

![](image/hpm6360-ce-shi-ban.png)

## HPM5361MiniFOC

基于HPM5361高性能国产RV内核MCU的迷你FOC驱动器
仓库地址：[HPM5361MiniFOC - 立创开源硬件平台](https://oshwhub.com/lx050724/hpm5361foc)
代码链接：https://github.com/LX050724/HPM5361MiniFOC

![](image/HPM5361MiniFOC_top.png)

![](image/HPM5361MiniFOC_board.jpeg)


## HSCanT

- HSCanT 是一款USB转4路CAN FD工具，基于HPM5321芯片设计
  - 支持4路CAN FD通道
  - 每路CAN FD通道支持最高8Mbit/s的数据传输速率
  - 支持上位机配置可选的120Ω终端电阻
  - 每路通道均支持独立的TX、RX状态全彩LED指示
  - 支持最高±58V的过压保护

仓库地址：[HSCanT](https://github.com/HalfSweet/HSCanT)

![](image/HScanT-image.jpg)
![](image/HCanT_top.png)

## HSDevKit5301

- 基于hpm5301设计的开发板

仓库地址：[HSDevKit5301](https://github.com/HalfSweet/HSDevKit5301)

![](image/HSDevKit5301_image.jpg)
![](image/HSDevKit5301_top.png)

## OSBDM/OSJTAG for Qorivva MPC55xx/56xx
基于 HPM5301 的 OSBDM 调试器，适用于 NXP 和 ST 的 PowerPC 内核单片机。

仓库地址：
https://github.com/zhangjinke/osbdm_hpm5301_hardware
https://github.com/zhangjinke/osbdm_hpm5301_software

![](image/OSJTAG.jpg)

## HPM6284Foc

- 基于HPM6284的FOC驱动器


- 仓库地址：[HPM6284Foc](https://github.com/LX050724/HPM6284Foc.git)

![](image/HPM6284Foc_board.jpg)

![](image/HPM6284Foc_top.png)

![](image/HPM6284Foc_buttom.png)


## HPM5E31-KIT
- 基于hpm5e31的EtherCAT开发板，板载HSLINK，本板子对应IPB-TINY Board，使用树莓派40PIN引出IO

- 仓库地址：[HPM5E31-KIT](https://oshwhub.com/hasaki6/hpm5e31-kit)

![](image/HPM5E31-KIT_TOP.png)

![](image/HPM5E31-KIT_buttom.png)

## miniHslink

- 基于HPM5301 迷你版Hslink硬件
- 仓库地址：[miniHslink](https://github.com/KotoriProject/miniHslink)
![](image/mini-hslink.png)

## LuckyCAT

- LuckyCAT是一款采用先辑半导体 HPM5E31 芯片，支持EtherCAT主从站开发的工业嵌入式开发板，适用于刀片IO、PLC、伺服电机等工业嵌入式应用，主频高达480MHz，能满足复杂的逻辑设计需求，采用全国产化设计，原理图PCB全开源，提供入门资料和视频方便新手快速上手开发

- 仓库地址：
    - github
        - https://github.com/coinlockerbaby/LuckyCAT_HardWare
        - https://github.com/coinlockerbaby/LuckyCAT_SoftWare
    - 立创开源硬件平台：https://oshwhub.com/undefined-innovation/hpmduino_dev

![](image/LuckyCAT_top.png)

![](image/LuckyCAT.png)

## HPM5E-EC-DEV 先楫Ethercat开发板

- 基于先楫HPM5E31IPB1的Ethercat开发板，将Ethercat P0/P1和千兆以太网接口引出，板载LCD、DS18B20、蜂鸣器、USB OTG、串口、CAN等外设

- 仓库地址：[HPM5E-EC-DEV 先楫Ethercat开发板](https://oshwhub.com/azure2024/hpm5e-ec-dev-public)

![](image/hpm5e_ec_dev_top.png)

![](image/hpm5e_ec_dev.png)


## 基于HPM6750的lambda-pi

- 基于HPM6750的开发板，版型参考ART-PI，原理图参考了HPM6750EVK2和HPM6750EVKMINI开发板，板载HSLINK烧录器和多种常用外设，引出74个IO口

- 仓库地址：[基于HPM6750的lambda-pi](https://oshwhub.com/zhaowenbin/lambda-pi)

![](image/lambda-pi-top.png)

![](image/lambda-pi-buttom.png)

![](image/lambda-pi-3d.png)

