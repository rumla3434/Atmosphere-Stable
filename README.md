大气层1.7.1整合包系统稳定版（更新时间：2024.10.03）
=====

原主页github.com/rumla34作废，改地址为github.com/rumla3434，另一个主页codeberg.org/rumla34不变。

大气层1.7.1最高支持NX-18.1.0系统。如果你一直使用我发布的包，以后的更新中没有特别的提醒，都是直接覆盖就完成大气层文件的升级。

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
