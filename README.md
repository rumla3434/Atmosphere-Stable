# 大气层1.10.2整合包系统稳定版（更新时间：2026.01.22）

大气层1.10.2最高支持NX-21.2.0系统。如果你一直使用我发布的包，以后的更新中没有特别的提醒，都是直接覆盖就完成大气层文件的升级。

2026.01.22更新hekate_ctcaer_6.5.1_Nyx_1.9.1修复Hekate6.5.0对于部分软破Erista型号主机开机卡bootlogo的问题，更新StatusMonitor.ovl-2026.01.21。

（1）大气层1.10.2+hekate6.5.1+sigpatch都最高支持21.2.0系统，升级最新系统，所有分享出来的破解游戏资源只要本身没问题，硬件没问题，就能正常安装正常游玩，和大气层整合包系统稳定版没关系，因为稳定版大气层没有垃圾插件，不会影响游戏。

（2）建议飞行模式启动游戏，如果之前使用了linkalho假关联过任天堂账号，升级到21.0.0建议重新使用带mod版linkalho.nro重新假关联一次或者解除假关联，这样虚拟系统wifi下玩破解游戏会消除启动游戏弹窗的bug。

（3）国行的系统19.0.1或以下的必须通过tencent-switcher-gui.nro插件或者在Tesla的系统模块最下一栏把系统转区成“全球系统”后才能离线升级20.0.0+系统，否则进系统会有2162-0002（0x4a2）变砖错误，可启动Tesla菜单，在系统模块里国行按Y键改国际。需要启动Tesla菜单，可Hekate选择usb连电脑打开SD：atmosphere/，在config_templates/复制boot2.flag文件到contents/420000000007E51A/flags/就可以启动Tesla。

（4）daybreak平刷系统是没问题的，但是如果20.0+以后再降级刷系统后会出现2162-0002的nim（0100000000000025）变砖错误，可以在进系统switch图标之前按住音量加减的官方恢复模式，进行保留数据系统初始化（快速）后才能进，所以要提前备份游戏存档数据，而且初始化以后游戏要重新安装。大气层整合包向下兼容Switch系统，所以降级Switch系统并不需要更换低版本的大气层，而且正版系统升级会熔断更无法使用低版本大气层，请确认SD卡上大气层三件套组件是最新版。

# 原主页github.com/rumla34作废，改地址为github.com/rumla3434，另一个主页codeberg.org/rumla34不变。

https://github.com/rumla3434/Atmosphere-stable/releases

https://codeberg.org/rumla34/Atmosphere-stable/releases

<img src="https://github.com/rumla3434/Atmosphere-Stable/blob/master/readme.jpg?raw=true" align="center" width="100%" >
