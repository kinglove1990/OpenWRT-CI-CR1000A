# OpenWRT-CI
云编译OpenWRT固件
源码：
[VIKINGYFY/immortalwrt](https://github.com/VIKINGYFY/immortalwrt.git)
[tsg2k2/openwrt](https://github.com/tsg2k2/openwrt)

# 硬件配置：

CPU: IPQ8072A
RAM: 2GB
EMMC: 4GB
Switch Chip: RTL9303
10G Chip: 2 x AQC113C
2.5G Chip:2 x RTL8221B
Radio 1: QCN5054
Radio 2: QCN6024 (4x4 5G 4800Mbps)
Radio 3: QCN9024 (4x4 6G 4800Mbps)

# 固件问题：

- 10g WAN口识别正常,我只有2.5g,速率不知道
- 三频无线正常，国家选择US，能有30dB
- 6E的无线可以降频5.2g使用，能跑到2400M
- NSS 硬件加速正常
- 10g LAN口正常,rtl9303交换机初始化了就正常，没有初始化就不能识别

# 固件简要说明：

- 带HP、Mihomo mosdns等简单几个软件，具体的自己看config

# 目录简要说明：

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置
