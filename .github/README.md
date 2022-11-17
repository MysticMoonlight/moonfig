<img align="right" alt="moonfig logo" width="100" src="https://user-images.githubusercontent.com/25527589/185532914-b3f88743-8877-4f1b-85cc-c62b4396758e.png">

# We're back!
We are back into working on moonfig! We are working on some changes to this project. Stay tuned.

# moonfig
moonfig is the fork of mastercomfig, a modern customization framework without bloats, respecting the user's choice rather than being controlled by the script.

moonfig is a modern customization framework, and aims to disable heavily unoptimized features and adjust other settings where it does not affect behavior or visuals noticeably. It also has customization features so that you may adjust settings to your needs/preferences.

You may find that moonfig makes TF2 a lot smoother, eliminates stuttering, reduces load times and increases FPS while respecting the user's choice.

moonfig is constantly updated following the new tweaks and features from upstream mastercomfig, while not adding many bloats into the scripts — ierated upon based on user feedback and benchmarks. If you think there's an unoptimal value, or if it's as simple as a comment being confusing to you, report the problem or make a pull request through `canary` branch and you'll most likely see a fix in a future update.

## Features & Differences with upstream
* Removes unnecessary bloats which does not respect user's choices. On upstream version it force disables the sprays, and disables HTML MOTD which is required for some interaction with some servers like Titan.TF. Now these settings are no longer forced by default.
* We will never add Ko-fi exclusive releases, which means there won't be any releases which requires monthly subscription by default. We don't plan to monetize the script in a either way.
* Community maintained, and always will be. We welcomes any contribution to the project.
* Only focused on improving the performance rather than taking away user's choice.
* Mods now consist of two mods: moonfig-core and moonfig-config. Instead of seperating the mod based on preset we now use moonfig-config to configure the presets using `moonfig-config/cfg/presets.cfg`.
* All overrides configurations are ready, now you don't need to create overrides folder for yourself. Every overrides are stored inside moonfig-config folder.

## Software/Projects
moonfig could not be where it is today without the use of many valuable community projects:

* [Game Tracking for TF2](https://github.com/SteamDatabase/GameTracking-TF2)
* [SourceMod](https://www.sourcemod.net/credits.php)
* [sm_cvarlist](https://forums.alliedmods.net/showthread.php?p=1298262)
* [GetLaunchOptions.bat](https://pastebin.com/bhQrywES)
* [cfg.tf](https://github.com/mkrl/cfgtf)

## People/Organizations
Many people and organizations have helped or inspired moonfig in some way:

* [mastercoms](https://github.com/mastercoms)
* [Chris](https://chrisdown.name/tf2/)
* [Comanglia](https://www.teamfortress.tv/25328/comanglias-config-fps-guide)
* [Rhapsody](https://rhapsodysl.github.io/perfconfig/)
* [JarateKing](https://github.com/JarateKing)
* jane
* Fraklin
* [Valve Developer Community](https://developer.valvesoftware.com/wiki/Main_Page)
* [Valve Corportation](https://www.valvesoftware.com/en/)

## Legal
Valve, the Valve logo, Steam, the Steam logo, Team Fortress, the Team Fortress
logo are trademarks and/or registered trademarks of Valve Corporation in the U.S. and/or other countries.

the moonfig project is not sponsored, endorsed, licensed by, or affiliated with Valve Corporation.
