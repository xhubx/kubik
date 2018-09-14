#Kubik Termux

```
pkg install php 
git clone https://github.com/xhubx/kubik
cd kubik
pkg install nano
nano mod.php 
php kubik.php 
```


Yang belum punya apk kubik:
DAFTAR: http://invite.kubik.mobi/invite/A6947143
code invite: A6947143



Cara mendapatkan config (deviceCode,tk,token ... etc)
```
1. Download Packet Capture 
2. Buka , Lalu Klik TOmbol Play dipacket capturenya 
3. Buka Kubik, diamkan sekitar 10-20detik
4. Buka Packet Capture lg :stop.
5. Ambil data yg dibutuhkan.

+++++LAnjut+++++
6. Edit file Mod.php
7. Jalankan script pada termux.

code: php kubik.php

```

# Install XAMPP (WINDOWS) dan PHP7 (MANUAL UNTUK LINUX)

**Windows** : 

```
1. Download Xampp : https://downloadsapachefriends.global.ssl.fastly.net/xampp-files/7.2.1/xampp-win32-7.2.1-0-VC15-installer.exe?from_af=true (PHP7)
2. Install in drive c:/xampp
3. run : "c:/xampp/php/php.exe" kubik.php

```



**LINUX** : 

1. Install PHP7 

**Ubuntu Install PHP7 :** 
```
sudo apt-get purge 'php5*'
sudo add-apt-repository ppa:ondrej/php 
sudo apt-get update
sudo apt-get install php7.1 php7.1-common
sudo apt-get install php7.1-curl php7.1-xml php7.1-zip php7.1-gd php7.1-mysql php7.1-mbstring 

run : php kubik.php
```



**Centos Install PHP7 :** 
```
yum -y remove php*
yum install http://rpms.remirepo.net/enterprise/remi-release-7.rpm -y
yum install yum-utils -y
yum install php php-mcrypt php-cli php-gd php-curl php-mysql php-ldap php-zip php-fileinfo

run : php kubik.php
```