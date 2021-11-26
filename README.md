# 云编译 OpenWrt 固件


** 固件说明**：
  - [x] 架构适配x86_64
  - [x] 后台地址：192.168.1.1 管理员：root  初始密码：空
  - [x] 添加jerrykuku第三方argon主题 并设置为默认
  - [x] 添加科学上网插件 passwall
  - [x] 添加DNS加强插件  smartdns
  
**集成插件**：（**打勾项**默认**编译**入固件；**未打勾项**默认**不编译**入固件。）
  - [x] luci-app-accesscontrol  #访问时间控制
  - [x] luci-app-adbyby-plus  #广告屏蔽大师Plus +
  - [x] luci-app-arpbind  #IP/MAC绑定
  - [x] luci-app-autoreboot  #支持计划重启
  - [x] luci-app-ddns   #动态域名 DNS（集成阿里DDNS客户端）
  - [x] luci-app-diskman   #磁盘管理工具
  - [x] luci-app-filetransfer  #文件传输（可web安装ipk包）
  - [x] luci-app-firewall   #添加防火墙
  - [x] luci-app-frpc   #内网穿透Frp客户端
  - [x] luci-app-frps   #内网穿透Frp服务端
  - [x] luci-app-hd-idle  #硬盘休眠
  - [x] luci-app-ipsec-vpnd  #VPN服务器 IPSec
  - [x] luci-app-mwan3   #MWAN3负载均衡
  - [x] luci-app-mwan3helper   #MWAN3分流助手
  - [x] luci-app-netdata  #Netdata实时监控（图形化）
  - [x] luci-app-nlbwmon   #网络带宽监视器
  - [x] luci-app-passwall  #科学上网（Li大内插件）
  - [x] luci-app-ramfree  #释放内存
  - [x] luci-app-samba   #网络共享（Samba）
  - [x] luci-app-smartdns  #SmartDNS本地服务器
  - [x] luci-app-softethervpn  #SoftEther VPN服务器  NAT穿透
  - [x] luci-app-syncdial  #多拨虚拟网卡（原macvlan）
  - [x] luci-app-ttyd   #网页终端命令行
  - [x] luci-app-turboacc   #Turbo ACC 网络加速(支持 Fast Path 或者 硬件 NAT) 
  - [x] luci-app-unblockmusic  #解锁网易云灰色歌曲
  - [x] luci-app-upnp   #通用即插即用UPnP（端口自动转发）
  - [x] luci-app-usb-printer  #USB 打印服务器
  - [x] luci-app-vlmcsd  #KMS服务器设置
  - [x] luci-app-vsftpd  #FTP服务器
  - [x] luci-app-wol   #WOL网络唤醒
  - [x] luci-app-zerotier  #ZeroTier内网穿透



![OpenWRT.png]()

## 感谢 ❤️
- 源码来源： Lean 的 Openwrt 源码仓库 https://github.com/coolsnowwolf/lede
- 脚本来源： P3TERX 的 使用 GitHub Actions 云编译 OpenWrt https://github.com/P3TERX/Actions-OpenWrt
