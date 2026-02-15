# 项目简介
本固件适配斐讯 N1 旁路由模式，追求轻量（请注意：不具备 PPPoE、WiFi 相关功能）。<br>
固件包含默认皮肤、完整 IPv6 支持，以及下列 luci-app：<br>
luci-app-openclash、luci-app-samba4、luci-app-aria2、luci-app-arpbind、luci-app-diskman、luci-app-filetransfer、luci-app-fileassistant、luci-app-autoreboot、luci-app-firewall、luci-app-minidlna、luci-app-ramfree、luci-app-upnp、luci-app-vsftpd、luci-app-wol、luci-app-ttyd、luci-app-zerotier等插件<br>
也可自行集成luci-app-dockerman<br>
***
# 致谢
本项目基于 [ImmortalWrt-25.12](https://github.com/immortalwrt/immortalwrt/tree/openwrt-25.12) 源码编译，使用 flippy 的[脚本](https://github.com/unifreq/openwrt_packit)和 breakingbadboy 维护的[内核](https://github.com/breakingbadboy/OpenWrt/releases/tag/kernel_stable)打包成完整固件，感谢开发者们的无私分享。<br>
flippy 固件的更多细节参考[恩山论坛帖子](https://www.right.com.cn/forum/thread-4076037-1-1.html)。
