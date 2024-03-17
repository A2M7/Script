
<b>
[  HTTPS  ] <br>
<br>
-TROJAN GO WEBSOCKET TLS (443) <br>
<br>
[  HTTP  ] <br>
<br>
-TROJAN GO WEBSOCKET NTLS (80) <br>
<br>
♦️ For Debian 10 Only For First Time Installation (Update Repo) <br>

  ```html
 apt update -y && apt upgrade -y && apt dist-upgrade -y && apt install curl -y && apt install wget -y && apt install unzip -y && apt install perl -y && apt install socat -y && reboot
  ```
♦️ For Ubuntu 18.04 Only For First Time Installation (Update Repo) <br>
  
  ```html
 apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && apt install curl -y && apt install wget -y && apt install unzip -y && apt install perl -y && apt install socat -y && reboot
 ```
♦️ Installation Link<br>

  ```html
 sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.github.com/A2M7/Script/main/jejel/trojan && chmod +x trojan && ./trojan
 ```
♦️ Buat Akses Root <br>

  ```html
    wget -qO- -O vpsroot.sh https://raw.githubusercontent.com/A2M7/Script/main/vpsroot.sh && bash vpsroot.sh
  ```
♦️ Multi Path Core Untuk OPOK <br>
  ```html
    wget -q -O /root/updateCore.sh "https://raw.githubusercontent.com/syfqsamvpn/scriptvps/main/dll/system/updateCore.sh" && chmod +x /root/updateCore.sh && ./updateCore.sh
  ```
♦️ Docker Dorowu <br>
  ```html
 docker run -p 6070:80 dorowu/ubuntu-desktop-lxde-vnc
 ```
