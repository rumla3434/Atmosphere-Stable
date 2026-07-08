# 大气层1.11.2整合包系统稳定版（更新时间：2026.07.08）

大气层1.11.2最高支持NX-22.5.0系统，如果你一直使用我发布的包，以后的更新中没有特别的提醒，都是直接覆盖就完成大气层文件的升级。

2026.07.08更新hekate的nyx.bin汉化文件，更新Z大佬的Ultrahand-Overlay及全套Tesla插件，更新Checkpoint.nro--v3.13.0，DBI.nro--v898，DowngradeFixer.bin--v1.0.1，一键清理contents的旧插件和删主题20260708更新。

（1）大气层1.11.2+hekate6.5.3+sigpatch都最高支持22.5.0系统。国行的系统19.0.1或以下的必须通过tencent-switcher-gui.nro插件或者在Tesla的系统模块最下一栏把系统转区成“全球系统”后才能离线升级20.0.0+系统，否则进系统会有2162-0002（0x4a2）变砖错误，可启动Tesla菜单，在系统模块里国行按Y键改国际。需要启动Tesla菜单，可Hekate选择usb连电脑打开SD：atmosphere/，在config_templates/复制boot2.flag文件到contents/420000000007E51A/flags/就可以启动Tesla。

（2）daybreak平刷系统是没问题的，但是如果20.0+以后再降级刷系统后会出现2162-0002的nim（0100000000000025）变砖错误，可以在进系统switch图标之前按住音量加减的官方恢复模式，进行保留数据系统初始化（快速）后才能进，所以要提前备份游戏存档数据，而且初始化以后游戏要重新安装。大气层整合包向下兼容Switch系统，所以降级Switch系统并不需要更换低版本的大气层，而且正版系统升级会熔断更无法使用低版本大气层，请确认SD卡上大气层三件套组件是最新版。

# 大气层版本怎么选？

看主机熔断数，Switch升级正版系统没有回头路，主机熔断不可逆，大气层版本是对应SW系统支持破解。

比如某个时间节点大气层1.11.0最高支持NX-22.0.0系统，当前主机正版系统21.0，虚拟系统21.0或19.0或更低，熔断=22，使用大气层1.10.2整合包。

如果升级正版系统到22.0，触发熔断23，只能换成大气层1.11.0的整合包，即使你降级正版系统到21.2，以后也只能用大气层1.11.0或更高版本大气层整合包。

如果升级虚拟系统到22.0，不会熔断，你可以先换成大气层1.11.0，顺利进虚拟系统，然后daybreak降级到21.2后再换大气层1.10.2整合包。

# 原主页github.com/rumla34作废，改地址为github.com/rumla3434，另一个主页codeberg.org/rumla34不变。

https://github.com/rumla3434/Atmosphere-stable/releases

https://codeberg.org/rumla34/Atmosphere-stable/releases

<img src="https://github.com/rumla3434/Atmosphere-Stable/blob/master/readme.jpg?raw=true" align="center" width="100%" >
