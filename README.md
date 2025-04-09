大气层1.8.0整合包系统稳定版（更新时间：2025.04.08）
=====

原主页github.com/rumla34作废，改地址为github.com/rumla3434，另一个主页codeberg.org/rumla34不变。

大气层1.8.0最高支持NX-19.0.1系统。如果你一直使用我发布的包，以后的更新中没有特别的提醒，都是直接覆盖就完成大气层文件的升级。

2025.04.08更新Checkpoint.nro--v3.8.2（无需重新制作前端NSP），NX-Activity-Log.nro--v1.5.5（和checkpoint一样必须以前端模式进），更新DBI同文件夹下DBI.nro.ru是俄文版DBI779。

2025.02.28更新wiliwili.nro--v1.5.1，更新DBI同文件夹下DBI.nro.ru是俄文版DBI763，一键清理contents的旧插件和删主题20250228更新。

2025.02.12更新z大佬发布的Tesla基本组件，Edizon和StatusMonitor，更新DBI同文件夹下DBI.nro.ru是俄文版DBI756。

2025.01.16更新sys-clk-EOS.ovl-1.5.1，新增DBI同文件夹下重命名DBI.nro.ru是俄文版DBI750，想替换英文版DBI658或共存都可以参考「分享」新人必看的Switch破解游戏安装教程。

2024.12.09更新Z大的ovlsysmodules，EdiZon，StatusMonitor，更新NX-Activity-Log.nro--v1.5.4，Tinfoil.nro--v19.1（自带前端，支持19.0.0+）。

2024.11.11更新Z大的ovlloader，ultrahand，ovlsysmodules，EdiZon，StatusMonitor，NX-Activity-Log.nro，更新linkalho.nro。

2024.11.08更新JKSV.nro--11.05.2024。

2024.10.29更新Z大的ovlmenu-ultrahand。Switch新系统19.0.1，大气层1.8.0继续支持，无需更新。

2024.10.25更新Z大的ovlloader，ovlmenu-ultrahand，ovlsysmodules，edizon和StatusMonitor.ovl，更新wiliwili.nro--v1.5.0支持19.0.0自动安装前端不会报错。

2024.10.21更新sigpatch在原来ES、FS、Loader和NFIM基础上新增nim patch，这个nim patch适合使用代理服务器在虚拟系统使用隐藏序列号玩黑商店，youtube等防BAN。更新ovlmenu-1.7.9，StatusMonitor.ovl-v1.1.4+。

2024.10.19更新ovlloader-Tesla启动器-1.0.9+，更新sys-clk-EOS.ovl-1.5.0支持大气层1.8.0或以上，只要不覆盖启动设置，这个极限超频只能当普通超频插件使用。更新EdiZon.ovl-1.0.9。虽目前大气层1.8.0还是prerelease，但经过一段时间的测试，和正式版没区别，而且运行nro转nsp前端的工具并不是sigpatch的问题，而是需要新版本的转换工具制作：Menu0.12beta-nro2nsp-FW19。

2024.10.16更新atmosphere-1.8.0-prerelease-c6014b533，更新此版大气层的loader patch（ips和patches.ini），fusee.bin取自gbatemp论坛编译版，支持fusee引导的fs/loader的ips补丁。

虽当前大气层1.8.0是prerelease版本，但有新的万能前端hbmenu解决nsp前端软件问题，tinfoil.nro和wiliwili.nro都能正常使用了。所以如果你的正版系统已通过联网误升级到19.0.0且熔断数20。或想升级虚拟系统到19.0.0下去玩最新的破解游戏，都可以把SD卡的大气层文件升级到此版本。由于极限超频插件EOS未更新支持大气层1.8.0pre，如果SD卡上已经有覆盖过朗姆之前发的极限超频插件EOS，建议删除atmosphere/kips/loader.kip后再覆盖大气层1.8.0pre整合包完成升级。

2024.10.15，更新支持19.0.0万能前端hbmenu.nsp，先删旧的桌面图标再安装新的，更新applet版的tinfoil.nro，进入方式和wiliwili.nro一样。由于极限超频插件EOS未更新支持大气层1.8.0pre，如果SD卡上已经有覆盖过朗姆之前发的极限超频插件EOS，建议删除atmosphere/kips/loader.kip后再覆盖大气层1.8.0pre整合包完成升级。

2024.10.13上午，更新内置sigpatch的fusee.bin，更新fss0的patches.ini，恢复显示大气层原版fusee引导，fss0和fusee引导的sigpatch都最高支持19.0.0系统，真实或虚拟破解系统都可以升级19.0.0后玩NSP/XCI等破解游戏，但是暂时不支持前端NSP软件，比如wiliwili解决方法可通过按住R键打开游戏进hbmenu再打开wiliwili.nro，更新StatusMonitor.ovl-v1.1.4。

2024.10.13凌晨，更新atmosphere-1.8.0-prerelease-5717ea6c0，hekate_ctcaer_6.2.2_Nyx_1.6.4，由于sigpatch最高只能支持SW18.1.0，所以不能在19.0.0系统里玩破解游戏，只能玩正版游戏，要daybreak降级到18.1.0才可以玩破解游戏，暂时屏蔽大气层原版fusee引导（更多-大气层自动识别，大气层1.7.0以后不支持fusee引导玩破解游戏），更新Lockpick_RCM.bin--v1.9.13。

2024.10.03更新替换Tesla（ovlloader+ovlmenu已同名替换成ultrahand，此次也一样可以覆盖升级，和Tesla一样启动键L+Ddown），更新StatusMonitor.ovl-v1.1.3英文，switchtime.nro--v0.1.5，更新极限超频EOS1.4.4。
由于替换ultrahand和StatusMonitor.ovl-v1.1.3英文，所以SD卡原config/Tesla-Menu，switch/.overlays/lang/Tesla-Menu，switch/.overlays/lang/StatusMonitor这三个文件夹可删除，不删也没关系。

2024.08.07更新JKSV.nro--08.06.2024。

2024.07.24更新JKSV.nro--07.18.2024，TegraExplorer.bin--v4.2.0。

2024.07.06更新Z大发布的StatusMonitor.ovl-2024.7.4，更新wiliwili.nro--v1.4.1（相册重进一次wiliwili.nro安装前端搞定升级）。

2024.07.03更新hekate6.2.1汉化版，更新极限超频EOS1.3.2（已解除掌机不充电的GPU限制）。

2024.06.19更新Z大的“StatusMonitor.ovl”插件，更新极限超频EOS1.3.1。

2024.06.17更新lsp199308编译的atmosphere-1.7.1-master-e85bc4db0-dirty，sigpatch已内置，替换atmosphere/package3，atmosphere/stratosphere.romfs，bootloader/payloads/fusee.bin这三个文件即可。重新显示“更多设置”中的“大气层自动识别（fusee引导）”。

2024.06.14更新Hekate6.2.0-v4汉化版。暂时屏蔽更多设置中的“大气层-自动识别（fusee引导）”，等大佬编译内置sigpatch的大气层1.7.1后再显示该引导项。

2024.06.11更新原版Atmosphere1.7.1，Hekate6.2.0-v3汉化版，Sigpatch，Z大的Tesla插件edizon和StatusMonitor.ovl，更新极限超频插件EOS1.3.0适配18.1.0系统。

2024.06.09更新EdiZon.ovl和nro-2024.6.9，更新极限超频EOS1.2.7，但loader.kip依旧锁RAM最大1996。

2024.06.04更新Tinfoil.nro--v18.1。

2024.05.10更新Z大发布的ovlmenu.ovl和ovl-sysmodules.ovl。

2024.05.01更新wiliwili.nro--v1.4.0。

2024.04.25更新18.0.1的nfim_ctest补丁，新增N-Xplorer--v0.7.1文本编辑文件管理器，替换Zdm大佬的完整汉化Hekate的nyx.bin。

2024.04.15更新ZDM大佬的Tesla插件，sys-clk超频插件，edizon金手指等。

2024.04.09更新lsp199308编译的atmosphere-1.7.0-master-35d93a7c4-dirty，sigpatch已内置，替换atmosphere/package3，atmosphere/stratosphere.romfs，bootloader/payloads/fusee.bin这三个文件即可。这样大气层自动识别（原版Fusee引导）也能正常玩破解游戏不受影响，更新EOS1.1（文件路径一样，OC2.2.0）极限超频插件代替原来的OC1.9.2，支持大气层1.7.0和SW18.0.0系统。

2024.03.31更新atmosphere-1.7.0-prerelease-35d93a7c4，hekate_ctcaer_6.1.1_Nyx_1.6.1，sigpatch，lockpick。大气层1.7.0开始，fusee自动识别引导不允许加载KIP patch，会导致FS和Loader的sigpatch不能被加载，建议FSS0引导的真实破解系统，虚拟破解系统或者真实正版系统。sigpatch的问题，如果想用fusee引导又要sigpatch玩破解游戏，就下载18.0.0系统的sys-patch兼容版替代sigpatch的插件，或者用大佬重新编译的大气层package3和stratosphere.romfs的两个内置sigpatch的组件替换原版的大气层文件。极限超频插件覆盖包用于替换稳定包自带的是标准超频插件，非续航和Lite两类机型不建议使用极限超频插件，极限超频插件暂时不支持18.0.0系统，目前能用普通超频插件，主要是loader.kip加载问题。

2024.02.23更新hekate_ctcaer_6.1.0_Nyx_1.6.0，Switch/DBI/DBI.nro是658英文版（同文件夹下重命名DBI.nro.cn是汉化版DBI647，可自行更名替换，原来DBI.nro.en是DBI658，现在可以删除它）。

2024.01.30更新Z大佬的StatusMonitor.ovl。

2024.01.18更新Z大佬的StatusMonitor.ovl和ovlsysmodules，更新wiliwili.nro--v1.3.0。

2024.01.11更新Z大佬的StatusMonitorOverlay v1.0.3a2和NX-Activity-Log.nro

2024.01.05更新Z大佬的更新StatusMonitorOverlay v1.0.3a，更新DBI658，新加Hekate可加载的树莓派工具箱picofly_toolbox.bin。

2024.01.02更新Z大佬修复的StatusMonitor.ovl插件。

2023.12.31更新Z大佬的Tesla-Menu、超频插件、金手指、Hekate汉化版nyx.bin文件，但没更新Z大佬的StatusMonitor.ovl，因为有字体显示不全的bug，更新DBI.nro--v657。

<img src="https://github.com/rumla3434/Atmosphere-Stable/blob/master/readme.jpg?raw=true" align="center" width="100%" >
