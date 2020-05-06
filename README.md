# OpenWrt for Xiaomi Redmi AC2100 Router
[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/harryhpxs/OpenWrt-RM2100/blob/master/LICENSE)

Build OpenWrt for Xiaomi Redmi AC2100 using GitHub Actions

## 云编译方法

请参见 [P3TERX 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## 直接食用

请前往 [Releases](https://github.com/harryhpxs/OpenWrt-RM2100/releases) 下载最新固件

## 本固件包含

除 Lean's OpenWrt (LEDE) 默认配置外，还包含：
- AdGuard Home - [luci](https://github.com/rufengsuixing/luci-app-adguardhome) @ rufengsuixing
- [OpenClash](https://github.com/vernesong/OpenClash) @ vernesong
- [helloworld](https://github.com/fw876/helloworld) @ fw876
- [luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon) @ jerrykuku
- 支持IPv6

## 固件写入方法

请参见 
- [一键解锁](https://www.right.com.cn/forum/thread-4016985-1-1.html) 
- [刷入OpenWrt](https://www.right.com.cn/forum/thread-4019555-1-1.html)

## 使用情况

电信500M，纯AP模式，信道44，开启160MHz，功率23dBm，开启MU-MIMO

5GHz实测下行峰值
- Mate 20 Pro - 360 Mbps
- 荣耀30 Pro - 320 Mbps
- 小米8 - 300 Mbps

## 参考

- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt) @ P3TERX
- [OpenWRT-For-Pi](https://github.com/Wygdbb/OpenWRT-For-Pi) @ Wygdbb
- [nanopi-openwrt](https://github.com/klever1988/nanopi-openwrt) @ klever1988
- [NanoPi-R2S](https://github.com/soffchen/NanoPi-R2S) @ soffchen

## License

[MIT](https://github.com/harryhpxs/OpenWrt-RM2100/blob/master/LICENSE) © harryhpxs
