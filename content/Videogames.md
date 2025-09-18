---
title: 🕹️ Videogames
description: Recommendations for emulation, hacking/homebrew, mods, re-implementations, fangames, and more
---
> [!important] [[Piracy#Videogame Piracy|🏴‍☠️Videogame Piracy]] is not on this page, its over here!
# Emulation
#### 🌟 [Emulation General Wiki](https://emulation.gametechwiki.com/)
Extremely useful resource for learning about emulation. Lists all noteworthy emulators for any given console, provides a feature comparison between them, lists where to get resources for each emulator, frontends, FAQ, guides, and more.
> [!tip]- Use this if you dont know what the best emulator is for any given system!
> This information is heavily subject to change over time (the scene moves faster than you'd think), so I dont list it here. Use the wiki!
#### [Retroarch](https://www.retroarch.com/) 
The frontend for libretro. Nice if you want to have all your retro games in one place, navigable with a controller, and especially useful if you're looking to use it's unique features (netplay, [shaders](https://youtu.be/mp0CF2S9N5o), etc). I prefer it to standalone counterparts for most generation 5 consoles and older, though.
Retroarch is also nice for emulating on console. I have retroarch installed on my Switch, for example. fuck the Nintendo Classics shitto rent but never own bullshit
- [Retroarch System Files](https://myrient.erista.me/files/Internet%20Archive/chadmaster/RetroarchSystemFiles/Retroarch-System/), [Archive.org](https://archive.org/details/RetroarchSystemFiles) a drag-n-drop collection of system files (bios) for retroarch
> [!note]- claims of abusive behavior regarding Retroarch's lead developer [\[1\]](https://x.com/BlueMaxima/status/1488826694626525185)
> squerepusher/TwinAphex has a lot of allegations regarding abusive behavior towards other developers in the emulation scene, including potentially contributing to Near's suicide, blackmailing Stenzek, and more. None of this information is compiled in a formal/centralized source, but I'd be remiss not to mention it. Hopefully the scene creates a competitive alternative some day.
>> [!info] Retroarch Alternatives: [Emulation Wiki's Frontends article](https://emulation.gametechwiki.com/index.php/Frontends), [OpenEmu](https://openemu.org/) (Mac), and keep an eye on [Highscore](https://gitlab.gnome.org/World/highscore) (linux, unreleased). These, or ES-DE (below)
#### [**ES-DE**](https://www.es-de.org/) (formerly EmulationStation Desktop Edition)
a frontend for browsing and launching games, retro, steam, standalone, or otherwise. I use it to browse through my library, since i enjoy exploring with es-de more than in Retroarch. I then have it launch the game in retroarch, since i like the way retroarch actually handles running games from an end-user perspective. That said, you could easily configure it to run games in their respective standalone emulators. My favorite theme is [es-de mini](https://github.com/Weestuarty/mini-es-de).
#### 🌟 [Fightcade](https://www.fightcade.com/) 
The definitive way to play virtually every retro fighting game online. Uses a collection of emulators forked with GGPO-based rollback netcode and online matchmaking. This essentially allows for an extremely smooth online experience, and is a more modern standard for online fighting games. It also supports replays, which is a huge boon if you're trying to git good at any of these old games. Since the rollback is also handled at the emulator layer rather than on a per-game basis, most MAME, snes, and dreamcast games support rollback through fightcade, as well.
> [!important]- Auto ROM downloading in Fightcade | [direct download](https://fightcade.download/fc2json.zip) (updated 04.20.23)
> You can have Fightcade automatically download roms by using lofi1048's scripts (updated 04.20.23) and extracting the archive to Fightcade's `Emulator` folder, or `~/.var/app/com.fightcade.Fightcade/data/` if you're using flatpak. Once the files are extracted to the correct folder simply join the desired game's respective channel and it'll download automatically. If you were already in the channel, simply leave and re-join.

> [!info] If you're interested in playing Super Smash Bros. Melee with rollback netcode, check out Slippi under [[Videogames#Smash Bros.]]
#### Switch / 3DS Emulation
Switch: [Ryubing](https://github.com/Ryubing/) [KenjiNX (Android)](https://github.com/Kenji-NX/) 
3DS: [Azahar](https://github.com/azahar-emu/azahar)
[Citra and Yuzu Archives](https://rentry.org/YuzuCitra) 
Tropical Haze (the LLC responsible for Citra and Yuzu) was [sued by nintendo in Feb 2024](https://x.com/citraemu/status/1764747696538046766). As a result, the software isn't able to be distributed officially by Tropical Haze. This is all the resources you need to get the final builds of either emulator running. Contact me or open an issue if any of the links inside of this paste stop working. Note that both emulators were licensed under GPLv3, so the code is still licensed under the GPLv3. Using, forking, or developing either emulator is still 100% above board.
#### Emulator Compatibility Lists. 
Basically, for any given emulator, they'll list all games for the console they're emulating, and how well they're emulated. In the case of the [Dolphin Wiki](https://wiki.dolphin-emu.org/index.php?title=Main_Page) they'll even list optimal emulator settings, enhancements, and more for individual games.
#### [EmuVR](https://www.emuvr.net/) 
Play retro games in emulation using libretro in a VR environment. You can actually play light gun games! [showcase](https://youtu.be/cXqt2J9iJOk)! Just really cool in general. Simulated CRT televisions and atmospheric lighting [showcase](https://youtu.be/025i3r6zjjI), netplay [showcase](https://youtu.be/xZsBaOFi9vM), and even adding videos and music as VHS, DVD, and CD objects, as well as internet tv channels. I've seen people having cartoons running in the background on a tv in one corner while they play super nintendo in the other. It's really neat.
#### [Red-Viper](https://archive.org/download/ni-n-vb) 
Play Virtual Boy games on 3DS. Obviously, this recreates the 3D effect that in my opinion many virtual boy games require. Looks great, and you can change the colors to anything you want. Virtual Boy Wario Land is trapped on that thing, and that game is worth playing, so yeah. You can use the No-Intro link above or Vimm's Lair to download VB games
* [VBjin-OVR](https://github.com/braindx/vbjin-ovr) Play Virtual Boy games in VR, which re-enables not only the 3D effect, but the VR effect too, since that's what the Virtual Boy was going for. That said, i think the VR setup was more of a means to an end than the point, but i'd be remiss not to mention the option. You can change the colors to black and white.
# Homebrew
#### 🌟 [Hacking & Homebrew resources](https://rentry.co/Guides) 
From the homebrew threads on 4chan's /vg/ board. Follow any guide here for it's respective console and you wont have any trouble if you have basic reading comprehension. Also provides links to piracy websites in the post-instillation sections.
#### [webcfw](https://webcfw.sdsetup.com/)
Nintendo Switch Payload Loader that works in chromium browsers. For booting into cfw. Not mentioned above so I thought I'd drop it here.
#### [Pretendo Network](https://pretendo.network/) 
3DS and WiiU homebrew. a free replacement to nintendo's servers. Play games online, etc. Heavy WIP but extremely promising.
#### [riiconnect24](https://rc24.xyz) 
Wii homebrew. Brings back support for utility channels, such as forecast, news, everybody votes, check mii out, and mail
#### [wiimmfi](https://wiimmfi.de) 
Brings nintendo Wii and DS game servers back online. Mario Kart Wii is still especially popular, especially with CGTP-R which is listed below.
#### [Lan-Play.com](http://lan-play.com/) 
Play Nintendo Switch and PS4 games online by using LAN over the internet! No PSN or Nintendo Switch Online required. For switch, you dont even need to hack or install homebrew for any OFW (Official Firmware) games! For games labeled as use with CFW (Custom Firmware) only, you unfortunately must hack your switch to play LAN online, though. This is the only viable method I know of for playing pirated Nintendo Switch games online, or playing online with CFW in general. But yeah, wanna play online with someone specific? check this before subscribing to some nintendo paid online service :3
#### [PSRewired](https://psrewired.com/) 
A revival group that provides third-party online servers for PS2, PSP, and PS3 games. Works in emulator for PS2 and in emulator and real hardware for PSP and PS3
# Mods Enhancements and Re-Implementations
#### [Rompatcher.js](https://www.marcrobledo.com/RomPatcher.js/) 
Some listings here are romhacks and may require you to patch a rom, use this tool to do so. I dont supply the patched rom directly because many of these update over time.
#### [RetroFab](https://itizso.itch.io/retrofab) 
is a collection of simulators available to play in browser of various LCD games (such as the Game & Watch series). Send it to your buddies and show them how they'll never beat your score in Ball or whatever lol :3
## Fan Works
#### 🌟 [Dr. Robotnik's Ring Racers](https://www.kartkrew.org/) 
An amazing kart racer mod for [Sonic Robo Blast 2](https://www.srb2.org/), which is a sonic fangame built using a modified version of Doom (well, [Doom Legacy](https://doomwiki.org/wiki/Doom_Legacy)). It's one of the best kart racers ever made, better than most Mario Kart entries, even. Hundreds of tracks, fanmade characters, etc. Lively community, especially in terms of [modding](https://mb.srb2.org/addons/categories/dr-robotniks-ring-racers-v2-x.23/). [game showcase](https://www.youtube.com/watch?v=qYrXg1IcW1U). DRRR is the sequel to [Sonic Robo Blast 2 Kart (SRB2K)](https://mb.srb2.org/addons/srb2kart.2435/).
#### [Super Mario War (SMWStuff Continuation)](https://github.com/mmatyas/supermariowar) 
A fan-made multiplayer Super Mario Bros. style deathmatch game in which players try to beat one another in a variety of gameplay modes. Super fun party game. Basically, Duck Game before Duck Game, with goomba stomps. If you're not sold [here's a video showcasing the game and talking about it's history](https://www.youtube.com/watch?v=RqS7ad_BFg4)
#### [Power Bomberman](https://www.bombermanboard.com/viewtopic.php?t=1925) 
A feature-rich Bomberman fangame. supports up to 12 players, has over 650 characters, over 70 stages, and an unprecedented level of settings to tweak.
#### [(Rhythm) Heaven Studio](https://archive.org/details/heaven-studio)
[control guide](https://heaven-studio-control-guide.super.site/), [dev curated levels](https://archive.org/details/heaven-studio-devs-picks-level-pack), [levels that shipped with HS](https://archive.org/details/heaven-studio-official-levels), 
A tool to create playable Rhythm Heaven custom remixes. There's a ton of fan-made levels and youtube showcase videos out there, so youtube and the discord's level showcase channel are good places to look.
Unfortunately, the [itch.io page](https://rheavenstudio.itch.io/heaven-studio) does not include any downloads due to a DMCA from nintendo, but the tool is still available from the archive.org link.
If anyone has a collection of official nintendo charts and minigames remade in Heaven Studio, [[Discussion|lmk]].
### Randomizers
#### [The Big List of Video Game Randomizers](https://github.com/video-game-randomizers/rando-list) 
A well maintained list of all videogame randomizers the author knows of. Pretty swell :)
#### 🌟 [Archipelago](https://archipelago.gg/)
A Multiplayer, multi-game randomizer. Supports a bunch of games. Get an item in OoT, could give your friend playing Kingdom Hearts II an item. They get an item? could give it to someone playing Hades with you both. Basically takes all your games and mixes them all up. [Supported games list](https://archipelago.gg/games). There's a number of third-party supported games out there, like [this one](https://github.com/alwaysintreble/Archipelago.BatBoy?tab=readme-ov-file) i found for BatBoy, so keep an eye out. I think they're all documented in the big list but it's kind of hard to control for archipelago support specifically.
### Smash Bros.
#### [Slippi.gg](https://slippi.gg/)
Super Smash Bros. Melee with online matchmaking, rollback netcode, and replays. Check out Fightcade above for other fighting games. [Unpatched ISO](https://archive.org/details/super-smash-bros.-melee-v-1.02.-7z)
I also recommend using [Uncle Punch Training Mode](https://github.com/UnclePunch/Training-Mode/releases) which is for training. Requires the unpatched ISO.
#### [Project+](https://projectplusgame.com/) 
Continuation of Project M, an extremely popular and famous mod of Super Smash Bros. Brawl that makes it play more like melee. Adds Roy, Mewtwo, and Knuckles to the roster. New stages, music, cosmetics. It's a better game. [Trailer](https://youtu.be/z_Hm9FBMz1M), [Unpatched ISO](https://archive.org/details/super-smash-bros.-brawl-ntsc-u-iso)

[Project M EX-Remix](https://forums.kc-mm.com/Gallery/BrawlView.php?Number=217920) Project+ if it was... insane? The character select screen straight up looks like some fan-wiki shit. Adds all characters from 4 and Ult, a bunch of fan characters, stages, music, etc. [great showcase video](https://youtu.be/7tpB55SPhpU). Requires the unpatched ISO.
#### [Smash Remix](https://smash64.online/remix/) 
a very impressive Smash 64 expansion mod. [1.5.0 release trailer](https://www.youtube.com/watch?v=utAxmyfSGbc)
### Pokémon
#### [PokéRogue](https://pokerogue.net/) 
an in-browser roguelite pokemon fangame. Pretty neat!

[Pokémon Emerald Rogue 2](https://www.pokecommunity.com/threads/479406/) a roguelike romhack for Pokémon Emerald. Widely considered to be one of the best romhacks ever made, especially if you like roguelikes.
#### [Pokémon Unbound](https://www.pokecommunity.com/showthread.php?t=382178) 
My favorite pokemon game is a rom-hack. Idk how to feel about it either. It's a "Fire Red romhack", but I'd sooner consider it a campaign made in gen 3's engine. Backported pokemon, mega evolutions, a great campaign. It's awesome. [Unpatched ROM](https://archive.org/details/1636PokemonFireRedUSquirrels)
#### [Poké Transporter GB](https://github.com/GearsProgress/Poke_Transporter_GB) 
a tool to transfer pokemon from gen 1/2 to gen 3 (and therefore all the way up) using official gameboy and gameboy advance hardware. Was made to "feel" official and prevent often immersion breaking methods used by other homebrew software seeking to achieve the same goal. [Showcase](https://www.youtube.com/watch?v=47A6p2hH2gU), [Dev Video](https://www.youtube.com/watch?v=9mSkGhEYBkg)
You can also play Gen 1/2 games on the 3DS Virtual Console to transfer directly to Gen 7 (and therefore up) officially.
### Classic Sonic
#### [Sonic 1 Forever and Sonic 2 Absolute](https://teamforeveronline.wixsite.com/home)
Modified versions of the official 2013 remakes for Sonic 1 and 2. This is possible thanks to the [decompilation](https://github.com/Rubberduckycooly/Sonic-1-2-2013-Decompilation) This is the definitive way to play both games. You'll need either the [Data.rsdk files](https://archive.org/details/s1and2data) or an apk of each game. [Sonic 1 apk](https://info.sonicretro.org/Sonic_the_Hedgehog_(2013_game)), [Sonic 2 apk](https://info.sonicretro.org/Sonic_the_Hedgehog_2_(2013))
#### [Sonic CD 2011 Decompilation](https://github.com/Rubberduckycooly/Sonic-CD-11-Decompilation/releases/latest)
A decompilation of the official 2011 remake. You'll need the [Data.rsdk](https://archive.org/details/data_20230512) file to play. here's a [tutorial](https://gamebanana.com/tuts/14111) if you need help. Either the base decomp or using [Sonic CD Restored](https://gamebanana.com/mods/50089) (a mod for the decomp) is the definitive way to play.
#### 🌟 [Sonic 3 A.I.R.](https://sonic3air.org/)
A fan-made widescreen remaster of Sonic 3 & Knuckles. The definitive way to play. The [S3&K.bin](https://archive.org/details/sonic-knuckles-w-sonic-3) from the steam release is required to play.
### Super Mario 64
#### [romhacking.com](https://romhacking.com/)
Website that hosts romhacks primarily for Super Mario 64. Founded and owned by YouTuber/Twitch Streamer SimpleFlips. They offer a launcher that lets you run n64 hacks from the website. [Unpatched Super Mario 64 ROM](https://archive.org/details/super-mario-64-u_202101)
- [B3313](https://romhacking.com/hack/b3313-super-mario-64-internal-plexus) A beta-based Super Mario 64 hack. Every copy is personalized. Don't spoil yourself. Use the abandoned version.
- [60fps Hack (Optional Widescreen)](https://romhacking.com/hack/60-fps-patch) A hack to get Super Mario 64 to run in 60fps, and optionally widescreen as well. Though I'd sooner recommend the PC port. [Showcase](https://youtu.be/L_pYhVo2mEo)
- [Kaze's Profile](https://romhacking.com/user/Kaze) Kaze is an extremely talented romhacker for SM64. He's the author behind star road, chaos edition, and the afformationed 60fps mod. Sort by most downloaded if you're interested. His [YouTube Channel](https://www.youtube.com/kazeemanuar) has some super interesting showcases, behind the scenes, and more as well.
#### [Super Mario 64 PC Port Info](https://www.sm64pc.info)
a website hosting info on Super Mario 64's [PC Port](https://github.com/sm64-port/sm64-port), which is based on the game's [decomp](https://github.com/n64decomp/sm64). The pc port allows the game to play natively on pc in 60fps and widescreen, rather than in emulator. Lets you use a number of other enhancements as well. [Unpatched Super Mario 64 ROM](https://archive.org/details/super-mario-64-u_202101).
* [Project SGI / Render96](https://github.com/Render96/Render96ex/wiki) A gorgeous mod for the PC Port that makes the game look like the Silicon Graphics Inc. 1996 renders (such as the game's boxart). When following the tutorial use the [latest](https://github.com/msys2/msys2-installer/releases/tag/nightly-x86_64) version of MSYS2 instead of the one they link to directly. Check out this [showcase](https://youtu.be/Lav8wgQP9rc)
### Chris Sawyer games
#### 🌟 [OpenRCT2](https://openrct2.org/)
An open-source re-implementation of Chris Sawyer's Roller Coaster Tycoon 2, however it also allows you to play RCT1 scenerios if you provide a copy of RCT1. Extremely good in countless ways. Requires a copy of the original game. [RCT2 iso](https://archive.org/details/roller-coaster-tycoon-2-triple-thrill-pack), [RCT iso](https://archive.org/details/roller-coaster-tycoon-deluxe).
#### [Roller Coaster Tycoon Classic](https://atari.com/products/rollercoaster-tycoon-classic)
a fine official way to play scenerios from both games on mobile devices. I like the way it orders scenerios :)
#### [OpenTTD](https://www.openttd.org/)
An open-source simulation game based on Chris Sawyer's Transport Tycoon Deluxe. You can provide a copy of the original TTD for original graphics and sound. [TTD iso](https://archive.org/details/msdos_Transport_Tycoon_Deluxe_1995)
### Clonk
#### [OpenClonk](https://www.openclonk.org/)
An open-source continuation of Clonk, a series of PC games that were quite popular in Germany. The classic clonk games are sort of inspired by worms, settlers, and lemmings.
In 2014, RedWolf open-sourced their code and has handed the game over to their community. Many compare the current gameplay to terraria and minecraft, but of course these games weren't around when Clonk started in the 90s. In some ways, like terraria and minecraft, Clonk has sort of become a 2D sandbox engine with a game already in it. [series showcase video](https://www.youtube.com/watch?v=4w6n5ERJraU)
#### [ccan.de](https://ccan.de/)
The community's modding archive repo for the game. The most popular mod at the time of writing was published last month (Feb 2025), so the community is still very active!
#### [Clonk 1-4 + Clonk Planet](http://www.clonk.de/classics.php), [Clonk Rage + Clonk Endeavor](http://www.clonk.de/index.php) 
official downloads for all the commercial games in the Clonk series that were developed by RedWolf. 

### Doom
>[!important]- Official .WADs ("roms") are over [[Piracy#[DOOM .wads](https//myrient.erista.me/files/Internet%20Archive/chadmaster/2020_03_22_DOOM/DOOM%20WADs/|here]]!

>[!note]- For sourceport comparisons, check Dwars' Overview
>[Dwars' Overview on YouTube](https://youtu.be/pILDo05ANDk),
>[Doom + Doom II addendum](https://www.youtube.com/watch?v=8-y8wdGY8ks)
#### 🌟 [Crispy Doom](https://github.com/fabiangreffrath/crispy-doom)
is my preferred sourceport. It's a fork of [Chocolate Doom](https://github.com/chocolate-doom/chocolate-doom). There isn't really a definitive way to play Doom, but this is very good if you want to preserve the original experience with higher resolution, framerate, mouse look, better controls, etc. Do not enable jump or free vertical looking.
* [Roland SC-55 Music Packs](https://sc55.duke4.net/) This site provides music packs meant to emulate the sound of a Roland SC-55. If you're using Crispy Doom, be sure to download the config files for it. The SC-55 was a sound module released in 1991, and is widely considered to provide the best sound for DOS games. I'm not sure why Crispy Doom doesn't replicate it by default. [E1M1 Comparisons](https://www.youtube.com/watch?v=t9IRWOzs0T0) (SC-55 starts at 9:50)
#### [Doom + Doom II](https://isthereanydeal.com/game/doom-and-doom-ii/info/)
((also on [Fitgirl](https://fitgirl-repacks.site/doom-i-ii-2024/)) normally this'd be in [[Piracy]], but i figured i'd keep soureport info here))
id/Bethesda's most recent official sourceport for Doom to modern hardware at the time of writing. Good if you just want to pick up and go. Contains optional [remixed music](https://www.youtube.com/watch?v=WBmD84EExmo), and a new official chapter (as well as sigil and other past expansions).
Even has a mod list to play modded wads from an easy to browse menu, albeit this feature is absent from the switch release and leaves some to be desired (and also isn't compatible with gzdoom exclusive wads).
Regardless, this is by far the best _official_ way to play Doom, and is a significant improvement over the Unity ports. See the [Dwars' overview addendum](https://www.youtube.com/watch?v=8-y8wdGY8ks) for more info
#### [GZDoom](https://zdoom.org/index) 
is a sourceport which is good for virtually every modded doom wad, especially since many wads dont support other sourceports. Change texture filtering to none in the options. [Doomworld 25 Years](https://www.doomworld.com/25years/) is a good place to start to discover modded wads, as is their Cacowards ceremony. My favorite wad is [MyHouse.wad](https://www.doomworld.com/forum/topic/134292-myhousewad/). I also quite like [Treasure Tech](https://forum.zdoom.org/viewtopic.php?t=66995). I have not played many custom wads.
#### [SIGIL, SIGIL II](https://romero.com/sigil) 
Doom's unofficial 5th and 6th episodes, designed by John Romero (a lead designer and programmer on Doom) for Doom's 25th and 29th anniversary respectfully. I recommend you grab the buckethead version from the .wad files link above for episode one, and the mp3 version from [this archive](https://archive.org/details/sigil-ii-shotgun-shell-usb) of the shotgun shell USB for episode two. I'm giving it it's own bullet because it feels like it deserves it's own mention, and also because John made these for GZDoom, albeit Crispy Doom supports them.
#### [Legacy of Rust](https://archive.org/details/doom-legacy-of-rust-2024_202408) 
A two episode expansion for Doom, which came out with Doom + Doom II's release in 2024. Made in collaboration with id Software, Nightdive Studios, and MachineGames. Basically just 16 new maps which also utilize some content formerly left on the cutting room floor.
#### The [Playstation port](https://www.youtube.com/watch?v=mRcFCkXbdGI) 
is also incredibly interesting as it's a very different but cool take on the game. May as well also mention Doom 64 has mouse controls now since it's good, but that's a different game.
#### [Action Button Reviews Doom](https://youtu.be/38zduHkwGcc)
as long as we're here... this is the best video/retrospective/overview of the game to ever exist. S-Tier vid.
## Mods misc
#### [romhacking.net](https://archive.org/details/romhacking.net-20240801)
Basically the website that hosts romhacks, save for romhacking.com and game/franchise dedicated forums (such as for Pokemon). Unfortunately, romhacking.net shut down on August 1st 2024. The link goes to an official archive of the sites content, hosted on Internet Archive. You may be able to use the wayback machine to browse the main site to find new hacks, then download them from the provided archive link.
#### [Sonic Adventure DX Mod Loader](https://sadxmodinstaller.unreliable.network/)
Sonic Adventure DX infamously has [numerous problems](https://www.youtube.com/watch?v=SORYL5J1Heg) compared to the Dreamcast original. The Sonic Adventure Mod Loader comes bundled with a ton of fixes that bring it in line with the dreamcast original, and also provides optional enhancements as well. And of course, allows you to install mods in general. Playing on PC with the mod loader is the definitive way to play Sonic Adventure.
#### [Widescreen Super Mario World](https://github.com/VitorVilela7/wide-snes)
Super Mario World in widescreen. 16:9, ultra-wide, you name it. [Showcase](https://youtu.be/ghAPgz-jV04), [Unpatched ROM](https://archive.org/download/super-mario-world_202204/Super%20Mario%20World%20%28U%29%20%5B%21%5D.zip)
* [Super Nintendo SA-1 Mods](https://github.com/VitorVilela7/wide-snes) The same author makes preformance enhancement mods for various Super Nintendo games. Games like Gradius III are virtually unplayable without it. [Comparison](https://youtu.be/6SDqm7uAJa0)
#### [The Mother 3 Fan Translation](https://mother3.fobby.net/)
The english translation of Mother 3, featuring Tomato of Legends of Localization fame. [Unpatched ROM](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Game%20Boy%20Advance.zip/Mother%203%20%28Japan%29.zip)
#### [TF2 Classic](https://tf2classic.com/)
A free Sourcemod that aims to re-imagine the 2008/2009 era of Team Fortress 2. New features range from weapons and maps to gamemodes such as VIP and Four-Team. If you're sick of vanilla TF2's bots, lack of support from valve, and general shitty state, try this out.
#### [CGTP-R](https://www.chadsoft.co.uk/)
A widely installed mod for Mario Kart Wii with a lively online community via wiimmfi. Adds over 200 new tracks to the game. [2019 Trailer](https://youtu.be/8R7B51s74WA)
#### [Open-Source Game Clones](https://osgameclones.com/)
a well maintained list of a bunch of open-source game clones. Many require a copy of the original game which you can often find on archive, but you can also check the piracy section of this garden ^^. Rollercoaster Tycoon, Jedi Knight Dark Forces II, Super Mario 64, classic sonic, you name it. Be sure to use their tag filters!
#### [OpenJKDF2](https://github.com/shinyquagsire23/OpenJKDF2) (Jedi Knight Dark Forces II)
an open-source re-implementation of JKDF2, removing the hassle of rendering and input compatibility shims, while providing in-all guided installation steps, cross-platform multiplayer, and a host of graphical (and other) improvements. You'll need a copy of the game, which you can find on the internet archive and elsewhere. [link](https://archive.org/details/star-wars-jedi-knight-dark-forces-ii-gog-pc-game)
# Misc.
#### [IsThereAnyDeal](https://isthereanydeal.com)
Key sites like G2A are shady and fuck over developers, but there's a load of second-party official key sellers (ex. Humble Bundle) that don't and still get you a deal on your games. This site is basically a live database for those, so just check it when you're wanting to buy a new game and you may save yourself a few bones. It can also notify you when a game goes on sale anywhere.
#### [My Life In Gaming](https://www.youtube.com/@mylifeingaming)
A youtube channel dedicated to retro games. I mention them specifically for their RGB series, which extensively details ways to get the best possible picture out of your retro consoles. There are broad episodes, episodes focused on specific consoles, and episodes focused on specific equipment
#### [TheBackloggery](https://www.backloggery.com/)
Sort of like MAL for videogames. You can detail what games you own, how you own them, and if you've played, beaten, completed, or mastered them.
#### [SteamGridDB](https://www.steamgriddb.com/)
Database of cover assets for Steam, since a lot of games are missing covers and the like. Includes non-steam games as well, in case you put those in your steam library.
* [SGDBoop](https://www.steamgriddb.com/boop) tool that automatically applies assets from SteamGridDB directly to your Steam library with a click of a button, removing the need to download and set them manually.
* [Millennium](https://github.com/SteamClientHomebrew/Millennium) a theme/plugin mod for the Steam client, which allows you to once again theme steam to your liking.
* [Adwaita for Steam](https://github.com/tkashkin/Adwaita-for-Steam) A skin to make Steam look more like a native GNOME app, for the GNOME heads.
* [Steam Rom Manager](https://github.com/SteamGridDB/steam-rom-manager) Useful for bulk adding non-steam games (such as retro games) to your steam library with image assets pulled from SteamGridDB
#### [Sudomemo](https://www.sudomemo.net/)
Brings the DSi's flipnote hatena service back online with community-run servers, has support for both DSi and 3DS! People are posting great stuff! [Example 1](https://x.com/Sudomemo/status/1619133335892271105), [Example 2](https://x.com/Sudomemo/status/1614080179311366146), [Example 3](https://x.com/parrygripp/status/1591189786555224064)
* [Sudomemo Archive](https://archive.sudomemo.net) An archive of virtually every flipnote ever that was on the flipnote hetena servers when it shut down.
* [Kaeru World](https://gallery.kaeru.world) is ran by a different team. Same idea as sudomemo, but for Flipnote's sequel Flipnote 3D. Less active, still cool.
#### [Death Generator](http://deathgenerator.com/)
Also known as Sierra Text Generator. Lets you create custom text boxes in the style of a ton of different games.
#### [NoClip](https://noclip.website/)
Lets you look around 3D environments in browser for a ton of games you absolutely played growing up as if you were using noclip in source.
#### [Earthbound Battle Backgrounds](https://www.gjtorikian.com/Earthbound-Battle-Backgrounds-JS/) 
Generator for moving earthbound backgrounds.
#### [Super Lesbian Animal RPG](https://slarpg.com/) 
SLARPG doesn't really belong here but fuck you it's my list. Everyone must play this. An RPGMaker game by Ponnet (aka Bobby), the author of [Thanks Ken Penders](https://www.tumblr.com/thankskenpenders). With [music](https://beatrixquinn.bandcamp.com/album/super-lesbian-animal-rpg-ost) by Beatrix Quinn. Give it a shot if you like "quirky earthbound inspired RPGs" or gay people. Fuck elden ring, it's my GOTY 2022. Be sure to read the (short) [official prologue comic](https://slarpg.com/comic) before you start.  If you read this far, there's sort of an easter egg if you try to go to melody's real tumblr page featured her in-game laptop :3
>[!warning]- Do not use joy2key or 1.5x/2x window size
>For playing the game with a controller, use steam input with community uploaded profiles (or make your own). If you don't own the game on steam, add it as a non-steam game and use steam input anyways. 
>Dont play on 1.5x or 2x window size unless you really need to fill the screen, it stretches the pixels
>(blame RPGMaker for both of these limitations).
