# Hackintosh-Dell-g3-15-3590<br>

## Laptop Specifications

Model     | Dell g3 15 3590 9<sup>th</sup> gen
---       | ---
Processor | Intel®️ Core™️ i5-9300H
iGPU      | Intel UHD 630
dGPU      | NVIDIA(R) GeForce(R) GTX 1650
Resolution| 15.6 inch FHD (1920 x 1080) 30 0 nits IPS Anti-Glare LED Back lit Display with 144Hz refresh rate
RAM       | 16GB, 2x8GB, DDR4 (2666MHz) 
Storage   | 128GB M.2 PCIe NVMe Solid State Drive (Boot) + 1TB 5400 rpm 2.5" SATA Hard Drive (Storage)
Audio     | Realtek ALC295
WIFI      | Intel AC9560 
Touchpad  | I2C1 HID TPD0
Bios      | 1.9.0 `Recommended`




## System configuration

Model | `MacBookPro16,4` | OS | `macOS Ventura（最新系统）` | OC | `0.8.4`
---|---|---|---|---|---



##什么是有效的
✅QE/CI 显卡英特尔 UHD 630
✅重新启动、睡眠和关机（带或不关闭盖子）
✅中央处理器电源管理

✅内置扬声器、耳机（带麦克风）

✅触摸板（SSDT Patche 中断 GPIO 固定）“请注意，acpibattery.kext 会导致触摸板滞后，使用 smcbatterymanager.kext 修复了该问题”

✅亮度（包括 f11 和 f12）
✅电池指示灯
✅以太网
✅无线上网
✅蓝牙

✅所有 USB 端口（包括 USB 类型 c）
✅外接显示器使用 C 型电缆
✅prtScr 键禁用触摸板和 winKey + prtScr 禁用键盘

##什么不起作用
❌内置麦克风（Mac 不支持智能声音技术）
❌GTX 1650
