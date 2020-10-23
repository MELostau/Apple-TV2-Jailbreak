\f0\fs24 \cf0 Quick and easy Apple TV 2 Jailbreak by c-r-e-a-l:\
\
Requirements: Mac and Apple TV 2, plugged into power source and connected to your Mac via Micro-USB.\
\
Step 1. Open Terminal, and enter: \'93ssh YOUR-IP-APPLE-TV-2-IP-ADDRESS\'94\
Replace YOUR-IP-APPLE-TV-2-IP-ADDRESS with your Apple TV 2 IP Address, and no quotes.\
\
Step 2. Still in terminal, type one line at a time:\
\pard\pardeftab720\sl440\partightenfactor0
\cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 apt-get install wget\
wget -0- http://apt.awkwardtv.org/awkwardtv.pub | apt-key add -\
echo \'93deb http://apt.awkwardtv.org/ stable main\'94 > /etc/apt/sources.list.d/awkwardtv.list\
echo \'93deb http://mirrors.kodi.tv/apt/atv2 ./\'94 > /etc/apt/sources.list.d/xbmc.list\
apt-get update\
apt-get install org.xbmc.kodi-atv2\
reboot\
\
When your Apple TV restarts, it should have Kodi.}
