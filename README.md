# 大气层1.10.0整合包系统稳定版（更新时间：2025.11.21）

大气层1.10.0最高支持NX-21.0.0系统。如果你一直使用我发布的包，以后的更新中没有特别的提醒，都是直接覆盖就完成大气层文件的升级。

2025.11.21更新DBI.nro--v842俄文版（同文件夹下重命名DBI.nro.cn是时大佬的汉化版DBI843，可手动重命名替换DBI.nro），NX-Activity-Log.nro--v1.5.7mod，wiliwili.nro--v1.5.2mod，删除tinfoil.nro，整合包里所有插件和相册里的软件都可以在21.0.0系统里正常使用了。

2025.11.20更新atmosphere-1.10.0-prerelease-d9fc6e99e，hekate_ctcaer_6.4.1_Nyx_1.8.1汉化版，Sigpatches for Atmosphere 1.10.0（nim未更新，联网有90dns挡在前面不会报错），更新Lockpick_RCM.bin--v1.9.16，更新Z大佬的Ultrahand-Overlay及全套Tesla插件最新版，更新相册Awoo-Installer，Checkpoint，DBI842俄文版，DeepSea-Toolbox，Edizon，Goldleaf，JKSV.nro--11.16.2025，linkalho.nro--v2.0.2修复bug版本。以上都支持21.0.0|AMS 1.10.0

（1）大气层1.10.0+hekate6.4.1+sigpatch都最高支持21.0.0系统，关于20.0.0+系统出现wifi联网待机耗电多的情况，见教程「分享」20.0.0+系统wifi联网待机耗电异常有效解决办法，可以有效解决，但是启动飞行模式待机还是最省电的。

（2）国行的系统19.0.1或以下的必须通过tencent-switcher-gui.nro插件或者在Tesla的系统模块最下一栏把系统转区成“全球系统”后才能离线升级20.0.0+系统，否则进系统会有2162-0002（0x4a2）变砖错误，可启动Tesla菜单，在系统模块里国行按Y键改国际。需要启动Tesla菜单，可Hekate选择usb连电脑打开SD：atmosphere/，在config_templates/复制boot2.flag文件到contents/420000000007E51A/flags/就可以启动Tesla。

（3）已经升级了20.0+的真实或虚拟系统都没必要降级19.0.1，daybreak降级后容易出现nim（0100000000000025）变砖错误，可以在进虚拟系统switch图标之前按住音量加减的官方恢复模式，进行保留数据系统初始化（快速）后才能进19.0.1。大气层整合包向下兼容Switch系统，所以降级Switch系统并不需要更换低版本的大气层，而且正版系统升级会熔断更无法使用低版本大气层，请确认SD卡上大气层三件套组件是最新版。

<img src="https://github.com/rumla3434/Atmosphere-Stable/blob/master/readme.jpg?raw=true" align="center" width="100%" >
