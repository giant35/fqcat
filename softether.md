#softether

-----
[docker 方式](https://hub.docker.com/r/frosquin/softether/)  
  bandwagon不支持docker 
  digitalOcean 运行后，用softether管理工具连 造成网络无法连接
----
##centos7 install softether  

```
yum groupinstall -y 开发工具
cd /usr/local
curl -O 'http://www.softether-download.com/files/softether/v4.18-9570-rtm-2015.07.26-tree/Linux/SoftEther_VPN_Server/64bit_-_Intel_x64_or_AMD64/softether-vpnserver-v4.18-9570-rtm-2015.07.26-linux-x64-64bit.tar.gz'
tar xvzf softether-vpnserver-v4.18-9570-rtm-2015.07.26-linux-x64-64bit.tar.gz 
cd /usr/local/vpnserver
make
./vpnserver start
echo '服务端安装好 请通过softether 管理工具配置'
```


##参考:  
http://mawenjian.net/p/1281.html
  
  
