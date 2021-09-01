A Woolen Sleevelet's TF2 Config, updated by Jötunn
======

Wait, you're not Woolen!
-------
Why yes, you are correct. I am not Woolen, I am Jötunn. But, I decided that after using these configs for years, that they could do with a refresh. With the advent of MasterComfig containing several functions that Woolen's config used to cover, I cleared these out to improve loading times while retaining the custom class binds while lightening the autoexec to options not easily accessible within the MasterComfig configurator webpage. Aside from that, I added more information to the configurable options to better explain what they do.

**All of these scripts are intended to be used alongside Yttrium's Viewmodel Mod. This handles all of the viewmodel hiding that Woolen uses.**

[MasterComfig, the ultimate in general purpose TF2 config, and the recommended pairing with these.](https://mastercomfig.com/ "MasterComfig")

[Yttrium's Viewmodels page w/downloadable installer](https://www.teamfortress.tv/34834/yttriums-competitive-viewmodels "Yttrium's Competitive Viewmodels")
[Installation tutorial for Yttrium's Viewmodels by Woolen](https://www.youtube.com/watch?v=4phrSBGD1qA "# Yttrium's Competitive Viewmodels in 60 Seconds")

[Woolen's Youtube Channel](www.youtube.com/user/TheBoy7477 "Woolen's Youtube link")
[Woolen's Twitter](www.twitter.com/WoolenSleevelet "Woolen's Twitter link")
[Woolen's Discord Server](www.discord.gg/8FNrdFR "Woolen's Discord server link")

[Jötunn's Discord Server (for more technical help)](https://discord.gg/NhnSysw "Jötunn's Discord server link")


Tools used to edit these configs
-------
**Code Writing**

GVIM Text Editor in Arch Linux w/KDE Plasma DE (Early 2017-) - Free - [Information and Download Here](https://www.vim.org/)

Installing the configs
-------

**Download**

To download the configs, click the green `Code` button above, then click `Download Zip` in the menu that pops up. Then, extract `Woolen-Configs-main.zip`, which should create a folder of the same name.

If you are not using MasterComfig, copy the contents of the `user` folder out of it and into the main `cfg` folder.

**Installation**

**Where to install:**

***Windows***

Navigate to:
`Program Files(x86)/Steam/SteamApps/common/Team Fortress 2/tf/cfg`

Copy+Paste the contents of `Woolen-Configs-main/cfg` folder into the above folder

***Mac OS***

Navigate to:
`(home folder)/Library/Application Support/Steam/SteamApps/common/Team Fortress 2/tf/cfg`

Copy+Paste the contents of `Woolen-Configs-main/cfg` folder into the above folder

***Linux (Most distros)***

Navigate to
`~/home/(home folder)/.steam/steam/steamapps/common/Team Fortress 2/tf/cfg`

Copy+Paste the contents of `Woolen-Configs-main/cfg` folder into the above folder

**If the above file path isn't exact to your distro, simply use the manage files menu option from within steam. The above example is the file path for most distros, as steam makes a folder link to the local data folder used by the distro within `/.steam/`**

The final file setup should look like this:
```
tf
└── cfg
    ├── antivirus.cfg
    ├── config.cfg
    ├── crouchjump.cfg
    ├── notalk.cfg
    ├── recordingstuff.cfg
    ├── scoreboard.cfg
    ├── talk.cfg
    └── user
        ├── autoexec.cfg
        ├── demoman.cfg
        ├── engineer.cfg
        ├── heavyweapons.cfg
        ├── medic.cfg
        ├── pyro.cfg
        ├── scout.cfg
        ├── sniper.cfg
        ├── soldier.cfg
        └── spy.cfg
```
Customization
-------

### While these files can be modified using any text editor, like Notepad, it is highly recommended that you use [Notepad++](https://notepad-plus-plus.org/) since it understands code batching and indentation, or any other editor that does the same. VSCode is an alternative for Windows, and Linux has a great multitude of such apps.


**General Instructions:**

Most, if not all, of the main customization is located in the `user/autoexec.cfg` file, which is done by uncommenting (removing the two slashes) in front of a setting you wish to use, and then changing any values you deem fit. If you wish to edit a specific executable `.cfg` file, go right ahead, but this is generally for people who know what they are doing.


Help and support:
-------

You can submit bug reports & questions via the [GitHub issue tracker](https://github.com/Jotunn/Woolen-Configs/issues).
You may also [Submit a pull request](https://github.com/Jotunn/Woolen-Configs/pulls), and that is great for me since you can make your own fixes and I can simply merge them into the master branch, and copy them into the versions stored on my computer.
This or simply sending me a ping over on Discord are the best ways to let me know something is borked. Links to the steam group, my Discord, and the HUDS.TF Discord are at the top of the readme.


Special Thanks
-------

Thanks to: A Woolen Sleevelet for creating the class configs and gathering the other useful bits of this.

