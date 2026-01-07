---
title: ⚙️ Emulation, Homebrew, Misc.
description: Emulation, hacking, and homebrew resources and recommendations
tags:
  - videogame
---
# Emulation
> [!tip]- Use the wiki if you dont know what the best emulator is for any given system.
> This information is heavily subject to change over time (the scene moves faster than you'd think), so I dont list my individual emulator recommendations here. Use the wiki!
> If you want Citra or Yuzu for whatever reason, you can use [this article](https://rentry.org/YuzuCitra), albeit it's a tad out of date.
#### 🌟 [Emulation General Wiki](https://emulation.gametechwiki.com/)
Learn about emulation, including what the best emulator for a given system is.
	Lists all noteworthy emulators for any given console, provides a feature comparison between them, lists where to get resources for each emulator, frontends, FAQ, guides, and more.
	- Compatibility lists
		For any given emulator, developers will often list all games for the emulator's target console, and how well they're emulated. In some cases (such as the [Dolphin Wiki](https://wiki.dolphin-emu.org/index.php?title=Main_Page)), they'll even list optimal settings, enhancements, and more for individual games.
#### 🌟 [RetroAchievements](https://retroachievements.org/)
Achievements in retro games.
	Supported by many emulators and front ends. Lets you create a profile and acquire user-created achievements in various games. The emulation scene continues to BTFO Nintendo on basic features.
#### [Retroarch](https://www.retroarch.com/) 
The frontend for Libretro.
	Nice if you want to navigate your collection with a controller, and especially useful if you're looking to use it's unique features (netplay, [shaders](https://youtu.be/mp0CF2S9N5o), etc).
	I prefer it to standalone counterparts for most generation 5 consoles and older, admittedly.
	Retroarch is also nice for emulating on console. I have Retroarch installed on my Switch 1, for example. Fuck the Nintendo Classics shitto rent-but-never-own bullshit.
	- Retroarch System Files ([Myrient](https://myrient.erista.me/files/Internet%20Archive/chadmaster/RetroarchSystemFiles/Retroarch-System/), [Archive.org](https://archive.org/details/RetroarchSystemFiles)) - a drag-n-drop collection of system files (bios) for Retroarch.
> [!note]- Claims of abusive behavior regarding Retroarch's lead developer [\[1\]](https://x.com/BlueMaxima/status/1488826694626525185)
> squerepusher/TwinAphex has a lot of allegations regarding abusive behavior towards other developers in the emulation scene, including potentially contributing to Near's suicide, blackmailing Stenzek, and more. None of this information is compiled in a formal/centralized source, but I'd be remiss not to mention it. Hopefully the scene creates a competitive alternative some day.
>> [!info] Retroarch Alternatives: [Emulation Wiki's Frontends article](https://emulation.gametechwiki.com/index.php/Frontends), [OpenEmu](https://openemu.org/) (Mac), and keep an eye on [Highscore](https://gitlab.gnome.org/World/highscore) (linux, unreleased). These, or ES-DE (below)
#### [**ES-DE**](https://www.es-de.org/) (formerly EmulationStation Desktop Edition)
My preferred frontend for emulated games. Browse your library beautifully and with a controller.
	I enjoy exploring with ES-DE more than in Retroarch. Though I do often launch the game with Retroarch, since I like the way Retroarch actually handles running games from an end-user perspective. That said, you could easily configure it to run games in their respective standalone emulators.
	My favorite theme is [ES-DE mini](https://github.com/Weestuarty/mini-es-de).
#### 🌟 [Fightcade](https://www.fightcade.com/) 
The definitive way to play virtually every retro fighting game online, with rollback.
	Uses a collection of emulators forked with GGPO-based rollback netcode and online matchmaking. This essentially allows for an extremely smooth online experience, and is the standard for modern online fighting games. It also supports replays, which is a huge boon if you're trying to git good at any of these old games. Since the rollback is also handled at the emulator layer rather than on a per-game basis. Most MAME, SNES, and Dreamcast games support rollback through Fightcade, as well.
> [!important]- Auto ROM downloading in Fightcade | [direct download](https://fightcade.download/fc2json.zip) (updated 04.20.23)
> You can have Fightcade automatically download roms by using lofi1048's scripts (updated 04.20.23) and extracting the archive to Fightcade's `Emulator` folder, or `~/.var/app/com.fightcade.Fightcade/data/` if you're using flatpak. Once the files are extracted to the correct folder simply join the desired game's respective channel and it'll download automatically. If you were already in the channel, simply leave and re-join.

> [!info] If you're interested in playing Super Smash Bros. Melee with rollback netcode, check out Slippi [[Emulation, Homebrew#Smash Bros.|here]].
#### [EmuVR](https://www.emuvr.net/) 
Play retro games in emulation using Libretro in a VR environment. [Including light gun games](https://youtu.be/cXqt2J9iJOk)!
	Also has [Simulated CRT televisions and atmospheric lighting](https://youtu.be/025i3r6zjjI), [netplay](https://youtu.be/xZsBaOFi9vM), and even adding videos and music as VHS, DVD, and CD objects, as well as internet TV channels. Just sick in general.
	I've seen people having cartoons running in the background on a TV in one corner while they play Super Nintendo in the other. Really neat.
	Unfortunately, the site and wiki has fallen out of date and they expect you to get the latest downloads from their [Discord](https://www.emuvr.net/discord) 🙄, which is even worse considering they only allow 10 new users into the Discord each day.
#### 🌟 [Red-Viper](https://archive.org/download/ni-n-vb) 
Play Virtual Boy games on 3DS, with any colors and in 3D (as intended).
	Looks great. Virtual Boy Wario Land is trapped on that thing, and that game is worth playing, so yeah.
	Check [[VG Piracy|🦜Videogame Piracy]] for resources on how to download VB games.
	* [VBjin-OVR](https://github.com/braindx/vbjin-ovr) - Play Virtual Boy games in VR
		Re-enables not only the 3D effect, but the VR effect too, since that's what the Virtual Boy was going for.
		That said, I think the VR setup was more of a means to an end than the point, but I'd be remiss not to mention the option. You can change the colors to black and white.
# Homebrew
#### 🌟 [Hacking & Homebrew resources](https://rentry.org/Guides) 
Resources from the homebrew threads on 4chan's /vg/ board.
	Follow any guide here for it's respective console and you wont have any trouble if you have basic reading comprehension. Also provides links to piracy websites in the post-instillation sections.
	- [webcfw](https://webcfw.sdsetup.com/) - Nintendo Switch 1 Payload Loader that works in Chromium browsers. For booting into cfw. Not mentioned above so I thought I'd drop it here.
#### [Pretendo Network](https://pretendo.network/) 
A free replacement to Nintendo's servers for 3DS and WiiU.
	Heavy WIP but extremely promising.
#### [Sudomemo](https://www.sudomemo.net/)
Brings the DSi's Flipnote Hatena service back online, with community-run servers.
	Has support for both DSi and 3DS!
	People are posting great stuff! [Example 1](https://x.com/Sudomemo/status/1619133335892271105), [Example 2](https://x.com/Sudomemo/status/1614080179311366146), [Example 3](https://x.com/parrygripp/status/1591189786555224064)
	* [Sudomemo Archive](https://archive.sudomemo.net) - An archive of virtually every flipnote ever that was on the Flipnote Hetena servers when it shut down.
	* [Kaeru World](https://gallery.kaeru.world) - Ran by a different team. Same idea as Sudomemo, but for Flipnote's sequel, Flipnote 3D. Less active, still cool.
#### [WiiLink](https://wiilink.ca/) 
Brings back support for the Wii's "always on" utility channels, such as forecast, news, Everybody Votes, Check Mii Out, and mail.
	WiiLink merged with RiiConnect24, so this is the successor to that.
	Also has support for more channels, such as ones that were exclusive to Europe and Japan like the food delivery channel.
#### [wiimmfi](https://wiimmfi.de) 
Brings Nintendo Wii and DS game servers back online.
	Mario Kart Wii is still especially popular, especially with CGTP-R, which is listed below.
#### [PSRewired](https://psrewired.com/) 
A revival group that provides third-party online servers for PS2, PSP, and PS3 games.
	Works in emulator for PS2 and in emulator and real hardware for PSP and PS3
#### [Lan-Play.com](http://lan-play.com/) 
Play Nintendo Switch and PS4 games online by using LAN over the internet, for free!
	For switch, you dont even need to hack or install homebrew for any OFW (Official Firmware) games. For games labeled as use with CFW (Custom Firmware) only, you unfortunately must hack your switch to play LAN online, though.
	This is the only viable method I know of for playing pirated Nintendo Switch games online, or playing online with CFW in general.
	Check this before subscribing to some Nintendo paid online service :)