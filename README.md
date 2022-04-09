<h1 align="center">ꪶ𝗖𝗵𝗲𝗲𝗺𝘀 𝗕𝗼𝘁-𝗠𝗗ꫂ<br></h1>
<p align="center">
  <img src="https://telegra.ph/file/83dda0f2e9772c01076b1.jpg" width="100" height="100" />
</p>



------


<p align="left">
Scan qr code from the above button, u can pay through GooglePay, Paytm, PhonePe and FamPay.
</p>


# Setup For Deployment 👇

## `SETTINGS`

- CHANGE OWNER NUMBER [Here](https://github.com/Alinshan/Jarvis/blob/master/config/config.json#L25)
- CHANGE OWNER NAME [Here](https://github.com/Alinshan/Jarvis/blob/master/config/config.json#L30)
- CHANGE BOT NAME [Here](https://github.com/Alinshan/Jarvis/blob/master/config/config.json#L29)

## ` BUILDPACKS`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
https://github.com/DuckyTeam/heroku-buildpack-imagemagick
heroku/nodejs
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Alinshan/Jarvis/)

# Install Manually 👇
## `Requirements`
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor
## `Clone Repo & Installation dependencies`
```bash
git clone https://github.com/DGXeon/CheemsBot-MD.git
cd CheemsBot-MD
npm start
```
## `For Termux/Ssh/Ubuntu`
```bash
apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
git clone https://github.com/Alinshan/Jarvis
cd Jarvis
npm start
```
## `For VPS`
```bash
apt install nodejs 
apt install git 
apt apt install ffmpeg 
apt apt install libwebp 
apt apt install imagemagick
apt install bash
git clone https://github.com/Alinshan/Jarvis
cd Jarvis
npm start
```
## `For 24/7 Activation`
```bash
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```
