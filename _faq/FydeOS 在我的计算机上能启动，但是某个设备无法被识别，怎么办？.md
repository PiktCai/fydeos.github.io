---
anchor: fydeos-can-start-on-my-computer-but-a-device-cannot-be-recognized-what-should-i-do
weight: 996
lang: zh_CN
---
FydeOS 致力于适配并且兼容更多的硬件设备和外接设备。由于 Chromium OS 系统结构的特殊性，FydeOS 目前对非主流、未提供主线 Linux 内核驱动以及对主流 Linux 发行版支持不完善的硬件设备兼容性较弱。

这里的「某个设备」可能包括但不限于：
 - 无线网卡
 - 以太网卡
 - 声音
 - 打印机
 - 耳机插孔自动识别
 - 触控板
 - 触屏
 - 手写笔
 - 指纹识别器
 - 摄像头
 - 重力感应模块
 - 电池余量显示
 - 电源管理策略
 - 其它特有的外接设备

如果你发现你的「某个设备」无法在 FydeOS 上被识别导致功能缺失，可以在你的设备上尝试运行 [Ubuntu Desktop](https://cn.ubuntu.com/desktop/) 来检测该设备对 Linux 系统的兼容性。若出现在 Ubuntu 下能被识别及能正常工作而在 FydeOS 下失灵的情况，欢迎至我们的[中文社区](https://community.fydeos.com/)发帖求助并提供详细的硬件信息以帮助我们的开发团队进一步完善硬件兼容性。

另外，FydeOS for PC 在 x86 体系的 Chromebook 设备上也会出现不同程度的适配问题，因为 FydeOS 在构建的时候试图加入对更多 PC 设备的支持，为此去掉了上游项目对 Chromebook 的特殊优化。对于还在支持期间的 Chromebook 设备，我们仍然推荐使用 Google Chrome OS 已获得最佳体验。