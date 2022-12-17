![FUZION LEECH](https://telegra.ph/file/213b587eee775e34ca221.jpg)
# Tele-LeechX Bot 
![GitHub Repo Stars](https://img.shields.io/github/stars/Omkar47/Auto-Leech?color=blue&style=plastic)
![GitHub Forks](https://img.shields.io/github/forks/Omkar47/Auto-Leech?color=green&style=plastic)
![GitHub Contributors](https://img.shields.io/github/contributors/Omkar47/Auto-Leech?style=plastic)
![GitHub Watchers](https://img.shields.io/github/watchers/Omkar47/Auto-Leech?style=plastic)
![GitHub issues](https://img.shields.io/github/issues/Omkar47/Auto-Leech?style=plastic)
![GitHub closed issues](https://img.shields.io/github/issues-closed/Omkar47/Auto-Leech?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Omkar47/Auto-Leech?style=plastic)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/Omkar47/Auto-Leech?style=plastic)
![GitHub repo size](https://img.shields.io/github/repo-size/Omkar47/Auto-Leech?color=red?style=plastic)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Omkar47/Auto-Leech?style=plastic)
[![Bot Support](https://img.shields.io/badge/Tele_LeechX-Support%20Group-blue)](https://t.me/APDBug)

**A Powerful Pyrogram Based Telegram Leech Bot** Modded by `MysterySD` to directly Leech to Telegram, with Multi Direct Links Support for Enhanced Leeching.

## Demo Group
<a href="https://t.me/FXTorrentz"><img src="https://img.shields.io/badge/FuZion Leech Bot-2cb6e0?style=for-the-badge&logo=telegram&logoColor=white"></a>


## Features Supported :-
<details>
    <summary><b>Click Here For Description</b></summary>

### From Original Repo :
- Google Drive link cloning using gclone.(wip)
- Telegram File mirrorring to cloud along with its unzipping, unrar and untar
- Drive/Teamdrive support/All other cloud services rclone.org supports
- Unzip, Unrar, Untar while Leeching to Telegram .
- Custom file name (Used in Prefix on Every Item Leeched)
- Custom commands for Using in Telegram .
- Get total size of your working cloud directory
- You can also upload files downloaded from `/ytdl` command to gdrive using `/ytdl gdrive` command.
- You can also deploy this on your VPS .
- Option to select either video will be uploaded as document or streamable
- Added `/renewme` command to clear the downloads which are not deleted automatically.
- Added support for YouTube Playlist .
- Renaming of Telegram files support added. 😐
- Changing rclone destination config on fly (By using `/rlcone` in private mode)


### From Different Repos :
- Aria2 configs In Root
- Small FIX for Gclone
- Added Dynamic Config 
- Added Custom ToggleDoc and ToggleVid Commands
- Added Custom Rename Command via vars
- Added direct rclone.conf url in vars


### New In Repo :
- Dual Commands Usage (Both With / Without Bot Username)
- Auto Commands Set To BotFather in Telegram 
- New Torrent Search Support 
```
nyaa.si, sukebei, 1337x, piratebay,
tgx, yts, eztv, torlock, rarbg
```
- Extract Error Fixed
- UI Added for Improved User Experience with Easy to Use.
- Added New Status Bar using `/status` command. 
- Added Speedtest Support.
- Direct links Supported:
```
letsupload.io, hxfile.co, anonfiles.com, bayfiles.com, antfiles,
fembed.com, fembed.net, femax20.com, layarkacaxxi.icu, fcdn.stream,
sbplay.org, naniplay.com, naniplay.nanime.in, naniplay.nanime.biz, sbembed.com,
streamtape.com, streamsb.net, feurl.com, pixeldrain.com, racaty.net,
1fichier.com, 1drv.ms (Only works for file not folder or business account), solidfiles.com 
```
- Extract these filetypes and uploads Telegram 
```
ZIP, RAR, TAR, 7z, ISO, WIM, CAB, GZIP, BZIP2, 
APM, ARJ, CHM, CPIO, CramFS, DEB, DMG, FAT, 
HFS, LZH, LZMA, LZMA2, MBR, MSI, MSLZ, NSIS, 
NTFS, RPM, SquashFS, UDF, VHD, XAR, Z.
```

</details>


## Variable Description :-


### Mandatory Variables :-
<details>
    <summary><b>Click Here For Description</b></summary>

* `TG_BOT_TOKEN`: Create a Bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API Token.

* `APP_ID`: Get this Value from [my.telegram.org/apps](https://my.telegram.org/apps).

* `API_HASH`: Get this Value from [my.telegram.org/apps](https://my.telegram.org/apps).
  * NOTE: If Telegram is blocked by your ISP, try Telegram to get the IDs.

* `AUTH_CHANNEL`: Create a Super(Means Changing it to `Visible` for `Chat History for New Members`) in Telegram, forward a Message from the Group to `@ShowJsonBot` to get this value.

* `OWNER_ID`: ID of the Bot Owner, He/She can be abled to access bot in bot only mode too(`Private mode`).

</details>


### Optional Configuration Variables :-

<details>
    <summary><b>Click Here For Description</b></summary>

* `DOWNLOAD_LOCATION`

* `MAX_FILE_SIZE`

* `TG_MAX_FILE_SIZE`

* `FREE_USER_MAX_FILE_SIZE`

* `MAX_TG_SPLIT_FILE_SIZE`

* `CHUNK_SIZE`

* `MAX_MESSAGE_LENGTH`

* `PROCESS_MAX_TIMEOUT`

* `ARIA_TWO_STARTED_PORT`

* `EDIT_SLEEP_TIME_OUT`

* `MAX_TIME_TO_WAIT_FOR_TORRENTS_TO_START`

* `FINISHED_PROGRESS_STR`

* `UN_FINISHED_PROGRESS_STR`

* `TG_OFFENSIVE_API`

* `CUSTOM_FILE_NAME`

* `LEECH_COMMAND`

* `YTDL_COMMAND`

* `GYTDL_COMMAND`

* `GLEECH_COMMAND`

* `TELEGRAM_LEECH_COMMAND`

* `TELEGRAM_LEECH_UNZIP_COMMAND`

* `PYTDL_COMMAND`

* `CLONE_COMMAND_G`

* `UPLOAD_COMMAND`

* `RENEWME_COMMAND`

* `SAVE_THUMBNAIL`

* `CLEAR_THUMBNAIL`

* `GET_SIZE_G`

* `UPLOAD_AS_DOC`: Takes two option True or False. If True file will be uploaded as document. This is for people who wants video files as document instead of streamable.

* `INDEX_LINK`: (Without `/` at last of the link, otherwise u will get error) During creating index, plz fill `Default Root ID` with the id of your `DESTINATION_FOLDER` after creating. Otherwise index will not work properly.

* `DESTINATION_FOLDER`: Name of your folder in ur respective drive where you want to upload the files using the bot.

</details>


## RClone Guide 

<details>
    <summary><b>Click Here For Description</b></summary>

- Set Rclone locally by following the official repo : https://rclone.org/docs/
- Get your `rclone.conf` file.
will look like this

```
[NAME]
type = 
scope =
token =
client_id = 
client_secret = 
```

- Copy `rclone.conf` file in the root directory (Where `Dockerfile` exists).

- Your config can contains multiple drive entries.(Default: First one and change using `/rclone` command)

</details>


## Deploying on Heroku
- Deploying on Heroku Indirectly `Supported`, Please Don't Abuse it or Share this Repo like Anything !!

<p><a href="https://github.com/5MysterySD/Tele-LeechX/blob/master/heroku-deploy.md"> <img src="https://img.shields.io/badge/Deployment%20Guide-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>

## Deploying on Okteto 

[![Develop on Okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com/deploy?repository=https://github.com/5MysterySD/Tele-LeechX&vars=[{"name":"API_ID","value":""},{"name":"API_HASH","value":""},{"name":"TG_BOT_TOKEN","value":""},{"name":"OWNER_ID","value":""},{"name":"AUTH_CHANNEL","value":""}])

## Bot Commands Available For Repo:-

<details>
    <summary><b>Click Here For Description</b></summary>

🤖Available BOT  Commands | Usage
------------ | -------------
|`/rclone`| This will change your drive config on fly.(First one will be def `/gclone`..This command is used to clone gdrive files or folder using gclone.-Syntax- `[ID of the file or folder][one space][name of your folder only(If the id is of file, don't put anything)]` and then reply /gclone to it.\
|`/log`| This will send you a txt file of the logs.
|`/ytdl`| This command should be used as reply to a [supported link](https://ytdl-org.github.io/youtube-dl/supportedsites.html)
|`/pytdl`| This command will download videos from youtube playlist link and will upload to telegram.
|`/gytdl`| This will download and upload to your cloud.
|`/gpytdl`| This download youtube playlist and upload to your cloud.
|`/leech`| This command should be used as reply to a magnetic link, a torrent link, or a direct link. this command will SPAM the chat and send the downloads a seperate files, if there is more than one file, in the specified torrent
|`/leechzip`| This command should be used as reply to a magnetic link, a torrent link, or a direct link. [This command will create a .tar.gz file of the output directory, and send the files in the chat, splited into PARTS of 1024MiB each, due to Telegram limitations]
|`/gleech`| This command should be used as reply to a magnetic link, a torrent link, or a direct link. And this will download the files from the given link or torrent and will upload to the cloud using rclone.
|`/gleechzip` | This command will compress the folder/file and will upload to your cloud.
| `/leechunzip`| This will unarchive file and dupload to telegram.
|`/gleechunzip`| This will unarchive file and upload to cloud.
|`/tleech`| This will mirror the telegram files to ur respective cloud cloud.
|`/tleechunzip`| This will unarchive telegram file and upload to cloud.
|`/getsize`| This will give you total size of your destination folder in cloud.
|`/renewme`| This will clear the remains of downloads which are not getting deleted after upload of the file or after /cancel command.
| `/rename`| u can add custom name as prefix of the original file name...Like if your file name is `gk.txt` uploaded will be what u add in `CUSTOM_FILE_NAME` + `gk.txt`..And also added custom name like...You have to pass link as ..`www.download.me/gk.txt new.txt`..the file will be uploaded as `new.txt`.
| `/toggledoc` | it used for toggling to be files if shall it be uploaded as doc via direct inchat cmd...**any users can now choose if their files will be upload as doc or streamabe...**
| `/togglevid` | it used for toggling to be files if shall it be uploaded as vid via direct inchat cmd...**any users can now choose if their files will be upload as doc or streamabe...**
| `/status`| show bot stats and concurrent downloads
| `/savethumbnail`| save the thumbnail
| `/clearthumbnail`| clear the thumbnail
| `/help`| send help

</details>


### Commands Available :-
- Set the Custom Commands in Heroku with Respective Var like leech1 or So on . .

<details>
    <summary><b>Click Here For Description</b></summary>

---
    leech - leech any torrent/magnet/direct-download link to Telegram 
	leechunzip - This will unarchive file and upload to telegram.
    leechzip - leech any torrent/magnet/direct-download link to Telegram and Upload It as .tar.gz acrhive...
    ytdl - This command should be used as reply to a supported link
    pytdl - This command will download videos from youtube playlist link and will upload to telegram.	
	toggledoc - choose whether the file shall be uploaded as doc or not
    togglevid - choose whether the file shall be uploaded as streamable or not
	savethumbnail - save thumbnail
    clearthumbnail - clear thumbnail
    tleech - This will mirror the telegram files to ur respective cloud .
    tleechunzip - This will unarchive telegram file and upload to cloud.
    gclone - This command is used to clone gdrive files or folder using gclone
    gytdl - This will download and upload to your cloud.
    gpytdl - This download youtube playlist and upload to your cloud.
    gleech - leech any torrent/magnet/direct-download link to cloud
    gleechzip - leech any torrent/magnet/direct-download link to Cloud and Upload It as .tar.gz acrhive...
    gleechunzip - This will unarchive file and upload to cloud.
    getsize - This will give you total size of your destination folder in cloud.
    rename - rename the file 
    speedtest - Check Server Speedtest 
    help - send help 
    status - show bot stats and concurrent downloads
    renewme - clear all downloads (admin only)⚠️
    log - This will send you a txt file of the logs.(admin only)⚠️
    rclone - This will change your drive config on fly.(First one will be default)--(admin only)⚠️
---

</details>


## Give A ⭐ Star ⭐ Before You Go Anywhere 


## Credits Goes To 🎖🏆  . . .

<details>
    <summary><b>Click Here For Description</b></summary>

* [`MysterySD`](https://github.com/5MysterySD) Meh 🧐 For Speedtest, Direct Link Support, More in Future. 
* [`KGK06`](https://github.com/KGK06) For Merging Different Repos 
* [`XcodersHub`](https://github.com/XcodersHub) For The Aria2 Config & Little More
* [`GautamKumar`](https://github.com/gautamajay52/TorrentLeech-Gdrive) 😬
* [`SpEcHiDe`](https://github.com/SpEcHiDe/PublicLeech) for his wonderful code😚
* [`Rclone Team`](https://rclone.org) for theirs awesome tool☁️
* [`Dan Tès`](https://telegram.dog/haskell) for his [Pyrogram Library](https://github.com/pyrogram/pyrogram)
* [`Robots`](https://telegram.dog/Robots) for their [@UploadBot](https://telegram.dog/UploadBot)
* [`@AjeeshNair`](https://telegram.dog/AjeeshNait) for his [torrent.ajee.sh](https://torrent.ajee.sh)
* [`@gotstc`](https://telegram.dog/gotstc), `@aryanvikash`, [`@HasibulKabir`](https://telegram.dog/HasibulKabir) for their TORRENT groups

</details>

