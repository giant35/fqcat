#strongswan

##安装
1. centos6 / ubuntu  
参考 http://quericy.me/blog/699   https://github.com/quericy/one-key-ikev2-vpn 
在bandwagon安装成功

安装成功后默认账号 
```
#############################################################
#
# [Install Successful]
# There is the default login info of your VPN
# UserName: myUserName
# PassWord: myUserPass
# PSK: myPSKkey
# you can change UserName and PassWord in /usr/local/etc/ipsec.secrets
# you must copy the cert  /home/sihai/my_key/ca.cert.pem  to the client and install it.
#
#############################################################
```

1. google cloud computer ok   
(g-micro) zone:asia-east1-c  (网速不错) 是 KVM 选 centos6，有时连不上的话重启下 strongswan `/usr/local/sbin/ipsec restart`


```
589 packets transmitted, 575 packets received, 2.4% packet loss
round-trip min/avg/max/stddev = 80.674/190.163/689.938/82.176 ms
```
需要使用 sudo 运行
ipsec 在/usr/local/sbin
sudo /usr/local/sbin/ipsec start



##ios
不需要导入证书，使用 IPSEC 
