----------
<div align="center">
  
## ![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Rockstar-ExtraBold&color=F33A6A&lines=WELCOME+TO+JARVIS+WA+BOT+REPO)

</div>
  
<div align="center">[![ERR0R-x-PREDAT0R](https://github.com/Alinshan.png?size=200)](https://github.com/Alinshan) |
----|
  </div>
  <div align="center">
<a href="#"><img title="JARVIS" src="https://img.shields.io/badge/-Jarvis%20-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
  <p align="center">
<a href="https://github.com/Alinshan"><img title="Author" src="https://img.shields.io/badge/AUTHOR-ALINSHAN-grey%2Fblue?color=blue&style=for-the-badge&logo=whatsapp">
</p>
  <p align="center"> 
  <a href="https://wa.me/918592068706"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
</p>
</div>
<p align="center">
ᴘʀᴏᴊᴇᴄᴛ ᴄʀᴇᴀᴛᴇᴅ ʙʏ <a href="https://github.com/Alinshan">ᴀʟɪɴsʜᴀɴ</a>
    <br>
       | © |
        Reserved |
    <br> 
</p>


----------


----------

# Setup For Deployment 👇


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
