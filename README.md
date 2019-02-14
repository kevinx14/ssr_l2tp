# ssr_l2tp
https://github.com/ToyoDAdoubi/doubi
ssr.sh

    脚本说明: ShadowsocksR 一键安装管理脚本，支持单端口/多端口切换和管理
    系统支持: CentOS6+ / Debian6+ / Ubuntu14+
    使用方法: https://doub.io/ss-jc42/
    项目地址: https://github.com/ToyoDAdoubiBackup/shadowsocksr

脚本特点:

目前网上的各个ShadowsocksR脚本基本都是只有 安装/启动/重启 等基础功能，对于小白来说还是不够简单方便。既然是一键脚本，那么就要尽可能地简单，小白更容易接受使用！

    支持 限制 用户速度
    支持 限制 端口设备数
    支持 显示 当前连接IP
    支持 显示 SS/SSR连接+二维码
    支持 切换管理 单/多端口
    支持 一键安装 锐速
    支持 一键安装 BBR
    支持 一键封禁 垃圾邮件(SMAP)/BT/PT

下载安装:
```
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
```


https://github.com/hwdsl2/setup-ipsec-vpn
IPsec VPN 服务器一键安装脚本
```
wget https://git.io/vpnsetup -O vpnsetup.sh && sudo \
VPN_IPSEC_PSK='你的IPsec预共享密钥' \
VPN_USER='你的VPN用户名' \
VPN_PASSWORD='你的VPN密码' sh vpnsetup.sh
```
