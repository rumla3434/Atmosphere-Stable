「分享」聊聊EOS极限超频插件掌机不锁GPU的注意点

极限超频插件EOS
https://www.tekqart.com/thread-364693-1-1.html
https://discord.com/invite/VndKxFg7EE
完全代替之前停止更新支持18.0.0的Switch-OC-Suite，没区别
https://github.com/hanai3Bi/Switch-OC-Suite

EOS目前最新1.3.2，EOS含sysclk-200b8_lineon和sys-clk-oc_8_0616两个极限超频插件，加载一样的loader.kip
超频插件是默认掌机不充电下锁GPU频率，但是可以解锁，由于两个极限超频插件编译不一样，所以在config/sys-clk/config.ini中的设置也不一样

sysclk-200b8_lineon在sd卡config/sys-clk/config.ini中加
[values]
unrestricted_handheld_clocks=1

sys-clk-oc_8_0616在sd卡config/sys-clk/config.ini中加
[values]
uncapped_clocks=1


小伙伴们也可以不设置config.ini，在相册的sys-clk-manager.nro管理器中进行设置相关的选项，把0改成1