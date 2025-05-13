# 大气层1.9.0整合包系统稳定版（更新时间：2025.05.13）

原主页github.com/rumla34作废，改地址为github.com/rumla3434，另一个主页codeberg.org/rumla34不变。

2025.05.13更新Z大佬的Tesla全套中文插件ovlloader，ovlmenu，ovlsysmodules，EdiZon，StatusMonitor，sys-clk。更新hekate的汉化nyx.bin文件，更新Goldleaf.nro--v1.1.0，新加AK佬的破解教程合集。

2025.05.10-2更新sys-clk-EOS.ovl-1.6.0测试发现loader.kip和lsp的内置sigpatch冲突，不能玩破解游戏，所以暂时移除。

2025.05.10更新hekate_ctcaer_6.3.0_Nyx_1.7.0汉化版，Lockpick_RCM.bin--v1.9.15。

2025.05.08更新lsp199308编译的atmosphere-1.9.0-20_support-9dd8269f7-dirty，sigpatch已内置（ES，FS，LOADER，NIM，NIFM内置），替换atmosphere/package3，atmosphere/stratosphere.romfs，bootloader/payloads/fusee.bin这三个文件即可，恢复大气层自动识别fusee.bin引导选项，因为sigpatch内置且最高支持20.0.1，所以虚拟升级20.0.1也能玩破解游戏，也不需要sys-patch插件。更新DBI同文件夹下DBI.nro.ru是俄文版DBI785。

2025.05.07更新官方atmosphere1.9.0测试版，官方hekate6.2.5测试版，sigpatch最高只能支持19.0.1玩破解游戏，想升级20.0.1玩破解游戏的可自行增加最新的sys-patch插件。

2025.05.05更新Z大的ultrahand，更新Hekate的emummc.kipm可引导虚拟20.0.1系统，但无sigpatch不能玩破解游戏，所以不建议升级。

2025.05.03更新测试版的atmosphere-1.9.0，hekate6.2.2，最高支持真实系统20.0.1，最高支持虚拟系统19.0.1。更新Checkpoint.nro--v3.10.0（无需重新制作前端NSP），NX-Activity-Log.nro--v1.5.7（和checkpoint一样必须以前端模式进），更新DBI同文件夹下DBI.nro.ru是俄文版DBI781，更新Lockpick_RCM.bin--v1.9.14。

（1）lsp编译的大气层1.9.0稳定版本没任何问题。Hekate正式发布6.3.0，其实各模块和之前发布的测试版都一样。所以双系统玩家，如果误升级真实系统到20.0.1的，建议更新此包，不会影响虚拟系统19.0.1或以下。只玩真实系统的玩家，比如BAN机的，如果误升级真实系统到20.0.1的，也可以用此包玩破解游戏。20.0.0或以上系统可能wifi联网下待机比较费电，可以选择插电、关机或者开飞行模式解决。

（2）只玩虚拟系统的玩家，只要不更新真实系统到20.0.0或以上，就不需要更新大气层，安心呆在虚拟19.0.1玩游戏。

（3）国行的系统19.0.1或以下的必须通过tencent-switcher-gui.nro插件或者在Tesla的系统模块最下一栏把系统转区成“全球系统”后才能离线升级20.0.0+系统，否则进系统会有2162-0002（0x4a2）变砖错误，尤其是真实系统变砖只能还原NAND备份。

（4）已经升级了20.0.1的真实或虚拟系统都没必要降级19.0.1，daybreak降级后容易出现nim（0100000000000025）变砖错误，可以在进虚拟系统switch图标之前按住音量加减的官方恢复模式，进行保留数据系统初始化（快速）后才能进19.0.1。

（5）极限超频loader.kip和ips的sigpatch有冲突，两者不可兼得，经实测，fss0引导能解决破解游戏的运行，但无法解决自制软件NSP的运行问题，所以想用极限超频插件的loader.kip的可删除ips的sigpatch，改用sys-patch插件。

<img src="https://github.com/rumla3434/Atmosphere-Stable/blob/master/readme.jpg?raw=true" align="center" width="100%" >
