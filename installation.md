# Configuration

This Tutorial tells you how to install EGM:RP

**0. Prerequisites**

- Your server needs a valid Gameserver Login Token (GSLT) You can generate one here: https://steamcommunity.com/dev/managegameservers?l=german

**1. Download Things**

- [EGM Development Website](https://egm-development.com/) Here you have to download your DRM DLL aswell as the gamemode
- [MySQLOO Github](https://github.com/FredyH/MySQLOO/releases) EGM:RP currently only supports mysql  and no SQLite so you have to download the version that fits your server from here

---

**2. Upload things**

- After you have downloaded everything, connect to you server via FTP or if you host it locally open the server folder

- Open /garrysmod/gamemodes and create a folder called egmrp

- Put the content of the 'src' directory that is part of the egmrp.zip into the newly created folder

- Create a second folder with the name of YOUR gamemode/server project. No Special Characters or spaces allowed.

- Into this new folder you upload the content of the deriving-template/mygamemode folder and rename the mygamemode.txt to YOURFOLDERNAME.txt

- Now open /garrysmod/lua/bin, if this folder isnt present create the 'bin' folder

- Here you upload the egmrp.dll and your mysqloo dll

---

**3. Settings**

- In your egmrp/gamemode folder you'll find multiple files.

- First you have to open and read the eula.lua, after you've done that scroll completely down and accept it by setting it to true.

- After that, open the shared.lua, this is where your gamemode gets initalized and your License Key is set, put your License Key into the quotation marks behind GM.LicenseKey. You get your License Key from [EGM Development Website](https://egm-development.com/). If not contact us with your server ip

- Now open your garrysmod/cfg folder and open your server.cfg

- Put everything you want into there but also add 'sv_hibernate_think 1', without this you'll get a message like 'Server is still starting' when you try to connect.

- Add our [Content](https://steamcommunity.com/sharedfiles/filedetails/?id=1327728430) to your collection.

---

**4. Configuration**

- Configure your server [here](https://github.com/Einfach-Gaming/egmrp-wiki/blob/master/configuration.md) you can see how to it.
