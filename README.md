<div align="center">
<img src="https://images2.alphacoders.com/200/200010.jpg" alt="MAF's Assistant V8" width="528" />

# MAF's Assistant V8

 MAF's Assistant is a multipurpose WhatsApp bot using wa-automate-nodejs library!



<p align="center">
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd"><img title="Author" src="https://img.shields.io/badge/Author-Maulana Akbar F.-purple.svg?style=for-the-badge&logo=github" /></a>
</p>
<p align="center">
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd"><img title="RATING" src="https://img.shields.io/badge/BASIC RATING-45%20%2F%20100-green?colorA=%23555555&colorB=%23FC5E00&style=for-the-badge"></a>
</p>
<p align="center">
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd"><img title="RATING" src="https://img.shields.io/badge/PREMIUM RATING-97%20%2F%20100-green?colorA=%23555555&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd/mafv8"><img title="Stars" src="https://img.shields.io/github/stars/MAULANAAKBARFIRDAUSYA-cmd/mafv8?color=red&style=flat-square" /></a>
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd/mafv8/network/members"><img title="Forks" src="https://img.shields.io/github/forks/MAULANAAKBARFIRDAUSYA-cmd/mafv8?color=red&style=flat-square" /></a>
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd/mafv8/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/MAULANAAKBARFIRDAUSYA-cmd/mafv8?label=watchers&color=blue&style=flat-square" /></a> <br>
  <a href="https://www.npmjs.com/package/@open-wa/wa-automate"><img src="https://img.shields.io/npm/v/@open-wa/wa-automate.svg?color=green" /></a>
  <img src="https://img.shields.io/node/v/@open-wa/wa-automate" />
  <img src="https://img.shields.io/badge/maintained%3F-yes-green.svg?style=flat" />
  <img src="https://img.shields.io/github/repo-size/MAULANAAKBARFIRDAUSYA-cmd/mafv8" /> <br>
</p>

<p align="center">
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd/mafv8#requirements">Requirements</a> •
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd/mafv8#installation">Installation</a> •
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd/mafv8#features">Features</a> •
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd/mafv8#thanks-to">Thanks to</a> •
  <a href="https://github.com/MAULANAAKBARFIRDAUSYA-cmd/mafv8#license">License</a>
</p>

<h4 align="center">
<details>
 <summary>Contact me!</summary></a></p>
 
[GitHub](https://github.com/MAULANAAKBARFIRDAUSYA-cmd)</a></p>
[My WhatsApp](https://wa.me/+6285236167349)</a></p>
[My WhatsApp BOT](https://wa.me/+6289504990855)</a></p>
[Telegram](https://t.me/maulanaakbarf)</a></p>
</h4>

</div>

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker GIF command)
* Any text editor

# Installation
## 📝 Cloning this repo
```bash
> git clone https://github.com/MAULANAAKBARFIRDAUSYA-cmd/mafv8
> cd mafv8
```

## 🔍 Installing the dependencies
```bash
> npm install
```
atau
```bash
> npm i
```

## 🆗 Running the bot
Regular node:
```bash
> npm start
```

PM2:
```bash
> pm2 start index.js
> pm2 monit
```

PM2 with cron job (restart after 5 hours):
```bash
> pm2 start index.js --cron "* */5 * * *"
> pm2 monit
```

After that scan the QR code using your WhatsApp in your phone!

## ✍️ Editing the file
Edit the required value in `config.json`.
```json
{
    "ownerBot": "62852xxxxxxxx@c.us", 
    "prefix": "$",
    "uaOverride": "WhatsApp/2.2037.6 Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/85.0.4183.83 Safari/537.36",
    "token": "api-key",
    "nao": "api-key",
    "vhtear": "api-key",
    "melodic": "administrator"
}
```

`ownerBot`: your WhatsApp number.  
`prefix`: bot's prefix.  
`uaOverride`: your user agent.  
`token`: API token. You can get it [here](https://api.i-tech.id) by creating an account. After that, set your server/host static IP in [here](https://api.i-tech.id/settings/profile).  
`nao`: SauceNAO API token. You can get it [here](https://saucenao.com/user.php) by creating an account.  
`vhtear`: VHTear API token. You can get it [here](https://api.vhtear.com/) by purchasing his API key.  
`melodic`: MelodicXT API token. You can use `administrator` key.  

## 🗣️ Changing language
If you want to change the language, replace all `ind` function to `eng`.   
Example:
```js
ind.wrongFormat()
```
To:
```js
eng.wrongFormat()
```

# Features
If you want to unlock premium commands, please contact me~

|     Leveling     |  Availability  |
| :--------------: | :------------: |
| Leveling         |       ✔️       |
| Set background   |       ✔️       |
| Set status color |      Soon      |
| Set level color  |      Soon      |
| Set XP color     |      Soon      |
| Set bar color    |      Soon      |

|     Sticker Maker     | Availability |
| :-------------------: | :----------: |
| Send/reply image      |      ✔️      |
| Send/reply GIF        |      ✔️      |
| Send/reply MP4        |      ✔️      |
| Text to sticker       |      ✔️      |
| Text to sticker GIF   |      ✔️      |
| Sticker to image      |      ✔️      |

|      Downloader     | Availability |
| :-----------------: | :----------: |
| Facebook video      |      ✔️      |
| YouTube audio/video |      ✔️      |
| Joox                |      ✔️      |
| TikTok              |      ✔️      |
| TikTok pic          |      ✔️      |
| Twitter             |      ✔️      |
| Instagram post      |      ✔️      |
| Instagram story     |      ✔️      |
| Layarkaca21 film    |      ✔️      |

|         Misc        | Availability |
| :-----------------: | :----------: |
| Say                 |      ✔️      |
| Lyric finder        |      ✔️      |
| Shortlink maker     |      ✔️      |
| Wikipedia           |      ✔️      |
| KBBI search         |      ✔️      |
| IG stalk            |      ✔️      |
| GSMArena            |      ✔️      |
| Food receipt finder |      ✔️      |
| YouTube search      |      ✔️      |
| TTS                 |      ✔️      |
| AFK                 |      ✔️      |
| Distance calculator |      ✔️      |
| Find sticker        |      ✔️      |
| List surah          |      ✔️      |
| Math                |      ✔️      |
| Surah               |      ✔️      |
| Random contact      |      ✔️      |
| Play YouTube        |      ✔️      |
| Whois               |      ✔️      |
| SMS gateway         |      ✔️      |
| Tafsir Al-Qur'an    |      ✔️      |
| Al-Kitab search     |      ✔️      |
| LK21                |      ✔️      |
| Reminder            |      ✔️      |
| Image to URL        |      ✔️      |
| Jadwal sholat       |      ✔️      |
| Line sticker latest |      ✔️      |
| Cek ongkir          |      ✔️      |

|          Fun          | Availability |
| :-------------------: | :----------: |
| Harta tahta maker     |      ✔️      |
| Calender image maker  |      ✔️      |
| Weton jodoh           |      ✔️      |
| Zodiac                |      ✔️      |
| Write on paper        |      ✔️      |
| Missing person maker  |      ✔️      |
| Valentine frame maker |      ✔️      |
| Glitch text maker     |      ✔️      |
| SimSimi               |      ✔️      |
| Blackpink logo maker  |      ✔️      |
| Pornhub logo maker    |      ✔️      |
| Galaxy text maker     |      ✔️      |
| Truth or dare         |      ✔️      |
| TikTok asupan         |      ✔️      |
| PH comment maker      |      ✔️      |
| Triggered effect      |      ✔️      |
| Deep fry effect       |      ✔️      |
| Kiss someone          |      ✔️      |
| 3D Text               |      ✔️      |
| Freefire logo         |      ✔️      |
| Freefire banner       |      ✔️      |

|      Weeb Zone     | Availability |
| :----------------: | :----------: |
| Random neko girl   |      ✔️      |
| Random wallpaper   |      ✔️      |
| Random kemonomimi  |      ✔️      |
| Kusonime scrapper  |      ✔️      |
| Komiku scrapper    |      ✔️      |
| Anime tracer       |      ✔️      |
| Source finder      |      ✔️      |
| Random waifu       |      ✔️      |
| Anitoki latest     |      ✔️      |

|        Bot       | Availability |
| :--------------: | :----------: |
| Toogle NSFW      |      ✔️      |
| Bot usage status |      ✔️      |
| Blocked list     |      ✔️      |
| Ping             |      ✔️      |
| Delete message   |      ✔️      |
| Report bug       |      ✔️      |
| Join group       |      ✔️      |

|        Owner       | Availability |
| :----------------: | :----------: |
| Broadcast          |      ✔️      |
| Clear all messages |      ✔️      |
| Leave all groups   |      ✔️      |
| Get snapshot       |      ✔️      |
| Ban                |      ✔️      |
| Eval               |      ✔️      |
| Shutdown           |      ✔️      |
| Add premium user   |      ✔️      |
| Set bot's info     |      ✔️      |

|    Moderation    | Availability |
| :--------------: | :----------: |
| Add              |      ✔️      |
| Kick             |      ✔️      |
| Promote          |      ✔️      |
| Demote           |      ✔️      |
| Leave bot        |      ✔️      |
| Everyone         |      ✔️      |
| Toogle NSFW      |      ✔️      |
| Set group icon   |      ✔️      |
| Anti-group link  |      ✔️      |
| Toogle welcome   |      ✔️      |
| Auto-sticker     |      ✔️      |
| Mute group       |      ✔️      |

|        NSFW        | Availability |
| :----------------: | :----------: |
| Lewds              |      ✔️      |
| nHentai lookup     |      ✔️      |
| Fetish             |      ✔️      |
| Latest Nekopoi     |      ✔️      |
| Waifu NSFW         |      ✔️      |
| Pornhub downloader |      ✔️      |
| Waifu 18+          |      ✔️      |
| nHentai downloader |    Premium   |
| Multi lewds        |    Premium   |
| Multi fetish       |    Premium   |

# Thanks to
* [`open-wa/wa-automate-nodejs`](https://github.com/open-wa/wa-automate-nodejs)
* [`MAF's Assistant V5`](https://github.com/MAULANAAKBARFIRDAUSYA-cmd/mafv5)

# License
**MAF's Assistant** © [Maulana Akbar Firdausya](https://github.com/MAULANAAKBARFIRDAUSYA-cmd), released under the MIT License.
Authored and maintained by Maulana Akbar Firdausya.
