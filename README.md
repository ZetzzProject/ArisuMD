 

<h1 align="center">Arisu Bot Multi Device<br></h1>
<p align="center">
<img src="https://i.ibb.co/cFfRbZ7/cheemspic.jpg" alt="cheemspic" border="0">
</p>

<p align="center">
Arisu Bot Multi Device is a automated whatsapp bot created by <a href="https://github.com/ZetzzProject" target="_blank">Zetzz</a> using <a href="https://github.com/adiwajshing/Baileys" target="_blank">Baileys</a> and <a href="https://github.com/nodejs" target="_blank">Nodejs</a>. Dont forget to give a star bro.
</p>
------

## ```Connect With Me```
<p align="center">
<a href="https://youtube.com/@zteamproject"><img src="https://img.shields.io/badge/YouTube-ff0000?style=for-the-badge&logo=youtube&logoColor=ff000000&link=https://youtube.com/@zteamproject" /><br>
<a href="https://whatsapp.com/channel/0029VaeJMTSCxoB5Xwoic81n"><img src="https://img.shields.io/badge/WhatsApp Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&link=https://whatsapp.com/channel/0029VaeJMTSCxoB5Xwoic81n" /><br>
<a href="https://chat.whatsapp.com/BW0o3ZyiAF5Azb1bIqG9Ue"><img src="https://img.shields.io/badge/WhatsApp Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
<a href="https://www.instagram.com/zetzz.zzz?igsh=MTNwNXdoM2twazhtcA=="><img src="https://img.shields.io/badge/Instagram-A020F0?style=for-the-badge&logo=instagram&logoColor=white" />
</p>

## ```Donate Me```

- [`Gopay`](https://i.ibb.co/ZdmJHgz/donate.png)

## ```Bot Support Group Chats```

- [`1st GC`](https://chat.whatsapp.com/Dc2qyVeK8JbJq8Gr3U1pKH)
- [`2nd GC`](https://chat.whatsapp.com/BW0o3ZyiAF5Azb1bIqG9Ue)
- [`3rd GC`](https://chat.whatsapp.com/KMymhLdGcjPHihOkrfHW7q)

# Setup For Deployment 👇

- FORK THE REPOSITORY [Here](https://github.com/ZetzzProject/ArisuMD/fork)

## ` BUILDPACKS`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/DGXeon/CheemsBot-MD11/)

# Install Manually 👇
## `Requirements`
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor
## `Clone Repo & Installation dependencies`
```bash
git clone https://github.com/ZetzzProject/ArisuMD.git
cd ArisuMD
npm i
npm start
```
## `For Termux/Ssh/Ubuntu`
```bash
apt update
apt upgrade
pkg update && pkg upgrade -y
pkg install bash
pkg install libwebp -y
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
pkg install nano -y
git clone https://github.com/ZetzzProject/ArisuMD
cd ArisuMD
yarn install
npm start
```
## `For VPS`
```bash
apt install nodejs 
apt install git 
apt install ffmpeg 
apt install libwebp 
apt install imagemagick
apt install bash
git clone https://github.com/ZetzzProject/ArisuMD
cd CheemsBot-MD11
npm i
npm start
```
## `One line installation`
```bash
apt update -y && apt upgrade -y && apt install git nodejs ffmpeg libwebp imagemagick python yarn && git clone https://github.com/ZetzzProject/ArisuMD && cd ArisuMD && rm -rf session && npm i && yarn install && npm start ```
## `For 24/7 Activation (Termux)`
```bash
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```
## `Note`
Change owner number on settings.js using ```nano settings.js```
