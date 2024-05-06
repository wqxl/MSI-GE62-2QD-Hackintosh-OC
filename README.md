# MSI-GE62-2QD Hackintosh whith OpenCore
## macOS
```bash
macOS Ventura 13.6.6(22G630)
```

## OpenCore
```bash
OpenCore-0.9.9-DEBUG
```

## 硬件信息
```bash
机型: MSI GE62-2QD
主板: 微星 MS-16J2
CPU: Intel i7-5700HQ
CPU架构: Broadwell
GPU: Intel HD Graphics 520 / NVIDIA GeForce GTX 960M
芯片组: Intel HM87
硬盘: 镁光 256 GB
内存: 三星 DDR3L 1600MHz 8GB / 金士顿 DDR3L 1600MHz 8GB
键盘: SteelSeries PS/2
声卡: Realtek ALC892
有线网卡: Killer Gb
无线网卡: Intel Dual Band Wireless AC 3160
```

## 功能
```bash
1、有线网卡正常
2、无线网卡正常
4、鼠标正常
3、触摸板正常
5、声卡没解决
6、核显和独显都没解决
```

## 说明
```bash
1. opencore和所有的kexts文件全部都是debug版本，方便调试。如果调试没有问题，可以全部换成release版本。
2. 完全按照opencre install guide安装手册一步一步搞就可以，无需参考其他教程。
3. 按照opencre install guide安装手册安装时，发现只能在线安装macos，离线安装macos识别不了dmg文件。
4. HideAuxiliary参数一定要设置为false，否则会导致opencore引导界面无法显示macos安装选项。
5. 生成平台信息最好选择MacBookPro15以上，否则引导会卡在EB报错。
```

## 参考
- [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [OpenCore安装指南](https://sumingyd.github.io/OpenCore-Install-Guide/)