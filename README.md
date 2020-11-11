# LabVIEW-BLE-Examples
## Brief/简介
  A example **base on LabVIEW-BLE-Driver**,which can help you to **communicate between LV and BLE Bluetooth devices**(eg:STM32+RF-BM-4044B4(CC2640R2F)).
> 基于LabVIEW-BLE-Driver项目的LV与BLE蓝牙设备（如STM32+RF-BM-4044B4模块(CC2640R2F)）的通信例程。

  **Thanks** for the open source driver and simple routines of [prabubharathi85/LabVIEW-BLE-Driver](https://github.com/prabubharathi85/LabVIEW-BLE-Driver) project.
> 感谢 [prabubharathi85/LabVIEW-BLE-Driver](https://github.com/prabubharathi85/LabVIEW-BLE-Driver) 项目的开源驱动及简单例程。

## Function/功能
  Realizing the communication between LabVIEW and BLE Bluetooth device and it is very convenient to use. The examples include "Bluetooth search connection", "read and write to target device", "string data conversion and extraction" and so on.
> 实现LabVIEW与BLE蓝牙设备的通信，使用非常方便。实例内具体包括“蓝牙搜寻连接”、“对目标设备读写”、“字符串数据转换提取”等实现。

## Development environment/开发环境
  Win10 operating system + LabVIEW 2020 (or above), does not support NXG and traditional LabVIEW below 2020.
> Win10 操作系统+LabVIEW 2020（或以上（~~好像暂时没有以上~~）），不支持NXG和2020以下的传统LabVIEW。
~~剩下的Readme我晚点再补~~

## Usage/用法
  (Please understand the related knowledge of BLE Bluetooth communication protocol) First, run the routine to search for the address information of the target BLE device, such as (80:6F:B0:35:C4:BF and 141217186038975), and you will get a 15-bit address code modified in The part required by the program will automatically find and connect to the device thereafter.Please remember to read through the program and modify the functions you need.
> （请先了解BLE蓝牙的通信协议相关知识）先运行例程，搜寻目标BLE设备的地址信息，如（80:6F:B0:35:C4:BF和141217186038975），将得到15位地址码修改于程序需要的部分，此后会自动寻找与连接该设备。
请记得通读程序，修改好自己所需的功能。

## Remarks/备注
简单写了下Readme，我先去吃饭了。
