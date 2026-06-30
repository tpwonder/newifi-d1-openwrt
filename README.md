# Newifi D1 OpenWrt 固件

基于 [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede) 自动编译

## 设备信息
- **型号**: Lenovo Newifi D1
- **芯片**: MediaTek MT7621AT (ramips)
- **内存**: 512MB
- **Target**: ramips/mt7621

## 使用方法
1. Fork 本仓库
2. 进入仓库 -> Actions -> Build Newifi D1 OpenWrt -> Run workflow
3. 等待编译完成
4. 在 Artifacts 中下载固件

## 包含插件
| 插件 | 说明 |
|------|------|
| luci-theme-argon | Argon 美化主题 |
| nlbwmon + luci-app | 网络数据流量监控 |
| ttyd | Web 终端 |
| zerotier | ZeroTier 组网 |
| reguard | re:Guard 网络守护 |
| upnp | UPnP 端口映射 |
| ipv6 | IPv6 完整支持 |
| cloudflared | Cloudflare Tunnel |
| vlmcsd | KMS 激活服务 |
| nano | 文本编辑器 |
| iperf3 | 网络测速 |
| **USB 挂载 (D1 特有)** | **ext4/vfat/exfat/ntfs/ntfs3/xfs/btrfs/hfs+ 全格式** |
| **自动挂载** | **block-mount + luci-app-diskman** |
| **Samba4** | **局域网文件共享** |
| **MiniDLNA** | **U盘媒体服务器** |
| **打印机** | **p910nd 网络打印** |
