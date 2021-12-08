<p align="center">
    <img src="https://telegra.ph/file/cc5ce3e7cf934ea8268af.jpg" width="50%" height="50%" alt="Yuki"/>
    <br>
    <a href="https://github.com/Akumayuki"><img title="Created by" src="https://img.shields.io/badge/Creator-Yukialtair-green?style=for-the-badge&logo=github"></a>
</p>

# RECODE WABOT-AQ

Simple WhatsApp Bot

<p align="center">
  <a href="https://github.com/Akumayuki"><img src="http://readme-typing-svg.herokuapp.com?color=7FFF00&center=true&vCenter=true&multiline=false&lines=Simple+Whatsapp+Bot;Base+ori+by+Nurutomo;Give+star+and+forks+this+repo+:)" alt="UwU">
</p> 

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/LitRHap/wabot)
# Chat sini kalo eror/ga paham
* [`chat sini`](https://wa.me/6283847405260) 
## FOR TERMUX/UBUNTU/SSH USER

```bash
apt update && apt upgrade
apt install git -y
apt install nodejs -y
apt install ffmpeg -y
apt install imagemagick -y
git clone https://github.com/LitRHap/wabot
cd wabot-aq
npm install
npm i hmtai
npm i booru
npm i image-to-pdf
npm i nhentai-node-api
npm i acrcloud
npm i sagiri
npm update
```

---------

## FOR WINDOWS/VPS/RDP USER

* Download And Install Git [`Click Here`](https://git-scm.com/downloads)
* Download And Install NodeJS [`Click Here`](https://nodejs.org/en/download)
* Download And Install FFmpeg [`Click Here`](https://ffmpeg.org/download.html) (**Don't Forget Add FFmpeg to PATH enviroment variables**)
* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/LitRHap/wabot
cd wabot-aq
npm install
npm update
```

---------

## Run

```bash
node .
```

---------

## Arguments `node . [--options] [<session name>]`

### `--self`

Activate self mode (Ignores other)

### `--pconly`

If that chat not from private bot, bot will ignore

### `--gconly`

If that chat not from group, bot will ignore

### `--swonly`

If that chat not from status, bot will ignore

### `--prefix <prefixes>`

* `prefixes` are seperated by each character
Set prefix

### `--server`

Used for [heroku](https://heroku.com/) or scan through website

### `--db <json-server-url>`

Use external db instead of local db, 
Example Server `https://json-server.nurutomo.repl.co/`
Code: `https://repl.it/@LitRHap/json-server`

`node . --db 'https://json-server.litrhap.repl.co/'`

The server should have like this specification

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

If small qr unicode doesn't support

### `--restrict`

Enables restricted plugins (which can lead your number to be **banned** if used too often)

* Group Administration `add, kick`

### `--img`

Enable image inspector through terminal

### `--autoread`

If enabled, all incoming messages will be marked as read

### `--nyimak`

No bot, just print received messages and add users to database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------

THANKS TO:
    [![Nurutomo](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo)
    [![LitRhap](https://github.com/LitRHap.png?size=100)](https://github.com/LitRHap)
    [![Akumayuki](https://github.com/Akumayuki.png?size=100)](https://github.com/Akumayuki)
