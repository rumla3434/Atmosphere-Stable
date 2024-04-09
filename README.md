# 大气层1.7.0整合包系统稳定版（更新时间：2024.03.31）

大气层1.7.0最高支持NX-18.0.0系统。

2024.04.09更新lsp199308编译的atmosphere-1.7.0-master-35d93a7c4-dirty，sigpatch已内置，替换atmosphere/package3，atmosphere/stratosphere.romfs，bootloader/payloads/fusee.bin这三个文件即可。这样大气层自动识别（原版Fusee引导）也能正常玩破解游戏不受影响，更新EOS1.1（文件路径一样，OC2.2.0）极限超频插件代替原来的OC1.9.2，支持大气层1.7.0和SW18.0.0系统。如果你一直使用我发布的包，以后的更新中没有特别的提醒，都是直接覆盖就完成大气层文件的升级。

2024.03.31更新atmosphere-1.7.0-prerelease-35d93a7c4，hekate_ctcaer_6.1.1_Nyx_1.6.1，sigpatch，lockpick。大气层1.7.0开始，fusee自动识别引导不允许加载KIP patch，会导致FS和Loader的sigpatch不能被加载，建议FSS0引导的真实破解系统，虚拟破解系统或者真实正版系统。sigpatch的问题，如果想用fusee引导又要sigpatch玩破解游戏，就下载18.0.0系统的sys-patch兼容版替代sigpatch的插件，或者用大佬重新编译的大气层package3和stratosphere.romfs的两个内置sigpatch的组件替换原版的大气层文件。极限超频插件覆盖包用于替换稳定包自带的是标准超频插件，非续航和Lite两类机型不建议使用极限超频插件，极限超频插件暂时不支持18.0.0系统，目前能用普通超频插件，主要是loader.kip加载问题。

2024.02.23更新hekate_ctcaer_6.1.0_Nyx_1.6.0，Switch/DBI/DBI.nro是658英文版（同文件夹下重命名DBI.nro.cn是汉化版DBI647，可自行更名替换，原来DBI.nro.en是DBI658，现在可以删除它）。

2024.01.30更新Z大佬的StatusMonitor.ovl。

2024.01.18更新Z大佬的StatusMonitor.ovl和ovlsysmodules，更新wiliwili.nro--v1.3.0。

2024.01.11更新Z大佬的StatusMonitorOverlay v1.0.3a2和NX-Activity-Log.nro

2024.01.05更新Z大佬的更新StatusMonitorOverlay v1.0.3a，更新DBI658，新加Hekate可加载的树莓派工具箱picofly_toolbox.bin。

2024.01.02更新Z大佬修复的StatusMonitor.ovl插件。

2023.12.31更新Z大佬的Tesla-Menu、超频插件、金手指、Hekate汉化版nyx.bin文件，但没更新Z大佬的StatusMonitor.ovl，因为有字体显示不全的bug，更新DBI.nro--v657。

<img src="https://github.com/rumla34/Atmosphere-stable/blob/master/readme.jpg?raw=true" align="center" width="100%" >
