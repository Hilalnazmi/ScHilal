## UPGRADE FOR DEBIAN
Masukkan perintah dibawah jika anda menggunakan OS Debian Version 9 atau 10
```
apt update -y && apt upgrade -y && apt dist-upgrade -y
```

##  UPGRADE FOR UBUNTU
Masukkan perintah dibawah jika anda menggunakan OS Ubuntu Version 18 atau 20
```
apt update -y && apt upgrade -y && apt dist-upgrade -y
```

## INSTALL SCRIPT 
Masukkan perintah dibawah untuk menginstall Autoscript Premium
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/Hilalnazmi/ScHilal/main/setup.sh && chmod +x setup.sh && ./setup.sh
```

## UPDATE SCRIPT
Masukkan perintah dibawah jika terdapat informasi pembaruan Script untuk versi yang akan datang
```
[[ -e $(which curl) ]] && if [[ -z $(cat /etc/resolv.conf | grep "8.8.8.8") ]]; then cat <(echo "nameserver 8.8.8.8") /etc/resolv.conf > /etc/resolv.conf.tmp && mv /etc/resolv.conf.tmp /etc/resolv.conf; fi
