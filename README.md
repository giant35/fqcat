# fqcat 翻墙猫  

## 翻墙的几种方式

1. web proxy  (全平台)  
  最简单的方式，不过经常被封，而且效果不稳定
  如：http://move.run
1. VPN  (全平台)  
    业界标准电脑手机都支持，需要找合适的供应商，我用了greenvpn 不好用老连不上
1. Shadowsocks  （推荐）
    还不错，需要自己的服务器，或者找账号。 iPhone 需要安装app
1. SSH tunnel （电脑）
    linux/osx 比较 方便 ，手机上不方便用啊  
    在本地创建socks5 proxy 
    `SSH -qTfnN -D port remotehost`
1. Goagent 之类  
  安装比较复杂，一般技术人员才行吧，而且手机上好像是没法用
1. TOR  
  我这用不了
1. stunnel+squid  
  服务器配置比较麻烦，可以使用标准的 http proxy ,电脑手机都支持
1. socks / http proxy  
  好像是不行的，被墙了
1. Lantern   
  最新版又可以用了，有段时间我这是用不了，使用倒是简单
1. Psiphon (win+android)
  没试过


## 主机试用  
1. [Aliyun.com](aliyun.md) (支持支付宝)
2. [DigitalOcean.com](digitalocean.md)  （不支持支付宝）
3. [bandwagonhost.com](bandwagon.md) (支持支付宝)

## [pritunl配置](pritunl.md)


## [相关链接](link.md)
