# **msi-b360m-mortar_i5-9400_efi**

处理器|英特尔 Core i5-9400 @ 2.90GHz 六核
--|:---
主板|微星 B360M MORTAR (MS-7B23) ( B360 芯片组 )
显卡|英特尔 UHD Graphics 630 ( 128 MB / 微星 )
内存|16 GB ( 金士顿 DDR4 2666MHz )
主硬盘|西数 WDC WDS480G2G0B-00EPW0 ( 480 GB / 固态硬盘 )
声卡|瑞昱 ALC892 @ 英特尔 High Definition Audio 控制器
网卡|英特尔 Ethernet Connection  I219-V / 微星
蓝牙|bcm94360cd

- 支持MacOS 10.15.4
- opencore 0.5.6
- 添加windows引导，因为该主板不支持原生NVRAM，所以保留了opencore引导界面，如果是只安装了MacOS可以关闭引导项选择界面，开机自动进入MacOS
- ***clover版本请切换到clover分支***
---
说明：本EFI文件是给予基于其他大佬提供打EFI文件修改，但是使用的显卡、CPU等硬件不一样，我又做了部分修改，以适用于自己的配置
>https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI