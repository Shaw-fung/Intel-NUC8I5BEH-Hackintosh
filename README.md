# Intel-NUC8I5BEH-Hackintosh

[![OpenCore version](https://img.shields.io/badge/OpenCore-0.8.1-blueviolet.svg)](https://github.com/acidanthera/OpenCorePkg) [![MacOS version](https://img.shields.io/badge/Monterey-12.5%2021G72-blueviolet.svg)](https://www.apple.com/macos) 
***
## 电脑配置
| 电脑型号 | NUC8I5BEH |
| :----: | :----:  | 
| 操作系统 | macOS Monterey / Big Sur  |
| 处理器 | Intel® Core™ i5-8259U Processor (6M Cache, up to 3.80 GHz) |
| 内存| 32 GB 2400 MHz DDR4 |
| 硬盘 | Samsung SSD 970 EVO Plus |
| 显卡 | Intel Iris Plus Graphics 655 |
| 声卡 | Realtek ALC235 alcid=14 |
| 无线网卡+蓝牙	 | Intel® Wireless-AC 9560 + Bluetooth 5.0 |
| 有线网卡 | Intel I219V6 PCI Express Gigabit Ethernet |	
***
## BIOS设置
- BIOS版本089
- 升级BIOS -> load BIOS defaults -> click advanced and change;
- Devices -> USB -> Port Device Charging Mode: off
- Devices -> USB -> USB Legacy -> Disabled
- Boot -> Boot Configuration -> Network Boot: Disable
- Boot -> Secure Boot -> Disable
- Security -> Thunderbolt Security Level: Legacy Mode
- Power -> Wake on LAN from S4/S5: Stay Off
***
## 安装说明
- 目前建议安装Monterey，当然Big Sur也可以安装
- opencore版本0.8.1
- 系统安装完成后自己修改序列号等相关配置
***
如果有问题，欢迎提交提问讨论，[我要提交问题](https://github.com/Shaw-fung/Intel-NUC8I5BEH-Hackintosh/issues/new)！
***
## 安装Monterey、Big Sur成功截图如下：
### Monterey：
![avatar](https://github.com/Shaw-fung/Intel-NUC8I5BEH-Hackintosh/blob/main/screenshots/Monterey.png?raw=ture)
***
### Big Sur：
![avatar](https://github.com/Shaw-fung/Intel-NUC8I5BEH-Hackintosh/blob/main/screenshots/Big%20Sur.png?raw=true)
****
## 更新日志
#### 2022-7-22
- 目前版本EFI可以在线升级到12.5（21G72）
#### 2022-6-9
- 升级OpenCore到0.8.1
- 现在EFI可以在线升级到12.4 (21F79)
- 修复蓝牙问题
#### 2022-04-1
- 现在EFI可以在线升级到12.3.1 (21E258)
#### 2022-3-19
- Monterey可以在线升级到12.3 (21E230)
#### 2022-2-24
- Monterey可以在线升级到12.2.1 (21D62)
#### 2021-11-12
- 支持Big sur及monterey安装
- 支持读卡器使用
- 完美睡眠
- intel WiFi及蓝牙可以使用
