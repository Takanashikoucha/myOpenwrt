# 自用R4A千兆版固件

- 【适合使用】支持ipv6、使用美观的主题、解锁uboot等分区
- 【适合养老】精简大部分用不上的插件
- 【调教完善】使用fork后修改的源码，可breed直刷，并尝试调用闭源驱动
- 【需要注意】注意开机时wifi不会同时启动，需要在启动项脚本里添加 `mtkwifi reload`，固件TruboACC采用sfe（高通？）而非HWNAT（mt的硬件加速）

默认：root/password 192.168.31.1

如需下载请到actions查看最新的编译情况，或者到release界面下载
