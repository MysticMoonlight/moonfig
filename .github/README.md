<img align="right" alt="moonfig logo" width="100" src="https://user-images.githubusercontent.com/25527589/185532914-b3f88743-8877-4f1b-85cc-c62b4396758e.png">

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

* [Game Tracking for TF2](https://github.com/SteamDatabase/GameTracking-TF2) and other tools by SteamDB, which the app uses to source various TF2 data
* Null-canceling movement script by povohat, which is used in respective mastercomfig addon
* [SourceMod](https://www.sourcemod.net/credits.php), for providing access into game internals used for research
* [sm_cvarlist](https://forums.alliedmods.net/showthread.php?p=1298262) by step, for finding hidden console variables
* [GetLaunchOptions.bat](https://pastebin.com/bhQrywES) by AveYo, for facilitating research into Windows launch options
* [cfg.tf](https://github.com/mkrl/cfgtf) by [200](https://steamcommunity.com/id/2x100/), for providing the basis for mastercomfig's own advanced customization UI
* [Leth's crosshair pack](https://www.teamfortress.tv/35367/vtf-crosshair-pack), included in the crosshair customization
* [Tob's crosshairs](https://www.teamfortress.tv/56226/tobs-crosshairs), included in the crosshair customization
* [wavesui shadowed crosshairs](https://www.teamfortress.tv/33387/wavesui) by rsbear, included in the crosshair customization
* [m0rehud black CPMA/QL crosshairs](https://www.teamfortress.tv/30008/m0rehud-black) by Quik, included in the crosshair customization
* [No explosion smoke script](https://www.teamfortress.tv/25647/no-explosion-smoke-script), included in weapons customization

## People/Organizations
Many people and organizations have helped or inspired moonfig in some way:

* [mastercoms](https://github.com/mastercoms) for creating upstream mastercomfig project
* [Chris](https://chrisdown.name/tf2/) for starting it all
* [Comanglia](https://www.teamfortress.tv/25328/comanglias-config-fps-guide) for continuing what Chris started and providing me with assistance
* [Rhapsody](https://rhapsodysl.github.io/perfconfig/) for updating Chris' config
* [JarateKing](https://github.com/JarateKing) for all their amazing work on TF2 modding and configuration
* jane for the shrinkKeyValues bash script
* Fraklin for screenshots and accompanying cfg script
* The [Valve Developer Community](https://developer.valvesoftware.com/wiki/Main_Page) for their documentation of the Source Engine
* and to Valve, for making and updating (for over a decade!) the best class-based FPS to date, and with so much customization on top

## Legal
Valve, the Valve logo, Steam, the Steam logo, Team Fortress, the Team Fortress
logo are trademarks and/or registered trademarks of Valve Corporation in the U.S. and/or other countries.

the moonfig project is not sponsored, endorsed, licensed by, or affiliated with Valve Corporation.