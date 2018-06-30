## DeezLoader Reborn V3.1.3


![](https://extraimage.net/images/2018/06/27/4a70fcd12d83ff245ffaaea9d2287215.png)

DeezLoader Reborn is here to replace the old DeezLoader V2.3.1. With this software you can download high-qualiy music and enjoy.

## Features
- Download FLAC/MP3-320 music content from Deezer(FLAC needs to be turned on in the settings 'turn on HIFI')
- Search musics
- Use Deezer links as an alternative for Searching and downloading inside the software
- Download multiple musics at a time
- Download Albums and artists
- Tagging system on MP3-320 and FLAC
- Simple and user friendly


## Supported platforms
- Windows x86 & x64
- Linux x64 & x64
- MacOS x64
- Android 


# How to run
- Download the installer and run it.
- Run DeezLoader.


## How to run on Android

Installing DeezLoader on Android is a little bit complicated but easy.<br/>
If you did installed DeezLoader and would like to just run it, go to step [5](https://git.teknik.io/Ermyas/DeezLoader/#5-run).

### How to update on Android

If you would like to update DeezLoader on android you need to first delete the folder

```
rm -rf DeezLoader-Reborn
```

Then follow from step 3

### 1. Install Termux
In order to have DeezLoader on Android you must install `termux`.
- Play Store: [link](https://play.google.com/store/apps/details?id=com.termux)
- Apk Mirror: [link](https://www.apkmirror.com/apk/fredrik-fornwall/termux)

### 2. Install dependencies
Run `Termux` and enter those lines in order:
```
pkg update && pkg upgrade && pkg install git nodejs
```
If it asks you if you want to continue, enter `y`.

### 3. Download


To download the release version:
```
git clone  https://git.teknik.io/Ermyas/DeezLoader/
```
Then navigate to the app folder using this command
```
cd DeezLoader-Reborn/app
```

### 4. Install

Now lets install what we have downloaded
```
npm install
```
In order for DeezLoader to work we need to setup storage for termux
```
termux-setup-storage
```

### 5. Run

In order to run make sure that you are in DeezLoader-Reborn/app folder run
```
cd DeezLoader-Reborn/app
```

Run the server side script
```
node app.js
```

And then go to your browser and enter to this site

[http://localhost:1730](http://localhost:1730)

# How to compile
- Download Node JS latest version
- Download the source code in the download section
- Run compile.sh/bat or run the command `npm install && npm run dist` or `yarn install && yarn run dist` if you have `yarn` installed
- Go to dist and you will see the installer and the software folder
- Have fun(Easy Peasy)

**If you are a linux user and it returns an error or stucks at creating AppImage then go to `package.json` and delete this**

```
"win":{
	"icon": "res/icon.ico"
},
"mac":{
	"icon": "res/icon.icns"
},
```
# Download Links
- Windows installer: [DeezLoader-3.1.3-win-64&32-installer.exe](https://mega.nz/#!HeYDGaBA!UIxC9jolQHbVNve5imn2Ay4HhIP6H60eVsGSM9P1oIY)
- Windows x32 portable: [DeezLoader-3.1.3-win-32-portable.7z](https://mega.nz/#!vHJ31SBR!_ILgzYz2wWVqhmWeapL8Ho5YdxWv6mrLLjTQjVgoAfk)
- Windows x64 portable: [DeezLoader-3.1.3-win-64-portable.7z](https://mega.nz/#!SGZlHSYJ!ZSfDl4kyKy2UHuRH6WCGd30EhqaUISYWJRORHTUJnr4)
- Linux x64[DeezLoader-3.1.3-linux-x64.AppImage](https://mega.nz/#!qWRRGSoY!yZudtFtTG22UJSmX_BSuJaePL9qzC72WmizugayZ0Q4)
- Linux x32 [DeezLoader-3.1.3-linux-32.AppImage](https://mega.nz/#!nfBVHCYR!_-hc8zPR3F8PJeEAOhqz4y6pIVU3QvftPO5n8ggCjJ0)
- Mac x64: [DeezLoader-3.1.3-mac-64.dmg](https://mega.nz/#!fKBQ3KQb!UomnpJhknwuCT5I-wO8pR9oo2XUQHwdP_LJkPOKAWXU)

## Join us
- Telegram news channel: [https://t.me/joinchat/AAAAAFCRjRpUr-IF96RV3g](https://t.me/joinchat/AAAAAFCRjRpUr-IF96RV3g)
- DeezLoader Telegram community group: [https://t.me/joinchat/FV19uEjZtJEkjerhZiG9nA](https://t.me/joinchat/FV19uEjZtJEkjerhZiG9nA)

# Credits
## Original Developer
-[ZzMTV](https://boerse.to/members/zzmtv.3378614/)

## Former Maintainers
-[ExtendLord](https://github.com/ExtendLord)<br/>
-[ParadoxalManiak](https://github.com/ParadoxalManiak)<br/>
-[snwflake](https://github.com/snwflake)<br/>
-[m0nster](https://t.me/m0nster_one)


# Disclaimer
- I am not responsible for the usage of this program by other people.
- I do not recommend you doing this illegally or against Deezer's terms of service.
- This project is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
