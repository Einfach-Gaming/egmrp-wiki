# Configuration

These Tutorials require you to have already [installed EGM:RP](https://github.com/Einfach-Gaming/egmrp-wiki/blob/master/installation.md).

**1. Basic Configuration** - *mygamemode/gamemode/shared.lua*

- In this file you can set a few very basic setting like the display name of the gamemode and the version number of your server.

---

**2. Gamemode Configuration** - *mygamemode/gamemode/config/gamemode.lua*

- The first part of this configuration file contains the basic settings of the gamemode like Name, Prefix, PrefixColor, Language and more...

- The next part is for enabling/disabling all the modules included into the gamemode.

- You can also enable your own modules here by adding them to the configuration file.

---

**3. Module Configuration** - *mygamemode/gamemode/config/\*.lua*

- The other configuration files in this folder all describe a single module of the gamemode.

- Most [modules](modules) (except the core ones) need to be enabled for them to load. If the module is enabled, its configuration file can be used, to configure the module to your hearts desire.

- This includes values like: Permissions, Default Values, Enabling Chats, etc...

- All configuration files are documented by comments for every single value you can set in them.

- The most important config of these is the **"sv_sql.lua"**. Without it you will not be able to create any character, factions, ranks or even store playerdata. We currently do not support any local data storage.

---

**4. Workshop Content** - *mygamemode/gamemode/sv_content.lua*

- This file is used to add all your workshop add-ons to be downloaded by joining users.

- Instructions on how to use the file are inside the file.
