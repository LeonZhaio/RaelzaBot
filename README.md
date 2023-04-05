<div align="center">
<img src="https://telegra.ph/file/07b50c0eca5870ab032c8.jpg" alt="RaelzaBot" width="500" />
  
# RaelzaBot
RaelzaBot adalah bot WhatsApp #multi-device menggunakan library ferdiz-afk/baileys.
<p align="center">
<a href="https://github.com/adamdani169"><img title="Author" src="https://img.shields.io/badge/Author-adamdani169-red.svg?style=for-the-badge&logo=github"></a>
  <img src="https://img.shields.io/github/repo-size/adamdani169/RaelzaBot"/>
</p>

Base [Nao-MD](https://github.com/ShirokamiRyzen/Nao-MD).

[![Group WhatsApp](https://img.shields.io/badge/WhatsApp%20Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/BYgDRubCSRt7uWylK8J6cQ)
[![Bot WhatsApp](https://img.shields.io/badge/WhatsApp%20Bot-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](http://wa.me/628388906981)
# Installation
## Termux user
```cmd
$ pkg upgrade && pkg update
$ pkg install git -y
$ pkg install nodejs -y
$ pkg install ffmpeg -y
$ pkg install imagemagick -y
$ git clone https://github.com/adamdani169/RaelzaBot
$ cd RaelzaBot
$ npm i
$ node .
```
If error try using yarn instead of npm\
Jika error coba gunakan npm
```cmd
$ pkg install yarn -y
$ yarn install
```
## Termux with Ubuntu
```cmd
apt update && apt full-upgrade
apt install wget curl git proot-distro
proot-distro install ubuntu
echo "proot-distro login ubuntu" > $PREFIX/bin/ubuntu
ubuntu
```
```cmd
ubuntu
apt update && apt full-upgrade
apt install wget curl git ffmpeg imagemagick build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev dbus-x11 ffmpeg2theora ffmpegfs ffmpegthumbnailer ffmpegthumbnailer-dbg ffmpegthumbs libavcodec-dev libavcodec-extra libavcodec-extra58 libavdevice-dev libavdevice58 libavfilter-dev libavfilter-extra libavfilter-extra7 libavformat-dev libavformat58 libavifile-0.7-bin libavifile-0.7-common libavifile-0.7c2 libavresample-dev libavresample4 libavutil-dev libavutil56 libpostproc-dev libpostproc55 graphicsmagick graphicsmagick-dbg graphicsmagick-imagemagick-compat graphicsmagick-libmagick-dev-compat groff imagemagick-6.q16hdri imagemagick-common libchart-gnuplot-perl libgraphics-magick-perl libgraphicsmagick++-q16-12 libgraphicsmagick++1-dev
```
```cmd
ubuntu
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
apt install -y nodejs gcc g++ make
git clone https://github.com/adamdani169/RaelzaBot
cd RaelzaBot
npm install
npm update
```
## For WINDOWS/VPS/RDP
- Download & Install Git [Here](https://git-scm.com/downloads)
- Download & Install NodeJS [Here](https://nodejs.org/en/download)
- Download & Install FFmpeg [Here](https://ffmpeg.org/download.html) (Don't Forget Add FFmpeg to PATH enviroment variables)
- Download & Install ImageMagick [Here](https://imagemagick.org/script/download.php)
```cmd
git https://github.com/adamdani169/RaelzaBot
cd RaelzaBot
npm install
npm update
```
## Editing the file
Edit the required value in `config.json`.\
Edit yang diperlukan di `config.json`.
# Run
### Regular node:
```cmd
> node .
```
### PM2:
```cmd
> npm install pm2 -g && pm2 update $$ pm2 start index.js && pm2 save && pm2 logs
```
After that scan the QR code using your WhatsApp in your phone.\
Setelah itu pindai kode QR menggunakan WhatsApp di ponsel Anda.
## FOR REPLIT USER
[![Run on Repl.it](https://repl.it/badge/github/adamdani169/RaelzaBot)](https://repl.it/github/adamdani169/RaelzaBot)
# Features
Type `.menu` to your bot number to see the list of commands.\
Ketik `.menu` ke nomor bot untuk melihat daftar perintah.
# Thanks to
- Allah SWT
- My parents
- All friends
- All contributors
- All creator bot
- [Nurutomo](https://github.com/Nurutomo)
- [BochilGaming](https://github.com/bochilgaming)
- [adiwajshing](https://github.com/adiwajshing)
- [Fokus ID](https://github.com/Fokusdotid)
- [ShirokamiRyzen](https://github.com/ShirokamiRyzen)
- [FERDIZ-afk](https://github.com/FERDIZ-afk)
- [nvhitori](https://github.com/nvhitori)
- [SlavyanDesu](https://github.com/SlavyanDesu)
<details>
<summary>Support saia🍵🗿</summary><br>
<img src="https://telegra.ph/file/43aae0b66cf7791171d05.jpg"/>
</details>
