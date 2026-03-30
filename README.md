# 大气层1.11.0整合包系统稳定版（更新时间：2026.03.26）

大气层1.11.0最高支持NX-22.0.0系统，如果你一直使用我发布的包，以后的更新中没有特别的提醒，都是直接覆盖就完成大气层文件的升级。

2026.03.26更新非官方atmosphere-1.11.0，更新hekate6.5.2最新和汉化nyx.bin，更新sigpatch的fs，loader（由borntohonk大佬提供的py脚本自制，但是22.0.0的exefs_patches会影响系统黑屏），所以虚拟系统只有降级21.2.0后才能完整的玩破解游戏不会报错。真实系统22.0.0玩正版游戏没问题，tesla也没问题，由于22.0.0破解下目前相册nro软件直接打开会报错，所以新增sphaira.nro重命名后替换根目录hbmenu.nro，便于生成daybreak的前端对虚拟系统进行降级。真实系统安装前端应用会被BAN机！

（1）大气层1.11.0+hekate6.5.2都最高支持22.0.0系统，sigpatch最高支持21.2.0，建议虚拟系统降级21.2.0，进虚拟系统22.0.0后点击相册是sphaira主页，移动到daybreak.nro后按X键呼出菜单，选择安装前端应用后返回桌面，进桌面的daybreak图标进行虚拟系统降级。如果不想生成前端，可直接重命名daybreak.nro为hbmenu.nro后替换SD卡根目录，进相册等于打开daybreak.nro。

（2）建议飞行模式启动游戏，如果之前使用了linkalho假关联过任天堂账号，升级到21.0.0建议重新使用带mod版linkalho.nro重新假关联一次或者解除假关联，这样虚拟系统wifi下玩破解游戏会消除启动游戏弹窗的bug。

（3）国行的系统19.0.1或以下的必须通过tencent-switcher-gui.nro插件或者在Tesla的系统模块最下一栏把系统转区成“全球系统”后才能离线升级20.0.0+系统，否则进系统会有2162-0002（0x4a2）变砖错误，可启动Tesla菜单，在系统模块里国行按Y键改国际。需要启动Tesla菜单，可Hekate选择usb连电脑打开SD：atmosphere/，在config_templates/复制boot2.flag文件到contents/420000000007E51A/flags/就可以启动Tesla。

（4）daybreak平刷系统是没问题的，但是如果20.0+以后再降级刷系统后会出现2162-0002的nim（0100000000000025）变砖错误，可以在进系统switch图标之前按住音量加减的官方恢复模式，进行保留数据系统初始化（快速）后才能进，所以要提前备份游戏存档数据，而且初始化以后游戏要重新安装。大气层整合包向下兼容Switch系统，所以降级Switch系统并不需要更换低版本的大气层，而且正版系统升级会熔断更无法使用低版本大气层，请确认SD卡上大气层三件套组件是最新版。

# 大气层版本怎么选？

看主机熔断数，Switch升级正版系统没有回头路，主机熔断不可逆，大气层版本是对应SW系统支持破解，目前大气层1.11.0最高支持NX-22.0.0系统。

举例：当前主机正版系统21.0，虚拟系统21.0或19.0或更低，熔断=22，使用大气层1.10.2整合包。

如果升级正版系统到22.0，触发熔断23，只能换成大气层1.11.0的整合包，即使你降级正版系统到21.2，以后也只能用大气层1.11.0或更高版本大气层整合包。

如果升级虚拟系统到22.0，不会熔断，你可以先换成大气层1.11.0，顺利进虚拟系统，然后daybreak降级到21.2后再换大气层1.10.2整合包。

# 原主页github.com/rumla34作废，改地址为github.com/rumla3434，另一个主页codeberg.org/rumla34不变。

https://github.com/rumla3434/Atmosphere-stable/releases

https://codeberg.org/rumla34/Atmosphere-stable/releases

<img src="https://github.com/rumla3434/Atmosphere-Stable/blob/master/readme.jpg?raw=true" align="center" width="100%" >
