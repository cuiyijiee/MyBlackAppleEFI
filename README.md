# MyBlackAppleEFI
我的黑苹果Clover EFI配置

# 我为什么要弄一台黑苹果
家境贫寒，价格劝退。（说到贫寒我就想起了宋濂的《送东阳马生序》吾家贫，无从致mac以用。🌹🐔）

# 主板设置
更新了最新bios(version:2012)的主板需要前往bios中更改
```
Advanced —> Onboard Devices Configuration-Serial Port Configuration Serial Port —> Off
Advanced —> USB Configuration-XHCI Hand-off —> Enabled
Secure Boot -> OS Type -> Other OS
Advanced —> PCH configuration-IOAPIC 24-119 Entries —> disabled
CFG-LOCK -> disabled
Advanced -> Advanced PCH Configuration -> system time and alarm source -> Legacy RTC
```

# 配置如下

| 项目        | 配置   |
| --------   | :-----  |
| CPU         | 英特尔（Intel）i5-9600K | 
|内存         |美商海盗船（CORSAIR） 复仇者8G DDR4 2666 X2|
| 主板        |   华硕（ASUS）TUF B360M-PLUS GAMING S   | 
| 显卡        |    蓝宝石（SAPPHIRE）RX470 4G DDR5超白金（闲鱼入的锻炼卡）    | 
| 硬盘        |    惠普（HP） EX900系列 250G M.2 NVMe SSD    | 
|无线网卡|BCM94360CS2 (免驱WIFI和蓝牙)|

# 问题解决

- [x] 显卡免驱完美
- [x] 有线以太网卡完美
- [x] 声卡（有声音，可使用siri）
- [x] 使用独显后无法使用预览查看JPG图片
- [x] USB3.1完美
- [x] 完美睡眠唤醒
- [x] 可登陆icloud，app store正常
- [x] 已经完美更新到`mojave10.14.5`

# BUG
- [x] 有时启动没有声音，待查明原因(已解决,更新了声卡驱动)
