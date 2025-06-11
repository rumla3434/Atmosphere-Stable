# 大气层1.9.1整合包系统稳定版（更新时间：2025.06.11）

原主页github.com/rumla34作废，改地址为github.com/rumla3434，另一个主页codeberg.org/rumla34不变。

大气层1.9.1最高支持NX-20.1.1系统。如果你一直使用我发布的包，以后的更新中没有特别的提醒，都是直接覆盖就完成大气层文件的升级。

2025.06.11更新Z大佬的Ultrahand-Overlay-1.9.1及全套Tesla插件，更新DBI同文件夹下重命名DBI.nro.cn是日寸大佬汉化版DBI794，DBI.nro.ru是俄文版DBI790，更新Goldleaf.nro--v1.1.1，Tinfoil.nro--v20.1，更新CommonProblemResolver.bin--v0.3.4。

（1）大气层1.9.1+hekate6.3.1+sigpatch都最高支持20.1.0系统，目前正版系统20.1.0+虚拟系统19.0.1或20.1.0都没问题。朗姆和朋友实测只要开启飞行模式就不会待机费电异常，也不会底座温热，前提是没有超频，后台没有启动sysmodule插件，不管是20.0+还是19.0，18.0都一样。但是20.0+以后运行插件和软件会有卡顿，是破解系统可用内存变小引起的，不折腾插件和MOD对玩破解游戏并不会有太大影响。如有虚拟系统联网WIFI后待机电耗高的问题，建议系统开启飞行模式。

（2）国行的系统19.0.1或以下的必须通过tencent-switcher-gui.nro插件或者在Tesla的系统模块最下一栏把系统转区成“全球系统”后才能离线升级20.0.0+系统，否则进系统会有2162-0002（0x4a2）变砖错误，可启动Tesla菜单，在系统模块里国行按Y键改国际。需要启动Tesla菜单，可Hekate选择usb连电脑打开SD：atmosphere/，在config_templates/复制boot2.flag文件到contents/420000000007E51A/flags/就可以启动Tesla。

（3）已经升级了20.0.1的真实或虚拟系统都没必要降级19.0.1，daybreak降级后容易出现nim（0100000000000025）变砖错误，可以在进虚拟系统switch图标之前按住音量加减的官方恢复模式，进行保留数据系统初始化（快速）后才能进19.0.1。大气层整合包向下兼容Switch系统，所以降级Switch系统并不需要更换低版本的大气层，而且正版系统升级会熔断更无法使用低版本大气层，请确认SD卡上大气层三件套组件是最新版。

<img src="https://github.com/rumla3434/Atmosphere-Stable/blob/master/readme.jpg?raw=true" align="center" width="100%" >
