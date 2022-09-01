# Script by Nakata143

Langkah Pertama Untuk OS Debian 9 & 10
```
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot

```

Langkah Pertama Untuk OS Ubuntu 18.04 & 20.04
```
apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && sleep 2 && reboot

```

Langah Kedua
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl wget tcpdump dsniff grepcidr dnsutils -y && wget -P /root -N --no-check-certificate https://raw.githubusercontent.com/scriptadamcrew/SC/main/setup.sh && chmod +x setup.sh && "/root/setup.sh"

```


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------



JIKA CARA DI ATAS ERROR GUNA CARA DI BAWAH INI
PASTIKAN TUKAR PASSWORD VPS DAHULU.

```
sudo apt update && sudo apt upgrade -y

```

```

sudo su -

```
```

sudo sed -i 's/#PermitRootLogin prohibit-password/PermitRootLogin yes/g' /etc/ssh/sshd_config

```

```

sudo sed -i 's/PasswordAuthentication no/PasswordAuthentication yes/g' /etc/ssh/sshd_config

```

```

service sshd restart

```

```

sudo sed -i 's/#PermitRootLogin prohibit-password/PermitRootLogin yes/g' /etc/ssh/sshd_config

```

```

sudo sed -i 's/PasswordAuthentication no/PasswordAuthentication yes/g' /etc/ssh/sshd_config

```

```

service sshd restart

```

taip exit dan exit

LOGIN VPS DAN INSTALL 

Langah AKHIR 
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl wget tcpdump dsniff grepcidr dnsutils -y && wget -P /root -N --no-check-certificate https://raw.githubusercontent.com/scriptadamcrew/SC/main/setup.sh && chmod +x setup.sh && "/root/setup.sh"

```
DONE.
