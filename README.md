# hackintosh-dell-G3-3590
戴尔G3-3590引导系统  
`Opencore v0.7.0`


### 硬件配置
- 处理器：第 9 代 Intel®️ 核™️i7 -9750H（12MB 高速缓存，最高 4.5 GHz，6 核）
- 核显：Intel(R) UHD Graphics 630
- 独显：GeForce GTX 1660 Ti Mobile
- 内存：4G, 16G, DDR4（2666MHz）
- 硬盘: 东芝 NVMe 512GB, 三星 SSD 860 EVO 1TB
- 音频编解码器: 瑞昱ALC295
- WIFI & 蓝牙: Intel(R) AX200
- 以太网卡：Realtek RTL8168H/8111H
- 触摸板：I2C HID TPD0
- 启动模式：UEFI
- Open Core 版本：0.7.0
- OS 版本：macOS BigSur 11.4

### 可以工作
- 核显
- 重新启动、睡眠和关机 (接外接显示器时唤醒灰屏，需要插拔一下外接HDMI)
- CPU 电源管理
- 内置扬声器、耳机（带麦克风）
- 触摸板
- 电池指示器
- 以太网
- WIFI & 蓝牙
- 所有 USB 端口（包括 type-c, type-c可以加个扩展坞外接显示器）

### 不能工作
- 内置麦克风


### 其它问题
 接外接显示器时唤醒灰屏，需要插拔一下外接HDMI.如果不需要外接显示器，可以 [禁用独立显卡](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/laptop-disable.html)   
 或者找找有没有其它大神可以解决