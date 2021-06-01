把 dvb.mk複製到lede/package/kernel/liunx/modules
dvb-firmware openwrt-packages OpenWrt-Packages-DVB 三個文件夾複製到lede/package
rm -rf ./feeds/packages/multimedia/tvheadend 

make kernel_menuconfig 選擇 device drivers 再選擇muitimedia support
選擇diaital tv support和 dvb network support
media pci adapters 進去全部選擇，推出
dvb platform device 
選擇customize tv tuners 進去全選。退出
選擇customise dvb frontends 進去全選退出 直到完全退出。

make menuconfig 进入菜单 选择DVB-EXTRAS 进去选择tvheadend oscam  libdvbcsa。
make V=s -j1
