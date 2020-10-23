Quick and easy Apple TV 2 Jailbreak by c-r-e-a-l:

Requirements: Mac and Apple TV 2, plugged into power source and connected to your Mac via Micro-USB.

Step 1. Open Terminal, and enter: “ssh YOUR-IP-APPLE-TV-2-IP-ADDRESS”
Replace YOUR-IP-APPLE-TV-2-IP-ADDRESS with your Apple TV 2 IP Address, and no quotes.

Step 2. Still in terminal, type one line at a time:
apt-get install wget
wget -0- http://apt.awkwardtv.org/awkwardtv.pub | apt-key add -
echo “deb http://apt.awkwardtv.org/ stable main” > /etc/apt/sources.list.d/awkwardtv.list
echo “deb http://mirrors.kodi.tv/apt/atv2 ./” > /etc/apt/sources.list.d/xbmc.list
apt-get update
apt-get install org.xbmc.kodi-atv2
reboot

When your Apple TV restarts, it should have Kodi.
