# v2ray

vless://8b109ac4-79a8-4e26-b673-87cf3d89316e@us.nimcllub-net13.site:443?path=%2Fnimcllub%3Fed%3D2560&security=tls&encryption=none&host=skyroom.online&fp=randomized&type=ws&sni=skyroom.online#Best-1USUN

wget -qO - https://apt.v2raya.org/key/public-key.asc | sudo tee /etc/apt/keyrings/v2raya.asc

echo "deb [signed-by=/etc/apt/keyrings/v2raya.asc] https://apt.v2raya.org/ v2raya main" | sudo tee /etc/apt/sources.list.d/v2raya.list
sudo apt update

sudo apt install v2raya v2ray ## you can install xray package instead of if you want

sudo apt install /path/download/installer_debian_xxx_vxxx.deb ### Replace the actual path where the deb package is located by yourself

