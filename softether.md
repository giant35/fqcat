#softether

-----
docker 方式  
https://medium.com/@gargar454/easiest-way-to-setup-your-own-vpn-with-a-single-docker-command-and-run-it-for-free-in-the-cloud-e792f581526c  
[docker 方式](https://hub.docker.com/r/frosquin/softether/) 
bandwagon不支持docker  

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


##ios 
使用 L2TP

## digitalOcean 运行正常？

##google cloud  
  没安装成功，连上也没有反应  
  通过docker 方式启动时 报 `iptables v1.4.21: can't initialize iptables table `filter': Permission denied (you must be root)`


##参考:  
http://mawenjian.net/p/1281.html  
http://www.freebuf.com/tools/40418.html  

  
  
