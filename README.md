# fqcat 翻墙猫  
##翻墙的几种方式

1. web proxy  
  最简单的方式，不过经常被封
  如：http://move.run
2. VPN  
    业界标准电脑手机都支持，需要找合适的供应商，我用了greenvpn 不好用老连不上
3. Shadowsocks  
    还不错，需要自己的服务器，或者找账号。 iPhone 需要安装app,而且要从国外商店才能下载app （不知道为啥我在iPhone上也上不了网）
4. SSH tunnel
    linux/osx 比较 方便 ，手机上不方便用啊  
    在本地创建socks5 proxy 
    `SSH -qTfnN -D port remotehost`
5. stunnel+squid  
  服务器配置比较麻烦，可以使用标准的 http proxy ,电脑手机都支持
6. socks / http proxy  
  好像是不行的，被墙了

##[pritunl配置](pritunl.md)


##[相关链接](link.md)
