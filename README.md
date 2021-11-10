# Intel-NUC8I5BEH-Hackintosh
## 电脑配置
|  | |
| :----: | :----:  | 
| 电脑型号 | NUC8I5BEH |
| 操作系统 | macOS Big Sur / Monterey |
| 处理器 | Intel® Core™ i5-8259U Processor (6M Cache, up to 3.80 GHz) |
| 内存| 32 GB 2400 MHz DDR4 |
| 硬盘 | Samsung SSD 970 EVO Plus |
| 显卡 | Intel Iris Plus Graphics 655 |
| 声卡 | Realtek ALC235 alcid=14 |
| 无线网卡+蓝牙	 | Intel® Wireless-AC 9560 + Bluetooth 5.0 |
| 有线网卡 | Intel I219V6 PCI Express Gigabit Ethernet |	
***
## BIOS设置
- BIOS版本
 ### Disable
 - Legacy Boot
- Fast Boot
- Network Boot
- Secure Boot
- Inter VT for directed I/VO(VT-d)
### Enable
- Boot USB Devices First
- Boot Network Devices Last
- Wake on LAN from S4/S5
- Stay Off
***
## 安装说明
- Monterey由于蓝牙框架改动，需要使用新的蓝牙驱动，需要将原IntelBluetoothInjector.kext开机加载取消，改用BlueToolFixup.kext开机加载。IntelBluetoothFirmware.kext这个不需要变动，仍然保持开机加载。

- Monterey安装的时候如需要启动自带WiFi，则需要将AirportItlwm.kext这个文件开机加载取消，改用开机加载AirportItlwm_v2.0.0_stable_Monterey.kext.kext这个驱动，然后就可以正常使用自带WiFi驱动。

## 更新日志
#### 2021-11-10
- 支持Big sur及monterey
- 支持读卡器使用
- 完美睡眠
- intel WiFi及蓝牙可以使用