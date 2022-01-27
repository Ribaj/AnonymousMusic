<h1 align= center><b>💕 Anonymous Music 💕</b></h1>
<h3 align = center> A Telegram Music Bot written in Python using Pyrogram and Py-Tgcalls for playing Audios & Videos in Telegram by the help of Telegram Video Chat Feature</h3>

<p align="center">
<a href="https://python.org"><img src="http://forthebadge.com/images/badges/made-with-python.svg" alt="made-with-python"></a>
<br>
    <img src="https://img.shields.io/github/license/AnonymousBoy1025/AnonymousMusic?style=for-the-badge" alt="LICENSE">
    <img src="https://img.shields.io/github/contributors/AnonymousBoy1025/AnonymousMusic?style=for-the-badge" alt="Contributors">
    <img src="https://img.shields.io/github/repo-size/AnonymousBoy1025/AnonymousMusic?style=for-the-badge" alt="Repository Size"> <br>
    <img src="https://img.shields.io/github/forks/AnonymousBoy1025/AnonymousMusic?style=for-the-badge" alt="Forks">
    <img src="https://img.shields.io/github/stars/AnonymousBoy1025/AnonymousMusic?style=for-the-badge" alt="Stars">
    <img src="https://img.shields.io/github/watchers/AnonymousBoy1025/AnonymousMusic?style=for-the-badge" alt="Watchers">
    <img src="https://img.shields.io/github/commit-activity/w/AnonymousBoy1025/AnonymousMusic?style=for-the-badge" alt="Commit Activity">
    <img src="https://img.shields.io/github/issues/AnonymousBoy1025/AnonymousMusic?style=for-the-badge" alt="Issues">
</p>

## 🔥 <a name="features"></a>Features

### ⚡️ Fast AF

Starts streaming your inputs while downloading and converting them. Also, it
doesn't make produce files.

### 🔗 Safest 

Restricts control and sensitive commands to admins.

### 🗑 Super Clean

Deletes old playing trash to keep your chats clean.

### 😇 Awesome Controls

Lets you switch stream mode, loop, pause, resume, mute, unmute anytime.

### 🤤 Cool Thumbnails

Response your commands with cool thumbnails on the chat.

### 😉 Stream Everything 

You can stream audio or video files, YouTube videos with any duration,
YouTube lives, YouTube playlists and even custom live streams like radios or m3u8 links or files in
the place it is hosted!

### 🕕 Multiple Stream at a time

Allows you to stream different things in multiple chats simultaneously. Each
chat will have its own song queue.

### 😴 Multi Language

Music Player is multilingual and speaks [various languages](#languages),
thanks to the translators.

## 🚀 <a name="deploy"></a>Deploy

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/AnonymousBoy1025/AnonymousMusic)

Note: `First Fork The Repo Then Click On Deploy To Heroku Button!`


## ☁️ <a name="self_host"></a>Self Host

- Legecy Method
```bash
$ git clone https://github.com/AnonymousBoy1025/AnonymousMusic
$ cd AnonymousMusic
$ sudo apt install git curl python3-pip ffmpeg -y
$ pip3 install -U pip
$ curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -
$ sudo apt install -y nodejs
$ sudo apt install build-essential
$ sudo npm install pm2@latest -g
$ pip3 install -U -r requirements.txt
$ cp sample.env .env
# < edit .env with your own values >
$ python3 main.py
```

- Docker Build Method
```bash
$ git clone https://github.com/AnonymousBoy1025/AnonymousMusic
$ cd AnonymousMusic
$ cp sample.env .env
# < edit .env with your own values >
$ sudo docker build . -t anonymousmusic
$ sudo docker run anonymousmusic
```

## ⚒ <a name="configs"></a> Required Vars

- `API_ID`: Telegram app id from https://my.telegram.org/apps.
- `API_HASH`: Telegram app hash from https://my.telegram.org/apps.
- `SESSION`: Pyrogram string session. You can generate from [here](https://telegram.me/AnonymousStringBot).
- `SUDOERS`: ID of sudo users (separate multiple ids with space).
- `BOT_TOKEN`: Telegram bot token from https://t.me/botfather. (optional)
- `QUALITY`: Custom stream quality (high/medium/low) for the userbot in vc. Default: `high`
- `PREFIX`: Bot commad prefixes (separate multiple prefix with space). Eg: `! /`
- `LANGUAGE`: An [available](#languages) bot language (can change it anytime). Default: `en`
- `STREAM_MODE`: An stream mode like audio or video (can change it anytime). Default: `audio`
- `ADMINS_ONLY`: Put `True` if you want to make /play commands only for admins. Default: `False`
- `SPOTIFY_CLIENT_ID`: Spotify client id get it from [here](https://developer.spotify.com/dashboard/applications). (optional)
- `SPOTIFY_CLIENT_SECRET`: Spotify client secret get it from [here](https://developer.spotify.com/dashboard/applications). (optional)


## 📄 <a name="commands"></a>Commands

Command | Description
:--- | :---
• /ping | Check if alive or not
• /start / !help | Show the help for commands
• /mode / !switch | Switch the stream mode (audio/video)
• /p / /play [song name or youtube link] | Play a song in vc, if already playing add to queue
• /radio / /stream [radio url or stream link] | Play a live stream in vc, if already playing add to queue
• /pl / /playlist [playlist link] | Play the whole youtube playlist at once
• /skip / /next | Skip to the next song
• /m / /mute | Mute the current stream
• /um / /unmute | Unmute the muted stream
• /ps / /pause | Pause the current stream
• /rs / /resume | Resume the paused stream
• /list / /queue | Show the songs in the queue
• /mix / /shuffle | Shuflle the queued playlist
• /loop / /repeat | Enable or disable the loop mode
• /lang / language [language code] | Set the bot language in group
• /ip / /import | Import queue from exported file
• /ep / /export | Export the queue for import in future
• /stop / /leave | Leave from vc and clear the queue
• /update / /restart | Update and restart your music player

## 🗣 <a name="languages"></a>Languages

```text
en    English
```

## 💜 <a name="contribute"></a>Contribute

New languages, bug fixes and improvements following
[our contribution guidelines](./CONTRIBUTING.md) are warmly welcomed!

## 🛫 <a name="supports"></a>Supports

For any kind of help join our [Support Group](https://telegram.me/DevilsHeavenMF) or raise an [issue](https://github.com/AnonymousBoy1025/AnonymousMusic/issues).

## ✨ <a name="credits"></a>Credits

- [𝝙𝗡𝗢𝗡𝗬𝗠𝗢𝗨𝗦](https://github.com/AnonymousBoy1025) for [Everything](https://github.com/AnonymousBoy1025/AnonymousMusic) 😇
- [Dan](https://github.com/delivrance) for [Pyrogram](https://github.com/pyrogram/pyrogram) 💕
- [Laky-64](https://github.com/Laky-64) for [Py-TgCalls](https://github.com/pytgcalls/pytgcalls) 💕
- And Thanks To All [Contributors](https://github.com/AnonymousBoy1025/AnonymousMusic/graphs/contributors)! 💕

### 📃 <a name="license"></a>License

Anonymous Music is licenced under the GNU Affero General Public License v3.0.
Read more [here](./LICENSE).
