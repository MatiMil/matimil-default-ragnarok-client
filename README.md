# Froggo Rö Folder 🐸

![Folder Size](https://img.shields.io/badge/Folder%20Size-2.96GB-lightgreen)


This is a simple RO folder that contains everything you need to run a **`2022-04-06`** client, the latest *publicly* available.

I have cleaned and compressed the **`data.grf`** file to reduce its size from **`3.87GB`** to **`2.14GB`**. **`official_data.grf`** took the same treatment and the file size went down to **`426MB`**.

Additionally, I have added a mini-map to all those maps that were lacking one, approximately  **`275`** mini-maps were added, I only ignored some indoor (_in) and guild castles maps.

##### Before BGM, the Rö folder has a total size of **`2.62GB`**, after BGM it reaches **`2.96GB`**

## Screenshots

![Froggo Ro Client - Login Screen](https://images.weserv.nl/?url=https://i.imgur.com/3y0gpuw.png?v=4&default=https://i.imgur.com/3y0gpuw.png&fit=cover&maxage=7d&l=9)

![Froggo Ro Client - Map Server](https://images.weserv.nl/?url=https://i.imgur.com/hDloxHw.png?v=4&default=https://i.imgur.com/hDloxHw.png&fit=cover&maxage=7d&l=9)

## Requirements

- Server Up & Running with **`PACKETVER=20220406`**

- [Visual C++ Redistributables](https://github.com/abbodi1406/vcredist/releases/latest/download/VisualCppRedist_AIO_x86_x64.exe)

- [DirectX Runtime](https://download.microsoft.com/download/1/7/1/1718CCC4-6315-4D8E-9543-8E28A4E18C4C/dxwebsetup.exe)

## Features
 - Includes latest [RoEnglishRE](https://github.com/llchrisll/ROenglishRE/) - *10/Sept/2024*
   - [Custom Lua Support](https://llchrisll.github.io/ROTPDocs/addons/#custom-lua-support)
   - [jRO Enchantment Display](https://llchrisll.github.io/ROTPDocs/addons/#jro-enchants-display)
  
 - Includes [rsu-kro-rag-lite (kRO updater)](https://nn.ai4rei.net/dev/rsu/) - *v4.2.2.1316*

 - Includes [opensetup](https://nn.ai4rei.net/dev/opensetup/) - *v3.1.0.627*

 - Includes [iRO's Setup.exe](# "It's in English 🤓"), thanks to relzz!

 - Includes [AzzyAI 1.55](https://github.com/SpenceKonde/AzzyAI) 

 - Includes a [Packet Viewer](https://i.imgur.com/rxfWgQ3.png)

## Download

You can [**click here**](https://gitlab.com/SapitoSucio/ro-folder/-/archive/main/ro-folder-main.zip) to download a .zip file of this ro-folder 🔸 [**~fast mirror (●'◡'●)~**](https://qiwi.gg/file/brYo0305-ro-folder "Really Fast, but dont fall for the ADS 🐸👍")


## Extra

> 👾 [Warp Profile for 2022-04-06 used for FroggoClient.exe](https://www.mediafire.com/file/9nednu5y8vcan7i/2022-04-06Patches.yml/file) 🔸 [(mirror)](https://drive.google.com/file/d/1Yd52mAJrdrDzDkbHeWvJSlw_r2nuiPmT/view?usp=sharing)

> 🕹️ [2022-04-06 Vanilla Ragexe](https://nemo.herc.ws/downloads/2022-04-06_Ragexe_1648707856/)
  
> 🖼️ [Client Login Screen Creator](https://sapitosucio.github.io/FroggoCutter/)


> 📦 [Official kRO Zipped Folder (10/June/2024) **(3.84GB)**](http://rofull.gnjoy.com/Ragnarok_240610.zip) 

> 📦 [Official kRO EXE Installer (08/Jan/2024) **(3.80GB)**](http://rofull.gnjoy.com/RAG_SETUP_240108.exe) 🔸 [(mirror)](https://archive.org/details/rag-setup-240108 "Thx to Archive.org 🐸👍")

## FAQ

### Why am I getting **CHARACTER_INFO size** error when trying to log in ?

> Possible reasons:
> - You using **outdated** rAthena which doesn't work with 2022-04-06 client
> - You haven't set correct **PACKETVER** or done it with mistakes (skill issue 💅)
> - You haven't **recompiled** rAthena after changing **PACKETVER**
> - You haven't **restarted** server after **recompilation**

### Why am I getting errors about **MSVCP140.dll**, **VCRUNTIME140.dll** when executing FroggoClient.exe?

> You haven't installed **`Visual C++ Redist`**, check [requirements](#requirements) section, if problem persists, try installing this too [Visual C++ Redist for VS 2012u4](https://www.microsoft.com/es-es/download/details.aspx?id=30679) 

### What is **official_data.grf** ?

> **`official_data.grf`** is from the [ROResourceCollection](https://github.com/llchrisll/ROResourceCollection "Chris's project 🐸" ) project, which brings many items, mobs and npc files from other RO Regions and merges it into one convenient grf.

### Why does the Setup.exe opens instead of the FroggoClient.exe ?

> In your Windows registry there is no data about your selected graphic card, to fix it, just set up your settings in **`Setup.exe`** and click on *OK*, be aware to don't select **DirectX9**, stay on **DirectX7** 😡


### What was removed from the data.grf?

> Several unnecessary files were removed from the **`data.grf`** archive. These included residual files such as **`thumbs.db`** and stray **`BMP Screenshots`**. However, the majority of the cleanup was performed in the **`mob`** and **`npc`** sprite folders.
>
> In these folders, some **`.spr`** files contained sprites (images) that were not utilized in their corresponding **`.act`** files. For instance, consider the monster **katrinn**, its **`.spr`** file contained approximately 140 images, but only 6 of them were actually used.
>
> In total, out of nearly **90,000** collective images, around **9,400** were removed **alv**.
>
> Additionally, every **`.bmp`** image was converted to **8-bit color depth**. This not only saves space in the archive but also makes it easier for the RO client to handle these images efficiently. Furthermore, both **PNGs** and **JPGs** underwent compression to reduce their file sizes.
