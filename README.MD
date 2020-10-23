{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf610
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;\red52\green52\blue52;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c26667\c26667\c26667;\cssrgb\c100000\c100000\c100000;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

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