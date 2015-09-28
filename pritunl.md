#pritunl install in centos7  
参考[https://github.com/pritunl/pritunl] (https://github.com/pritunl/pritunl)

```
sudo yum -y install epel-release
$ nano /etc/yum.repos.d/pritunl.repo
[pritunl]
name=Pritunl Repository
baseurl=http://repo.pritunl.com/stable/yum/centos/7/
gpgcheck=1
enabled=1

$ gpg --keyserver hkp://keyserver.ubuntu.com --recv-keys CF8E292A
$ gpg --armor --export CF8E292A > key.tmp; rpm --import key.tmp; rm -f key.tmp
$ yum install pritunl mongodb-server
$ systemctl start mongod pritunl
$ systemctl enable mongod pritunl```
