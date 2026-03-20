# 大气层1.10.3整合包系统稳定版（更新时间：2026.03.20）

大气层1.10.3最高支持NX-21.2.0系统，如果你一直使用我发布的包，以后的更新中没有特别的提醒，都是直接覆盖就完成大气层文件的升级。

2026.03.20大气层1.10.3最高支持NX-21.2.0系统，但配合hekate6.5.2可以引导真实（正版）22.0.0系统，引导虚拟或真实（破解）21.2.0或以下系统也不会有休眠死机bug。更新hekate_ctcaer_6.5.2_Nyx_1.9.2，更新atmosphere-1.10.3-2200_support-3aa9c7450和对应的loader patch，更新Lockpick_RCM.bin--v1.9.18，Checkpoint.nro--v3.12.0，新增熔断23的wb_17.bin补丁。等atmosphere更新支持22.0.0后再看是否有新的es/fs等sigpatch。当下最高只支持真实破解系统21.2.0，虚拟破解系统21.2.0和真实正版系统22.0.0。只有误升级正版系统的Switch可以更新此版本整合包，虚拟系统不可以升级22.0.0，等atmosphere更新支持再升级。

如果新人入手新机并升级22.0.0后想做破解和虚拟系统，不能直接降级虚拟系统到21.2.0，只有（1）等大气层更新支持22.0.0再去破解和制作虚拟系统。（2）通过hekate提取本主机prod.keys和本主机EMMC的prodinfo分区，制作一个21.2.0的系统固件线刷降级才行。所以新人建议耐心等几天。

（1）大气层1.10.3+hekate6.5.2+sigpatch都最高支持21.2.0系统，升级最新系统，所有分享出来的破解游戏资源只要本身没问题，硬件没问题，就能正常安装正常游玩，和大气层整合包系统稳定版没关系，因为稳定版大气层没有垃圾插件，不会影响游戏。

（2）建议飞行模式启动游戏，如果之前使用了linkalho假关联过任天堂账号，升级到21.0.0建议重新使用带mod版linkalho.nro重新假关联一次或者解除假关联，这样虚拟系统wifi下玩破解游戏会消除启动游戏弹窗的bug。

（3）国行的系统19.0.1或以下的必须通过tencent-switcher-gui.nro插件或者在Tesla的系统模块最下一栏把系统转区成“全球系统”后才能离线升级20.0.0+系统，否则进系统会有2162-0002（0x4a2）变砖错误，可启动Tesla菜单，在系统模块里国行按Y键改国际。需要启动Tesla菜单，可Hekate选择usb连电脑打开SD：atmosphere/，在config_templates/复制boot2.flag文件到contents/420000000007E51A/flags/就可以启动Tesla。

（4）daybreak平刷系统是没问题的，但是如果20.0+以后再降级刷系统后会出现2162-0002的nim（0100000000000025）变砖错误，可以在进系统switch图标之前按住音量加减的官方恢复模式，进行保留数据系统初始化（快速）后才能进，所以要提前备份游戏存档数据，而且初始化以后游戏要重新安装。大气层整合包向下兼容Switch系统，所以降级Switch系统并不需要更换低版本的大气层，而且正版系统升级会熔断更无法使用低版本大气层，请确认SD卡上大气层三件套组件是最新版。

# 原主页github.com/rumla34作废，改地址为github.com/rumla3434，另一个主页codeberg.org/rumla34不变。

https://github.com/rumla3434/Atmosphere-stable/releases

https://codeberg.org/rumla34/Atmosphere-stable/releases

<img src="https://github.com/rumla3434/Atmosphere-Stable/blob/master/readme.jpg?raw=true" align="center" width="100%" >
