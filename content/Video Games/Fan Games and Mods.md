---
title: 👾 Fan Games and Mods
description: Fan game and mod resources recommendations
tags:
  - videogame
---
>[!tip] [[Minecraft]] and [[Doom]] have their own articles.

>[!info]- Some of these entries require [Rompatcher.js](https://www.marcrobledo.com/RomPatcher.js/) 
Romhacks may require you to patch a rom, use this tool to do so.
# General
#### [Open-Source Game Clones](https://osgameclones.com/)
A well maintained list of a bunch of open-source game clones.
	Many require a copy of the original game which you can often find on Archive.org, but you can also check [[VG Piracy|🦜Video Game Piracy]].
	Rollercoaster Tycoon, Jedi Knight Dark Forces II, Super Mario 64, classic Sonic, and more. Be sure to use their tag filters!
#### [Romhacking.net](https://www.romhacking.net/) 
Website that's the home for many kinds of modhacks.
	That said, there's also often game/franchise dedicated forums, such as for Pokemon and SM64.
	Romhacking.net was shut down awhile ago, but it looks like they're back up again. I've left the archive link just in case.
	- [archive](https://archive.org/details/romhacking.net-20240801)
#### [Super Nintendo SA-1 Mods](https://github.com/VitorVilela7/SA1-Root)
Performance enhancement mods for various Super Nintendo games, utilizing the SA-1 chip.
	Supports Contra III, F-Zero, Gradius III, Race Drivin', and Super R-Type.
	Maintains hardware compatibility, and keeps most games intact. The SA-1 is a co-processor used shipped in the cartridge of some SNES games. These mods activate the co-processor and modifies game engine code to utilize the chip's features. Games like Gradius III are virtually unplayable without it.
	- [Gradius 3 original vs SA-1 Comparison](https://youtu.be/6SDqm7uAJa0)
	- [**Project FastROM**](https://github.com/VitorVilela7/fastrom)
		Optimizes SNES games designed to run under SlowRom to FastRom
		Takes games from 2.68 MHz to 3.58 MHz, allowing the SNES CPU to read data from the rom about 33% faster. Though practically performance boosts range from 10-33%.
		Supports Super Castlevania IV, Axelay, F-Zero, and U.N. Squadron. Can be combined with SA-1 in F-Zero's case.
### Nintendo 64 Decomps, Recomps, and Ports
>[!warning] Heavy WIP - Needs work before publishing
#### [Decomps vs Recomp vs Ports explained](https://www.youtube.com/watch?v=lpOEhtoc3DY)
A video explaining what the differences between decompilations, recompilations, and ports.
I am not intimately familiar with the technicalities of this sort of thing, so note to take anything I say with a grain of salt. I may be wrong.
tl;dr: Decomps just convert compiled machine code back into whatever language the code was originally written in. In the case of n64 games, this is usually C.
A port takes that code and compiles it to be executed as a native program on new target hardware, rather than, say, the n64. Often new graphics backends need to be written, however.
A Recomp re-integrates reverse engineering steps of a decomp and the porting work into a single workflow. Basically lets you decompile n64 games then recompile them for new target hardware yourself.
#### 🌟 [Super Mario 64 PC Port](https://www.sm64pc.info)
Super Mario 64 ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29/Super%20Mario%2064%20%28USA%29.zip), [Archive.org](https://archive.org/details/super-mario-64-u_202101)
Website hosting info on Super Mario 64's [PC Port](https://github.com/sm64-port/sm64-port), which is based on the game's [decomp](https://github.com/n64decomp/sm64).
The PC port allows the game to play natively on PC in 60fps and widescreen. Lets you use a number of other enhancements as well.
* [Project SGI by Render96](https://github.com/Render96/Render96ex/wiki), [showcase](https://youtu.be/Lav8wgQP9rc) - PC Port mod that makes the game look like the Silicon Graphics Inc. 1996 renders.
	Gorgeous, though I'm not sure it'll ever be finished.
	When following the tutorial to compile the project yourself, you may have to use the [latest](https://github.com/msys2/msys2-installer/releases/tag/nightly-x86_64) version of MSYS2 instead of the one they link to directly.
#### [SpaghettiKart](https://github.com/HarbourMasters/SpaghettiKart) (Mario Kart 64)
Mario Kart 64 ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29/Mario%20Kart%2064%20%28USA%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29.zip/Mario%20Kart%2064%20%28USA%29.zip)
A PC port of MK64 built from a decompilation. high res, high framerate, widescreen, and more!
Based on Ship of Harkinian, so its highly customizable and modular.
Soon enough [Mario Kart 64 HD](https://evilgames.eu/texture-packs/mk64-reloaded.htm) will run on Spaghetti. When it releases, I recommend it! especially if you're playing at higher resolutions where the original graphics will struggle to look good. Its a texture pack for Mario Kart 64 with remade pre-renders for the game's graphics. Makes all the racers look a lot more high-fidelity, while retaining the game's original art style. If you really want to play MK64HD without waiting for it to release in SpaghettiKart, you can play it in the [MK64Recomp](https://github.com/sonicdcer/MarioKart64Recomp/releases/latest).
[SpaghettiKart showcase](https://www.youtube.com/watch?v=awcFpg_BG38), [MK64HD trailer](https://www.youtube.com/watch?v=YMXtvliz7sg), [MK64HD showcase](https://www.youtube.com/watch?v=lsGb4YOFnBY).
#### [Zelda64Recomp](https://github.com/Zelda64Recomp/Zelda64Recomp) (Zelda: Majora's Mask)
MM ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29/Legend%20of%20Zelda%2C%20The%20-%20Majora%27s%20Mask%20%28USA%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29.zip/Legend%20of%20Zelda%2C%20The%20-%20Majora%27s%20Mask%20%28USA%29.zip)
OoT ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29/Legend%20of%20Zelda%2C%20The%20-%20Ocarina%20of%20Time%20%28USA%29%20%28Rev%202%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29.zip/Legend%20of%20Zelda%2C%20The%20-%20Ocarina%20of%20Time%20%28USA%29%20%28Rev%202%29.zip)
Static recomp of MM, runs at high-res with high fps, [mod support](https://thunderstore.io/c/zelda-64-recompiled/), gyro, analogue camera, low input latency, and more! Natively on Win/Mac/Linux.
Super clean. Looks especially impressive with some fan projects that help the game's graphics match the fidelity of HD resolutions like [MMN64HD](https://thunderstore.io/c/zelda-64-recompiled/p/Nerrel/MMN64HD/) (an [extremely impressive](https://www.youtube.com/watch?v=ovknYMdIP9I) texture pack for MM by Nerrel), or the [upcoming "N64 style" raytracing](https://youtu.be/GIp7C2ro2T8?t=111). Even [Archipelago support](https://thunderstore.io/c/zelda-64-recompiled/p/RecompRando/MMRecompRando/)! OoT is planned for a future update.
[Recomp trailer](https://www.youtube.com/watch?v=yUmdQ5qA5b0), [Digital Foundary technical showcase](https://www.youtube.com/watch?v=O1wlTOvn2y0), [Nerrel feature showcase](https://www.youtube.com/watch?v=ywWwUuWRgsM),
[Nerrel general N64 recomp mod showcases](https://www.youtube.com/watch?v=NtSDwwZqJ5A)
- [Ship of Harkinian](https://www.shipofharkinian.com/) / [2ship2harkinian](https://github.com/HarbourMasters/2ship2harkinian) - If you're familiar with these games and are more into tinkering than playing, Harkinian gives extreme, granular control over settings. Ship is for OoT (which the recomp has yet to do at time of writing), and 2h2h is Majora's. Its very impressive! Though I think the Recomp is better for just casually playing.
#### [Goemon64Recomp](https://github.com/klorfmorf/Goemon64Recomp) (Mystical Ninja Starring Goemon)

#### [Perfect Dark Port](https://github.com/fgsfdsfgs/perfect_dark)
Work-in-progress port of the [Perfect Dark decomp](https://github.com/n64decomp/perfect_dark) to modern platforms.
Singleplayer and split-screen multiplayer are fully working, though there are minor graphics and gameplay related issues and some crashes.
The game includes mouselook, dual analogue controller support, configurable fov, widescreen, 60fps, and more.
#### [Starship: Centauri Alfa](https://github.com/HarbourMasters/Starship) (Star Fox 64)
Star Fox 64 Decomp based on Ship of Harkinian. High res, high framerate, and more!
	Read more about SpaghittiKart or Ship of Harkinian under Zelda64Recomp above. They're all essentially the same idea as this.
	- Star Fox 64 ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29/Star%20Fox%2064%20%28USA%29%20%28Rev%201%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29.zip/Star%20Fox%2064%20%28USA%29%20%28Rev%201%29.zip)
#### N64 Decomp
A series of projects decompiling various N64 Games.
- [Mario Kart 64](https://github.com/n64decomp/mk64)
- [Banjo-Kazooie](https://github.com/n64decomp/banjo-kazooie)
- [Goldeneye 007](https://github.com/n64decomp/007)
- [Perfect Dark](https://github.com/n64decomp/perfect_dark)
- [Super Mario 64](https://github.com/n64decomp/sm64)
- [Ocarina of Time](https://github.com/n64decomp/oot)
- [Majora's Mask](https://github.com/n64decomp/majora)
### Randomizers
####  [The Big List of Video Game Randomizers](https://github.com/video-game-randomizers/rando-list) 
A well maintained list of all video game randomizers the author knows of. Pretty swell :)
####  🌟 [Archipelago](https://archipelago.gg/)
A Multiplayer, multi-game randomizer.
	Get an item in OoT and its actually a Kingdom Hearts II item, sent to your friend playing that game (and vice versa).
	Supports a bunch of games.
	Basically takes all your games and mixes them all up. [Supported games list](https://archipelago.gg/games).
	There's a number of third-party supported games out there, like [this one](https://github.com/alwaysintreble/Archipelago.BatBoy?tab=readme-ov-file) I found for BatBoy, so keep an eye out. I think they're all documented in the big list but it's kind of hard to control for Archipelago support specifically.
# Franchises
## Metroid
#### [PrimeHack](https://github.com/shiiion/dolphin) (Metroid Prime trilogy)
Fork of Dolphin to give the Metroid Prime trilogy mouselook controls.
	Also improves controller support.
	- [wiki](https://github.com/shiiion/dolphin/wiki)
	- Metroid Prime Trilogy ISO: [Myrient](https://myrient.erista.me/files/Redump/Nintendo%20-%20Wii%20-%20NKit%20RVZ%20%5Bzstd-19-128k%5D/Metroid%20Prime%20Trilogy%20%28USA%29.zip), [Archive.org](https://archive.org/download/Wii_ISO/Metroid%20Prime%20Trilogy%20%28USA%29.iso)
#### [AM2R Launcher](https://github.com/AM2R-Community-Developers/AM2RLauncher) (Metroid II: Return of Samus)
Another Metroid 2 Remake, critically acclaimed fan game that isn't as dead as you think.
	While Nintendo did DMCA the original developer for the game, the community has since picked up where they left off, adding widescreen, among other planned features like NG+, a randomizer, bug fixes, and Linux support.
	A full scale graphical overhaul among other features are [planned](https://www.reddit.com/r/AM2R/comments/1nj0pg9/am2r_community_updates_news_roundup_september_2025/) for the 2.0 update.
#### [X-Fusion](http://metaquarium.wordpress.com/xfusion) (Super Metroid / Metroid Fusion)
Total conversion of Super Metroid that acts as a re-imagining of Metroid Fusion.
	Spent ~10 years in development. Maybe one of the most anticipated romhacks ever made, especially in the Metroid community. Probably one of the most ambitious too.
	The difficulty on its initial patch has left it in a controversial state, but updates have seemingly remediated people's issues, and difficulty options are available. This said, "Even easy mode is far from a cakewalk by Super Metroid standards".
	This is not a port of or replacement for Fusion, but a sort of hybrid remix.
	I highly recommend the showcase video if you want to learn more.
	- [Metroid Construction](https://metroidconstruction.com/hack.php?hack_id=837)
	- Super Metroid ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Super%20Nintendo%20Entertainment%20System/Super%20Metroid%20%28Japan%2C%20USA%29%20%28En%2CJa%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Super%20Nintendo%20Entertainment%20System.zip/Super%20Metroid%20%28Japan%2C%20USA%29%20%28En%2CJa%29.zip)
	- [showcase](https://www.youtube.com/watch?v=luaDpYGDNhk)
#### [Metroid Construction](https://metroidconstruction.com/index.php)
The central hub for all things Metroid hacking. Including 1-4, Zero-Mission, and Prime 1-3.
	They have a huge library of hacks, resources for hacking, a forum, contests, you get the idea.
## Pokémon
### Useful Websites
#### 🌟 [PokéCommunity](https://www.pokecommunity.com/)
Pokemon community forum, especially popular among romhackers.
	There's a lot of weird mirror sites hosting pokemon romhacks. I tend to avoid these if I can help it, as they tend to be pretty sketchy. (Excluding HackDex and PokeROM Codex)
#### 🌟 [HackDex](https://www.hackdex.app/)
Catalog of Pokemon romhacks, with a built-in patcher.
	You can point the website to local copies of the vanilla Pokemon ROMs and it'll remember where they are in the cache, allowing you to one click auto patch romhacks on the fly. Super cool. (Though the site's catalog is very limited at the time of writing. I anticipate the site to fill out as it just went live, though.)
#### [PokéROM Codex](https://pokeromcodex.notion.site/8f188f1761b9430f9adb68833c44e5b8?v=bb31503a729442f798b4233509dacab8)
Catalog of Pokémon romhacks, fangames, and resources.
	This helps a lot with discoverability and the like. Doesn't host roms directly, just keeps track of and links to them. Uses extensive (and subjective) tagging. I just wish there was a way to sort by ratings/downloads.
#### [Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Main_Page)
A Pokémon wiki. Part of [Bulbagarden](https://bulbagarden.net/home/).
	This is my personal preference as far as Pokémon wikis go, this is seemingly the opinion of many others, as well.
#### [PokéCollector](https://www.pokellector.com/sets)
TCG site that hosts images for all English cards from Base to current, sorted by set.
#### [TCGPlayer](https://www.tcgplayer.com/search/pokemon/product)
Look up the market price for any TCG card or sealed package (Pokémon or otherwise).
### Enhancement+ Hacks
#### [Pokémon Renegade Platinum](https://projectpokemon.org/home/forums/topic/52294-pok%C3%A9mon-renegade-platinum/)
Enhancement hack for Platinum.
	Provides access to all 493 pokemon, revamped trainers and bosses, lots of optional changes, removal of trade-only evolutions, fairy types, and a number of QoL changes. All pokemon have been buffed, many more moves can be learned by level up, and the levels they learn moves are reasonable, etc. etc.
	Basically, its just a really quality, engaging way to play Platinum as an adult. I had a lot of fun with it in a way I often struggle to do with vanilla Pokémon.
	Some people consider this a "difficulty hack", but I believe this is the result of people slapping the label on, as its obstinately the case and is a common type of hack. However, I feel Renegade Platinum's appeal is much better conveyed by calling it an enhancement, as its not overly challenging and provides a lot more than simply making the game harder. The boss battles are fun and fair.\
	- Pokémon Platinum ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%20DS%20%28Decrypted%29/Pokemon%20-%20Platinum%20Version%20%28USA%29%20%28Rev%201%29.zip), [Archive.org](https://archive.org/download/retro-roms-best-set/Nintendo%20-%20DS.zip/Pokemon%20-%20Platinum%20Version%20%28USA%29%20%28Rev%201%29.zip)
#### [Pokémon Pinball: Generations](https://rainbowdevs.com/title/pinball/)
A Pokémon Pinball (gbc) enhancement+expansion! 
	Play in 60fps, obtain 251 pokemon, and play on the original red/blue boards in addition to the new gold/silver boards. So simple, but so nice.
	Fun fact, this hack is always playing in the corner of [TwitchPlaysPokemon](https://www.twitch.tv/twitchplayspokemon), spamming random inputs.
	- Pokémon Pinball ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Game%20Boy%20Color/Pokemon%20Pinball%20%28USA%2C%20Australia%29%20%28Rumble%20Version%29%20%28SGB%20Enhanced%29%20%28GB%20Compatible%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Game%20Boy%20Color.zip/Pokemon%20Pinball%20%28USA%2C%20Australia%29%20%28Rumble%20Version%29%20%28SGB%20Enhanced%29%20%28GB%20Compatible%29.zip)
#### [Pokémon Fool's Gold](https://foolsgold.miraheze.org/wiki/Main_Page)
Jhoto, remixed. A neat way to (re)play Gold/Silver/Crystal.
	All 251 Pokémon in the game have been remixed with a clever change or twist, sporting new designs, types, movesets, and dex entries. Its nice to be able to play and be vaguely familiar yet not at all familiar with the mons you'll run into. The lead dev highly encourages players play completely blind.
	The region it's self is also remixed, with new areas, quests, and an expanded post-game. QoL and enhancements are also present (such as the physical/special split).
	Its slightly more difficult than the vanilla games, but not by much in my opinion. The original game honestly wasn't very well balanced so Fool's Gold addresses this.
	I am intentionally underselling Fool's Gold for the sake of surprise.
	- [PokéCommunity](https://www.pokecommunity.com/threads/pok%C3%A9mon-fools-gold-a-hack-of-crystal-where-everything-is-familiar-yet-different.433723/)
	- Pokemon Crystal ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Game%20Boy%20Color/Pokemon%20-%20Crystal%20Version%20%28USA%2C%20Europe%29%20%28Rev%201%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Game%20Boy%20Color.zip/Pokemon%20-%20Crystal%20Version%20%28USA%2C%20Europe%29%20%28Rev%201%29.zip)
	- [trailer](https://www.youtube.com/watch?v=4UBiwAW_Ut8), [showcase](https://www.youtube.com/watch?v=U3_Eg3WbEow)
	- 
### Fangames and Original Hacks
#### 🌟 [Pokémon Showdown](https://pokemonshowdown.com/)
Web-based Pokémon battle simulator.
	Free [open-source](https://github.com/smogon/pokemon-showdown) website that lets you battle others online and which is utilized heavily by the competitive Pokémon battling community, particularly [Smogon](https://www.smogon.com/forums/forums/pok%C3%A9mon-showdown.209/), where the official forums for Showdown are hosted.
#### [PokéRogue](https://pokerogue.net/) 
Roguelike Pokémon browser fangame.
	Runs take about 2 hours, and quick save options are available.
	Features mobile support (great mobile game as a PWA), cloud saves, all pokemon from gen 1-9, a ton of items, meta progression, megas, gigantamax, and terastallization.
	The game is nothing but back to back pokemon battles, so no overworld or exploration or anything like that here.
	The original creator was a [bit of a weirdo](https://dotesports.com/pokemon/news/all-pokemon-starters-by-generation) but has since [stepped down](https://x.com/FlashfyreDev/status/1791283340017840387), so take that for what you will.
	- [PokéCommunity](https://www.pokecommunity.com/threads/pok%C3%A9rogue-web-based-pok%C3%A9mon-roguelite.527282/)
	- [showcase](https://www.youtube.com/watch?v=Bz2gyQ0EQPk)
#### [Pokémon Emerald Rogue 2](https://www.pokecommunity.com/threads/479406/)
Roguelike romhack for Pokémon Emerald.
	Runs take about 3-4 hours, but quick save options are available.
	Includes a hub area with meta progression, character customization, and a good amount of QoL features.
	The game is split into two versions: Expanded (recommended), and Vanilla. In expanded, the game contains modern improvements like new battle items, abilities, fairy type pokemon, a physical/special split, and more. Vanilla is just standard Emerald mechanics with few changes.
	- Pokémon Emerald ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Game%20Boy%20Advance/Pokemon%20-%20Emerald%20Version%20%28USA%2C%20Europe%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Game%20Boy%20Advance.zip/Pokemon%20-%20Emerald%20Version%20%28USA%2C%20Europe%29.zip)
	- [trailer](https://www.youtube.com/watch?v=08CNykGBd8U), [showcase](https://www.youtube.com/watch?v=GtqQZHXp-QU)
#### 🌟 [Pokémon Unbound](https://www.pokecommunity.com/showthread.php?t=382178) 
Widely considered the greatest Pokémon romhack.
	A new campaign made in gen 3's engine. Backported Pokémon, mega evolutions, a great campaign. It's quite the party pleaser.
	This is a more traditional Pokémon adventure than Odyssey, so if you just want some damn good traditional Pokémon, go with this.
	The story is a little "edgy", and a lot of romhack players consider it generic, but I think its pretty fun.
	- [Pokémon Fire Red ROM](https://archive.org/details/1636PokemonFireRedUSquirrels)
	- [showcase](https://youtu.be/WrdtqB807AM?t=4)
#### [Pokémon Odyssey](https://www.pokecommunity.com/threads/pokemon-odyssey-complete-v4-1-1.488536/)
Crossover fangame featuring Etrain Odyssey and Made in Abyss.
	Though the author says you don't need to be familiar with either of those to play.
	This hack is incredibly critically acclaimed within the Pokémon romhack scene. There's a focus on story and exploration, as well. ~100 new regional variants, double battles only, sidequests, original mechanics, QoL features, [an original soundtrack](https://youtube.com/playlist?list=PLiYbx6rE4CV55dp-ThUanIDgJmtHtrSeV), and more.
	A bit different of a Pokemon experience, so try it if you want something a little different. Its story is also considered by many to be pretty good!
	- [Pokémon Fire Red ROM](https://archive.org/details/1636PokemonFireRedUSquirrels)
	- [trailer](https://www.youtube.com/watch?v=KwbuJHdVx70)
#### [Poké Transporter GB](https://github.com/GearsProgress/Poke_Transporter_GB) 
Tool to transfer Pokémon from gen 1/2 to gen 3 (and thus up) using official hardware.
	Was made to "feel" official and prevent often immersion breaking methods used by other homebrew software seeking to achieve the same goal. 
	You can also play Gen 1/2 games on the 3DS Virtual Console to transfer directly to Gen 7 (and therefore up) officially.
	[Showcase](https://www.youtube.com/watch?v=47A6p2hH2gU), [Dev Video](https://www.youtube.com/watch?v=9mSkGhEYBkg)
## Smash Bros.
#### 🌟 [Slippi.gg](https://slippi.gg/)
Super Smash Bros. Melee with online matchmaking, rollback netcode, and replays.
	I also recommend using [Uncle Punch Training Mode](https://github.com/UnclePunch/Training-Mode/releases) which is for training. Requires the unpatched ISO.
	- Melee ISO: [Myrient](https://myrient.erista.me/files/Redump/Nintendo%20-%20GameCube%20-%20NKit%20RVZ%20%5Bzstd-19-128k%5D/Super%20Smash%20Bros.%20Melee%20%28USA%29%20%28En%2CJa%29%20%28Rev%202%29.zip), [Archive.org](https://archive.org/details/super-smash-bros.-melee-v-1.02.-7z)
#### [Project+](https://projectplusgame.com/) 
Continuation of Project M, the famous mod for Brawl that makes it play like Melee.
	P+ adds Roy, Mewtwo, and Knuckles to the Brawl roster. New stages, music, cosmetics. It's a better game.
	- Brawl ISO: [Myrient](https://myrient.erista.me/files/Redump/Nintendo%20-%20Wii%20-%20NKit%20RVZ%20%5Bzstd-19-128k%5D/Super%20Smash%20Bros.%20Brawl%20%28USA%2C%20Canada%29%20%28Rev%202%29.zip), [Archive.org](https://archive.org/details/super-smash-bros.-brawl-ntsc-u-iso)
	- [trailer](https://youtu.be/z_Hm9FBMz1M)
	- [**Project M EX-Remix**](https://forums.kc-mm.com/Gallery/BrawlView.php?Number=217920)
		Project+ if it was... insane? The character select screen straight up looks like some fan-wiki shit. Adds all characters from 4 and Ult, a bunch of fan characters, stages, music, etc. Requires the unpatched ISO. [showcase video](https://youtu.be/7tpB55SPhpU).
#### 🌟 [Smash Remix](https://smash64.online/remix/) 
A very impressive Smash 64 expansion mod that adds new fighters, stages, game modes, and more. Featuring the game's original announcer!
	- Smash N64 ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29/Super%20Smash%20Bros.%20%28USA%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29.zip/Super%20Smash%20Bros.%20%28USA%29.zip)
	- [2.0.0 release trailer](https://www.youtube.com/watch?v=q-iLvy0w8hs)
#### [Akaneia Build](https://github.com/akaneia/akaneia-build)
Mod for Melee that adds new fighters, stages, trophies, game modes, and more. Similar to Smash Remix.
	- Melee ISO: [Myrient](https://myrient.erista.me/files/Redump/Nintendo%20-%20GameCube%20-%20NKit%20RVZ%20%5Bzstd-19-128k%5D/Super%20Smash%20Bros.%20Melee%20%28USA%29%20%28En%2CJa%29%20%28Rev%202%29.zip), [Archive.org](https://archive.org/details/super-smash-bros.-melee-v-1.02.-7z)
	- [trailer](https://www.youtube.com/watch?v=gcKGV23ZbHs)
## Sonic the Hedgehog
### 2D Sonic
#### [Sonic 1 Forever and Sonic 2 Absolute](https://teamforeveronline.wixsite.com/home)
Improvement mods for Sonic 1/2 (2013). Fixes, restorations, and more!
	Widescreen support, Tails, Knuckles, and Amy in both games, optional drop dash, and a bunch of other nifty features. Oh, and mod support for [both](https://gamebanana.com/games/10601) [games](https://gamebanana.com/games/15019).
	This is all possible thanks to the [decompilation](https://github.com/Rubberduckycooly/Sonic-1-2-2013-Decompilation).
	This is the definitive way to play both games, imo.
	You'll need either the Data.rsdk files or an .apk of each game's mobile release.
	- Sonic 1 data.rsdk: [Archive.org](https://archive.org/download/proper-sonic-origins/proper-sonic-origins/Sonic_2013_RSDKv4.zip/data.rsdk)
	- Sonic 2 data.rsdk: [Archive.org](https://archive.org/download/proper-sonic-origins/proper-sonic-origins/Sonic2_2013_RSDKv4.zip/data.rsdk)
	- [**Sonic Forever: Epilogue Expansion**](https://gamebanana.com/mods/479364)
		Mod for Sonic Forever that adds Mighty and Ray, and overhauls Knuckles, Amy, and Super Sonic to be more in-line with Sonic 1's art style. If you're going to play these characters that were never in the game anyways, you may as well use this to improve things somewhat. Sonic has also been slightly tweaked. Highly configurable.
	- **Sonic 3D Classics Collection**:
		Also, if you have a 3DS, the Sonic 1 port in the Sega 3D Classics Collection is competent and incredibly novel. As is the whole collection to be honest. The 3D on the 3DS was really under-rated, especially on new 3DS models where the effect was significantly improved. The mobile ports are still better, however.
#### [Sonic CD: Miracle Edition](https://gamebanana.com/mods/467930)
Improvement mod for Sonic CD (2011). Fixes, restorations, and more!
	Has some bonus content, like the (optional) ability for characters to turn "miracle" when all the time stones have been collected, optional drop dash, Knuckles and Amy (when you provide the Sonic Origins data .rsdk), and more and more. Not to mention the numerous fixes and restorations. The whole thing is also highly customizable.
	The whole thing is a bit complicated to install unfortunately, especially if you want to use the content added in Origins (Knuckles, Amy, Drop Dash). Read the mod page for details on how to install. Else, using the [decompilation](https://github.com/RSDKModding/RSDKv3-Decompilation) with just the 2011 .rsdk is still acceptable, and there are [fan](https://gamebanana.com/mods/464373) [made](https://gamebanana.com/wips/53126) [mods](https://gamebanana.com/mods/50072) that unofficially implement these features and [more](https://gamebanana.com/mods/454683). Though afaik none of these are compatible with Miracle if you want its feature-set.
	Regardless of what version you use, I recommend you make sure that you **use the original spindash** and not the Sonic 2 style like the 2011 remake defaults to. It causes a lot of gameplay issues and is inauthentic anyways.
	For the decomp, you can also build for [Switch](https://github.com/heyjoeway/Sonic-CD-11-Decompilation) and [3DS](https://github.com/SaturnSH2x2/Sonic-CD-11-3DS). (Though I doubt Miracle Edition works on those platforms).
	- Sonic CD 2011 .rsdk: [Archive.org](https://archive.org/download/data_20230512/Data.rsdk)
	- Sonic Origins Plus' Sonic CD .rsdk: [Archive.org](https://archive.org/download/origins-plus-rsdk/Origins%20Plus%20RSDK.zip/Origins%20Plus%20RSDK%2FSonicCDu.rsdk)
	- [**Sonic CD: The Unsung Masterpiece**](https://www.youtube.com/watch?v=ORJryigA0Ck)
		 A whopping 8 hour video analysis by someone whom deeply loves Sonic CD. Combs though the game in meticulous, deeply personal detail. The Sonic analysis of all time. Will make you appreciate this game, like it or not.
		Contains two intermissions, chapter breaks, and is also made so that you can just sort of watch whatever chapters catch your eye. Maybe think of it more as "A bunch of Sonic CD analysis that totals to 8 hours of runtime".
#### 🌟 [Sonic 3 A.I.R.](https://sonic3air.org/)
A fan-made widescreen remaster of Sonic 3 & Knuckles. The definitive way to play, imo.
	Also adds [modding support](https://gamebanana.com/games/6878), achievements, a ton of unlockables (including the drop dash), highly customizable settings, and much more.
	If you want an Amy mod to compete with Origins Plus, I recommend [Amy Galore](https://gamebanana.com/mods/500302), which is an Amy mod with a lot of options.
	The S3&K.bin from the Steam release is required to play.
	- Sonic 3 & Knuckles bin: [archive.org](https://archive.org/download/proper-sonic-origins/proper-sonic-origins/Sonic3AIR.zip/savedata%2FSonic_Knuckles_wSonic3.bin)
	- **Sonic 3 Complete**:
		- [Sonic 3 Complete](https://www.s3complete.org/) - If you're stuck playing on real hardware or emulator for whatever reason, I highly recommend S3 Complete. Though the devs consider AIR to be the project's de-facto successor. [showcase](https://www.youtube.com/watch?v=Pux2TNnKuw4)
		- [Sonic 3 Unlocked](https://s3unlocked.blogspot.com/) - A series of articles on the internal workings of Sonic 3, written by S3 Complete's co-creator.
#### [Sonic Mania Decompilation](https://github.com/RSDKModding/Sonic-Mania-Decompilation)
Run Sonic Mania natively on a ton of systems, including exclusive mods.
	This isn't necessary to play Sonic Mania and doesn't particularly add any improvements out of the box, but it does allow people to inject more complicated mods and easily port the game (such as to Linux, MacOS, Android, [Vita](https://github.com/SonicMastr/Sonic-Mania-Vita), [Wii](https://github.com/Mefiresu/RSDKv5-Decompilation/tree/dev/wii-port), [WiiU](https://github.com/Clownacy/Sonic-Mania-Decompilation-Wii-U), [3DS](https://github.com/SaturnSH2x2/RSDKv5-Decompilation/tree/3ds-main), [Miyoo Mini](https://github.com/emtee40/Miyoo-Mini-Ports-Collection), and even some under heavy WIP like [Dreamcast](https://x.com/SonicFreak94)). There's also a [general optimization fork](https://github.com/smb123w64gb/RSDKv5-Decompilation).
	- [Sonic Mania Plus Data.rsdk](https://archive.org/download/data.rsdk/Data%20Mania%20Plus.rsdk) (rename to `Data.rsdk`)
	- **Mod Showcase**:
		None of these require the decomp, for the record. Though some mods out there do.
		- 🌟 [Amy Mania](https://gamebanana.com/wips/50006) - An amazing mod for Sonic Mania that adds Amy to the game. My favorite implementation of Amy ever. Sonic 1 Forever and 2 Absolute's Amy are based on this release. Worth a dedicated playthrough, second only to Sonic. She replaces Mighty.
		- [Blazey Mix](https://gamebanana.com/mods/244284) - Another good character mod I like. Adds Blaze, though she replaces Sonic. She has an upward thrust and can summon a fire shield for 20 rings 
		- [One more Shadow mod 2.0](https://gamebanana.com/wips/63400) - a Shadow character mod based on Hortinus and Megamix Mania. Shadow gets a homing attack/thok ontop of Sonic's drop dash. Adds a bunch of cheesy music and sfx that feel out of place, but this is the Shadow mod that a lot of people seem to praise for what I assume has to be a good reason. Also has support for [ModernSonicBoost](https://gamebanana.com/tools/6595) which adds a boost meter. Shadow replaces Ray.
#### Controls Unchained 
Control enhancements for [Sonic Forever](https://gamebanana.com/mods/475211), [2 Absolute](https://gamebanana.com/mods/476856), [3 AIR](https://gamebanana.com/mods/470596), and [Mania](https://gamebanana.com/mods/469550).
	Slightly unbalanced but so fun. Everyone gets super peel-out, air recurl, and can activate air abilities after a roll off (drop dash, etc). Tails always gets flight cancel, Knuckles can always glide drop spin dash. So nice.
	In Mania, Sonic gets insta-shield, Tails gets flight cancel, Knuckles can glide drop spin dash like in Sonic 3, and Mighty can hammer drop twice.
	CU is actually built into Miracle edition, but it also supports [Sonic CD](https://gamebanana.com/mods/474192) without it.
	CU supports Epilogue Expansion (mentioned under Absolute above), however CU must be placed at the highest priority.
#### [Sonic Origins Ultrafix](https://gamebanana.com/mods/452036)
Sonic Origins is a bad port... improve it somewhat.
	I still wouldn't recommend playing Origins over the above (or even the genesis originals in some cases) if you can ever help it (for reasons far too many to detail here), but if you're stuck with Origins, give this a spin.
#### [Sonic Megamix Mania](https://gamebanana.com/mods/560558)
Fan game remake+remix of [Sonic Megamix](https://www.headcannon.com/TeamMegamix/index.php?p=mm_home), given the Mania treatment. 5+ years in the making.
	Hugely impressive. Though I'm personally waiting for 1.0 to release.
	20 acts, new moves for existing characters, Amy, and Shadow!
	This is a mod for Sonic Mania Plus, so you'll need that to play.
	I'll likely have more to say when I play it. I'm incredibly excited. The team regularly posts updates on their [Twitter](https://x.com/MegamixMania) and [Bluesky](https://bsky.app/profile/megamixmania.bsky.social).
	1.0 will be the complete mod, but after the game's release 2.0 will support the decomp, with additions that the decomp will allow for.
	Currently v0.9 at the time of writing.
	- [SHC 2023 trailer](https://www.youtube.com/watch?v=vY0y033-Gic)
	For context:
		Sonic Megamix is a Sonic 1 ROM Hack created by [Simon "Stealth" Thomley](https://segaretro.org/Simon_Thomley) and his team. The project went dormant in 2008. Christian "Taxman" Whitehead and Stealth would go on to produce the official Retro engine remakes for Sonic 1 and 2 (which the above entries are all based upon), before developing Sonic Mania together.
		Needless to say, Megamix was a very critically acclaimed ROM hack (especially for the time). Megamix Mania looks to improve on it across the board. Albeit, Stealth is not working on it, though [he did play the 2019 demo](https://www.youtube.com/watch?v=-_IzR6i5-D0) and liked it!
#### [Sonic Triple Trouble 16-Bit](https://stt16bit.wixsite.com/sonictripletrouble16)
Great fan remake of Triple Trouble that asks what it'd have been like if it was on Genesis.
	In story mode you can play as either Sonic & Tails or Knuckles. Fang, Amy, and Metal Sonic are all unlockable characters, too. Sonic has his spin dash, and Amy has 3 movesets to choose from. You actually get to hotswap between Sonic and Tails during their playthrough.
	The game also includes content from the Genesis games (like elemental shields), new enemies, mechanics, and layouts.
	As a note, TT16-Bit is actually a game maker game, not a ROM hack. But you probably wouldn't know that just by looking, as the game's lead designer (Noah Copeland) went out of his way to stick to the limitations of the Genesis.
	The game is available for Windows (and thus Linux), Mac, and Android.
- [trailer](https://www.youtube.com/watch?v=R4eeo2nGw4c)
#### [Sonic and the Fallen Star](https://stardropsmh.github.io/sonic-and-the-fallen-star/)
Pretty and original 2D Sonic fangame!
	Its light on features but is still mostly quality. There's a lot of artistic touch, fully animated cutscenes, good music, and more. Sonic has the drop dash, super peel-out, and an extremely powerful spin-dash. Tails is also playable.
	This is a very speedy 2D Sonic game, the level design really encourages speed in a way few other 2D Sonic games do, which has its pros and cons. Its slightly automated, but well paced. The level design is still done well, and there's still exploration to be done.
	This is the fangame with the unique looking elemental shields. The electric shield is triangular and gives you a downward forward dash, and the fire shield gives you a sort of double jump. The bubble shield works like it does in Sonic 3, and is shaped like a square. Super sonic feels powerful, and there's some spoiler-stuff i shouldn't tell you about too :)
- [trailer](https://youtu.be/oAsY4VEsmMk)
### 3D Sonic and Spin-offs
#### 🌟 [Sonic Adventure DX Mod Loader](https://sadxmodinstaller.unreliable.network/) (fixes and restorations)
Restore Sonic Adventure to its Dreamcast quality on PC with modern enhancements, and optionally load mods.
	Sonic Adventure DX infamously has [numerous problems](https://www.youtube.com/watch?v=SORYL5J1Heg) compared to the Dreamcast original. The Sonic Adventure Mod Loader comes bundled with a ton of fixes that bring it in line with the Dreamcast original, and also provides optional enhancements as well.
	Playing on PC with the mod loader is the definitive way to play Sonic Adventure.
	There's also [Lutris install scripts](https://lutris.net/games/sonic-adventure-dx/) if you want to run this on Linux, but they require the original PC release, rather than the steam release.
	- Sonic Adventure DX (PC) ISO: [Archive.org](https://archive.org/download/sonic-adventure-dx-directors-cut_202212/Sonic%20Adventure%20DX%20Director%27s%20Cut.rar)
#### 🌟 [Dr. Robotnik's Ring Racers](https://www.kartkrew.org/) 
Fangame. The best kart racer ever made.
	Built ontop of Sonic Robo Blast 2. Hundreds of tracks, fanmade characters, and more. Lively community, especially in terms of [modding](https://mb.srb2.org/addons/categories/dr-robotniks-ring-racers-v2-x.23/).
	DRRR is the sequel to [Sonic Robo Blast 2 Kart (SRB2K)](https://mb.srb2.org/addons/srb2kart.2435/).
	- [game showcase](https://www.youtube.com/watch?v=qYrXg1IcW1U).
#### [Sonic Robo Blast 2](https://www.srb2.org/)
Sonic fangame built atop [Doom Legacy](https://doomwiki.org/wiki/Doom_Legacy). Classic sonic design, in 3D.
	Surprisingly good! Also has a huge, lively [modding community](https://mb.srb2.org/addons/categories/srb2-v2-2-x.1/).
	- [2.2 trailer](https://www.youtube.com/watch?v=Ia097A0pKNM)
#### [Project 06'](https://www.youtube.com/watch?v=aHFWn8nSgjw)
Fangame that remakes the gameplay segments of Sonic the Hedgehog (2006) in the Unity engine.
	Less buggy, more enhancements, Cooler. A lot of people swear by this. Doesn't adapt the story mode, unfortunately. ChaosX has said they're working on a big update at the time of writing, but has previously said he considers the project "finished", and has stated he won't be adding story mode.
	Main link is a showcase video and what people treat as the homepage. The project doesn't really have a central website or page, for some reason.
	- Patch v1.45: [Google Drive 1](https://drive.google.com/file/d/1kJhwQu7Xo10HTpXLbsgkKtAa1S5gaFn2/view), [Google Drive 2](https://drive.google.com/file/d/1W1k7cHALGSbPsySLFlYass73aCMdkwCq/view), [MediaFire](https://www.mediafire.com/file/p2rnpp0exedbha1/Project_06_-_Silver_Release_%2528Patch_v1.45%2529.zip/file)
#### [Extreme Gear Labs](https://www.exgearlabs.org) (Sonic Riders + SR: Zero Gravity)
Developer homepage for Sonic Riders DX and Sonic Riders Regravitified
	SRDX is an enhancement mod that adds mechanics, balances stages and type shortcuts, revamps gear designs, and adds new characters, cosmetics, and super forms, etc. All while attempting to stay true to the original's gameplay ethos.
	In the same vein, SR: Regravitified is an enhancement mod for ZG that overhauls mechanics to speed the game up and reintroduces mechanics from the first game. Regravitified is a WIP at the time of writing. 
	Both games support Netplay.
	This is the same team responsible for whatever good you can find in Tournament Edition. The entire team unanimously split from SRTE after the release of 1.3 due to harassment and abuse from the project's supposed director. SRDX is built on top of SRTE 1.3.
	- Sonic Riders ISO: [Myrient](https://myrient.erista.me/files/Redump/Nintendo%20-%20GameCube%20-%20NKit%20RVZ%20%5Bzstd-19-128k%5D/Sonic%20Riders%20%28USA%29%20%28En%2CJa%2CFr%2CDe%2CEs%2CIt%29.zip), [Archive.org](https://archive.org/download/GC_US_Arquivista/Sonic%20Riders%20%28US%29.iso)
	- Zero Gravity ISO: [Myrient](https://myrient.erista.me/files/Redump/Nintendo%20-%20Wii%20-%20NKit%20RVZ%20%5Bzstd-19-128k%5D/Sonic%20Riders%20-%20Zero%20Gravity%20%28USA%29%20%28En%2CJa%2CFr%2CDe%2CEs%2CIt%29.zip), [Archive.org](https://archive.org/download/Wii_ISO/Sonic%20Riders%20-%20Zero%20Gravity%20%28USA%29%20%28En%2CJa%2CFr%2CDe%2CEs%2CIt%29.iso)
	- [SR:DX trailer](https://www.youtube.com/watch?v=7wKfpnHQhtM), [Regravitified trailer](https://www.youtube.com/watch?v=QLn9tbnMpO8)
#### [Sonic the Fighters: Community Edition](https://gamebanana.com/mods/581347#H1_0)
The mod that the STF community widely uses, especially in competitive play.
	You can easily install this in [RPCS3](https://rpcs3.net/) using [HoneyPatcher](https://github.com/coatlessali/HoneyPatcher?tab=readme-ov-file). You'll mostly be able to netplay with people from the STF community Discord. Though you can also play singleplayer or with your friends.
	They also offer an alternative [STF: Tournament Edition](https://gamebanana.com/mods/630433) which is closer to the vanilla game, but removes port-priority and the underdog mechanic "ketchup".
	- STF PS3 pkg/rap: [Myrient](https://myrient.erista.me/files/No-Intro/Sony%20-%20PlayStation%203%20(PSN)%20(Content)/Sonic%20The%20Fighters%20%28USA%29.zip) 
#### [Sonic 3D Blast: Director's Cut](https://ttjontt.wixsite.com/gamehut/sonic-3d-blast-dx)
An "update" to Sonic 3D Blast, created by the game's lead programmer.
	Includes a ton of feature additions like a stage select screen, time attack mode, super sonic, a password-based save system, debug mode, gameplay tweaks, new controls, and more.
	I'm not sure how I feel about the new controls. I know sonic is supposed to be fast, but I personally find DX a bit unweildy, though I haven't heard many others complain about it. 
	Calling the mod a director's cut is a bit of a misnomer, as the game was actually directed by Takao Miyoshi. Jon Burton is the game's lead programmer and creator of this mod, so the mod's name and reputation isn't _totally_ unwarranted.
	I've included pre-patched ROM links since it's in no-intro's database for some reason.
	- [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=1241378226)
	- Sonic 3D Blast ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Sega%20-%20Mega%20Drive%20-%20Genesis/Sonic%203D%20Blast%20%28USA%2C%20Europe%2C%20Korea%29%20%28En%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Sega%20-%20Mega%20Drive%20-%20Genesis.zip/Sonic%203D%20Blast%20%28USA%2C%20Europe%2C%20Korea%29%20%28En%29.zip)
	- Sonic 3D Blast DX pre-patched ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Sega%20-%20Mega%20Drive%20-%20Genesis/Sonic%203D%20Blast%20%28USA%2C%20Europe%2C%20Korea%29%20%28En%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Sega%20-%20Mega%20Drive%20-%20Genesis.zip/Sonic%203D%20Blast%20-%20Director%27s%20Cut%20%28World%29%20%28Unl%29.zip)
	- [trailer](https://www.youtube.com/watch?v=TO-N2WHbnqU), [development playlist](https://www.youtube.com/playlist?list=PLi29TNPrdbwKbLF55py8J7DH_D3AigOCX)
#### [Sonic R Updater](https://gamebanana.com/tools/6325)
Tool that lets the 1998 PC port of Sonic R run on modern systems, with fixes and enhancements.
	Sonic R is an odd game... but as an oddity, its pretty neat!
	This is the definitive way to play. Also comes with the mod manager, which will let you run the game at native resolution, and which also comes bundled with some fixes and restorations. Oh, and [modding support](https://gamebanana.com/games/6165), of course.
	Consider getting a mod that makes the ring SFX more gentle, its pretty brutal in this version. There's [a](https://gamebanana.com/sounds/39571) [couple](https://gamebanana.com/sounds/39581) [options](https://gamebanana.com/sounds/43560).
	- Sonic R (PC) ISO: [Archive.org](https://archive.org/download/sonicr_202212/SONICR.ISO)
#### 🌟 [Sonic Unleashed Recompiled](https://github.com/hedge-dev/UnleashedRecomp)
The unofficial PC port of the Xbox360 version of Sonic Unleashed.
	Pretty self-explanatory. They decompiled the game so now you can play it on Desktop in 4k60fps at better performance than the original had, plus [mod](https://gamebanana.com/mods/games/21975) it.
	- Sonic Unleashed Xbox360 files: [Archive.org](https://archive.org/details/unleashed-recomp-windows-complete-installation), [Archive.org (direct download)](https://archive.org/download/unleashed-recomp-windows-complete-installation/Sonic%20Unleashed%20%28X360%20iso%2C%20update%20and%20DLCs%29.zip)
## Super Mario
#### [romhacking.com](https://romhacking.com/)
Website that hosts romhacks, primarily for Super Mario 64.
	Founded and owned by [YouTuber](https://www.youtube.com/@SimpleFlips)/[Twitch Streamer](https://www.twitch.tv/SimpleFlips) SimpleFlips.
	They offer a launcher that lets you run n64 hacks from the website.
	- Super Mario 64 ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29/Super%20Mario%2064%20%28USA%29.zip), [Archive.org](https://archive.org/details/super-mario-64-u_202101)
#### [Kaze's Profile](https://romhacking.com/user/Kaze) 
Extremely talented romhacker for SM64. Author behind Star Road, Chaos Edition, and more.
	Sort by most downloaded if you're interested.
	His [YouTube Channel](https://www.youtube.com/kazeemanuar) has some super interesting showcases, behind the scenes, and more as well.
	- Super Mario 64 ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29/Super%20Mario%2064%20%28USA%29.zip), [Archive.org](https://archive.org/details/super-mario-64-u_202101)
#### 🌟 [B3313 (Internal Plexus)](https://romhacking.com/hack/b3313-super-mario-64-internal-plexus)
Beta-based Super Mario 64 hack. A cryptic, labyrinthine sprawl of a video game that plays like an elaborate dream.
	Maybe the biggest SM64 hack ever made. Don't spoil yourself. Though if you absolutely must, [Gabri Lovecraft's B3313 video](https://www.youtube.com/watch?v=-QjeCe7zV54) is good. Maybe stop around the 15 minute mark.
	Use the abandoned version.
	- Super Mario 64 ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29/Super%20Mario%2064%20%28USA%29.zip), [Archive.org](https://archive.org/details/super-mario-64-u_202101)
#### [sm64coopdx](https://sm64coopdx.com/)
Super Mario 64 Co-Op DX adds multiplayer to the PC port of SM64
	Not actually that, its just "sm64coopdx", but y'know.
	Also adds a LUA api similar to Roblox and Garry's Mod, so there's a lot of fan stuff made for this release due to the ease of scripting new content.
	- [Mods for sm64coopdx](https://mods.sm64coopdx.com/mods/)
	- [Discord](https://discord.gg/TJVKHS4)
	- Super Mario 64 ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%2064%20%28BigEndian%29/Super%20Mario%2064%20%28USA%29.zip), [Archive.org](https://archive.org/details/super-mario-64-u_202101)
#### 🌟 [Super Mario Bros. Remastered](https://baldgordon.itch.io/smbr)
Ground up remake of the original NES game and its derivatives, in widescreen.
	Plus new levels, custom modes, new characters, resource packs, and a full level editor, improved physics, visuals, audio, and more. Also completely open source :)
	- [GitHub](https://github.com/JHDev2006/Super-Mario-Bros.-Remastered-Public)
	- Super Mario Bros. ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Nintendo%20Entertainment%20System%20%28Headered%29/Super%20Mario%20Bros.%20%28World%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Nintendo%20Entertainment%20System%20%28Headered%29.zip/Super%20Mario%20Bros.%20%28World%29.zip)
	- [trailer](https://www.youtube.com/watch?v=P8WqSn4JUIQ)
#### [Widescreen Super Mario World](https://github.com/VitorVilela7/wide-snes)
Hack of Super Mario World that runs in widescreen. 16:9, ultra-wide, etc.
	- Super Mario World ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Super%20Nintendo%20Entertainment%20System/Super%20Mario%20World%20%28USA%29.zip), [Archive.org](https://archive.org/download/super-mario-world_202204/Super%20Mario%20World%20%28U%29%20%5B%21%5D.zip)
	- [showcase](https://youtu.be/ghAPgz-jV04)
#### [CGTP-R](https://www.chadsoft.co.uk/)
A widely installed mod for Mario Kart Wii with a lively online community via wiimmfi.
	Adds over 200 new tracks to the game. 
	- [2019 trailer](https://youtu.be/8R7B51s74WA)
#### [Mushroom Kingdom Fusion](https://fusion-fangaming.itch.io/mushroom-kingdom-fusion)
Huge Mario crossover fangame featuring 21 playable characters and over 200 levels.
	9 worlds, 80+ bosses. One of the most elaborate crossover games I've ever seen.
	The trailer explains more than i ever could.
	- [trailer](https://youtu.be/j-NxajOfFfw?si=dE2VOhtyWpYPszof)
#### [Super Mario War (SMWStuff Continuation)](https://github.com/mmatyas/supermariowar) 
A fan-made multiplayer Super Mario Bros. style deathmatch game
	Players try to beat one another in a variety of gameplay modes. Super fun party game. Basically, Duck Game before Duck Game, with goomba stomps.
	- [showcase](https://www.youtube.com/watch?v=RqS7ad_BFg4).

## Plants vs. Zombies
#### [PvZ Wiki](https://plantsvszombies.wiki.gg/)
Non-fandom wiki for PvZ
	Affiliated with the [PvZ: Fusion](https://pvzfusion.wiki.gg/) and [Neighborhood Defense](https://pvzneighborhooddefense.wiki.gg/) fangame wikis, as well as the [PvZ Discord](https://discord.com/invite/FBasnrE).
#### PvZ 2: Reflourished
Experience PvZ 2 mostly vanilla, without the mobile garbage and bloat
	Reflourished removes the ads, micro-transactions, plant leveling, and more that plague the official PvZ 2 release from EA. Aims to be a continuation of the game's pre-2017 release and design. Targeted at casual players. Only has an apk release.
	Play this if you want to play PvZ 2 as it was officially designed by PopCap to be played.
	Reflourished also adds unofficial post-game content that's extremely well received by the community if you're into that as well.
	They don't have a home page, for some reason. So I've opted to link the Fandom installation guide, mirrored to a BreezeWiki instance.
	- Downloads: [Google Drive](https://drive.google.com/drive/folders/1y5lVZh-flKWxpeXSFYJprzJlL4Jlcfm4), [Mega](https://mega.nz/folder/yHxTTbhY#zWMzwNxQZrBw38ZqM32wJQ)
	- [Fandom](https://reflourished.fandom.com/wiki/Installation_Guide) installation guide
	- [Discord](https://discord.com/invite/ba9rC7QdKb), [Twitter](https://x.com/PvZReflourished), [Bluesky](https://bsky.app/profile/pvzreflourished.bsky.social), [Fandom Wiki](https://reflourished.fandom.com/)
#### PvZ 2: Alternate UniverZ
"What if" PvZ 2 mod which reimagines the game with the original's mechanical spirit.
	AlterverZ introduces the original's progression and re-establishing 25 sun gameplay, on top of adding new plants, zombies, and gimmicks. Targeted at casual players.
	PvZ fans widely consider this to be their favorite way to play PvZ, so play this if you want to play a fan-interpreted version of PvZ 2 that plays similar to the original.
	Obviously also removes all the mobile garbage like Reflourished does.
	- Downloads: [Google Drive](https://drive.google.com/drive/folders/1ckXFy-1cv7Ka0eCxOXMweHWb_atzOc1z?usp=sharing), [Media Fire](https://www.mediafire.com/folder/gx085wj9rfp44/Plants_vs._Zombies_2_-_Alternate_UniverZ)
	- [YouTube](https://youtu.be/0j7yVEzycf0) installation guide
	- [Discord](https://discord.gg/ee5dUt5), [Twitter](https://x.com/PvZAltverZ), [Bluesky](https://bsky.app/profile/pvzaltverz.bsky.social), [YouTube](https://www.youtube.com/@posstwo), [Wiki.gg](https://altverz.wiki.gg/)
#### [PvZ 2: Gardenless](https://pvzge.com/en/)
PvZ 2 remade for PC
	For Linux it has you running a docker instance to host the web version, but i was unable to get the web version working properly myself. I've heard good things about Gardenless otherwise, though i'm not sure if its finished.
	I'd personally recommend running Reflourished in an Android emulator, but Gardenless is well received for the people who have gotten it working so I'd be remiss not to mention it.
	- [Discord](https://discord.gg/ZEfb2tBQFW), [GitHub](https://github.com/Gzh0821/pvzge_web)
#### [PvZ: DLC Edition](https://gamejolt.com/games/pvzdlceditionmod/1009738)
Adds post-game and bonus content to PvZ1
	Doesn't change the base game and leaves off right where the base game leaves off, continuing into roof night levels and going from there. Adds new plants, zombies, gimmicks, minigames, and more. Also adds the versus mode from the xbox 360 release which is very nice to see.
#### PvZ: Fusion
That fangame you see in YouTube videos and TikToks that have plants fusing together.
	This is the one contribution from the Chinese PvZ community I'll be highlighting, since its well renowned by the Chinese community and fleshed out.
	Lets you combine every plant in the game with every other plant in the game, with a total of over 400 fusions. Maximalist.
	Has a habit of just spamming zombies for its level design difficulty solution, particularly zombies which require player reaction. Its different.
	Not to be confused with [Hybrid](https://github.com/Amir-Ali-Rasooli/Pvz-hybrid-english-3.9.9), which is a mod with a similar idea. I don't know which came first or which is better, but afaik Fusion is more popular.
	- English Translation: [GitHub (PC/Android)](https://github.com/Teyliu/PVZF-Translation/issues/37), [Linux (Lutris)](https://github.com/Teyliu/PVZF-Translation/issues/37). Mac guide in their Discord.
	- [Discord](https://discord.gg/pvzfusion), [Wiki.gg](https://pvzfusion.wiki.gg/)
#### [I RULE!](https://doctorhummer.itch.io/irule)
Roguelike tower defense Binding of Isaac fangame, utilizing PvZ gameplay.
	It's a very clever adaptation of PvZ's gameplay to a roguelike that recontextualizes Isaac's iconography to the TD format. A very neat and fun experience.
	The dev is currently in active development of a total remake which i'm very excited for, which will come in the form of an update and add a good chunk of content, as well as 2 player local co-op.
	- [Showcase](https://www.youtube.com/watch?v=v10tm46pv5A)
#### [The Ultimate PvZ Retrospective](https://www.youtube.com/watch?v=OsInBzjxAIU)
YouTube video by Foekoe in which he completes every official English game release.
	This video is what inspired this section and what made me want to get back into PvZ after playing it years ago. His PvZ 2 section in particular really made me want to play the game but without the mobile garbage baggage it comes with, and it turned out that existed! So I've been having fun with the franchise as a result and figured I'd put what I learned here. I'll probably also try GW2 again here soon since apparently it's still popping.
	As for the video, there aren't many people that can make their videos as fun and entertaining as Foekoe can in editing. If not for Foekoe I'd probably say this sort of png tuber half-hearted comedy style doesn't work, but Foekoe's so snappy and fun that I can't help but enjoy myself watching his game showcases and retrospectives.
#### Notes:
Notes I have about PvZ and this section
	Some PvZ games that you wouldn't think are alive very much are. Garden Warfare 2 had an all time player peak in Dec 2025 (the game is in a similar position as TF2 imo), people still play PvZ Heroes (which is apparently good), and the versus modes in the Xbox 360 and Replanted releases are still relevant.
	There's a LOT of content exclusive to official Chinese releases in and outside of the games, and a lot of Chinese fan content as a result as well. I am not familiar at all with this side of the community, but to be honest I'm not the most interested (despite the numerous English translations).
	The PvZ community is extremely fractured and decentralized. There's dozens of wikis, Discords, Discords for those wikis, mod pages, lack of mod pages, and more. To add insult to injury, its also largely fractured between languages, and the Chinese side of the community seems to be even bigger than the English side. This makes finding information in regards to the fan community really difficult. There's often little to no curation and often you have to be "in the know". So apologies in advance if the information here isn't the best. 
## Other Franchises
#### 🌟 [OpenRCT2](https://openrct2.org/) (RollerCoaster Tycoon)
An open-source re-implementation of Chris Sawyer's Roller Coaster Tycoon games.
	Extremely good in countless ways. Requires a copy of RCT2, and a copy of RCT is optional if you want to play the first game's objectives.
	- [RCT2 iso](https://archive.org/details/roller-coaster-tycoon-2-triple-thrill-pack), [RCT iso](https://archive.org/details/roller-coaster-tycoon-deluxe).
	- Other ways to play:
		- [Roller Coaster Tycoon Classic](https://atari.com/products/rollercoaster-tycoon-classic) - A fine official way to play scenarios from both games on mobile devices. I like the way it orders scenarios :)
#### [OpenTTD](https://www.openttd.org/) (Transport Tycoon)
An open-source simulation game based on Chris Sawyer's Transport Tycoon Deluxe.
	You can optionally provide a copy of the original TTD for original graphics and sound.
	- [TTD iso](https://archive.org/details/msdos_Transport_Tycoon_Deluxe_1995)
#### [OpenGOAL](https://opengoal.dev/) (Jak and Daxter, Jak II)
Port of the first two Jak and Daxter games to PC, with enhancements.
	Better performance, QoL features, mod support, and more. Incredibly impressive.
	Jak and Daxter were created using a custom language developed by NaughtyDog called GOAL, so this turns compiled GOAL machine code into somewhat human-readable GOAL code which can be recompiled to run on PC, etc.
	Jak 3 is also planned in the future.
	- Jak and Daxter ISO: [Myrient](https://myrient.erista.me/files/Redump/Sony%20-%20PlayStation%202/Jak%20and%20Daxter%20-%20The%20Precursor%20Legacy%20%28USA%29%20%28En%2CFr%2CDe%2CEs%2CIt%29%20%28Rev%201%29.zip), [Archive.org](https://archive.org/download/RedumpSonyPS2NTSCU/Jak%20and%20Daxter%20-%20The%20Precursor%20Legacy%20%28USA%29%20%28En%2CFr%2CDe%2CEs%2CIt%29%20%28Rev%201%29.7z)
	- Jak II ISO: [Myrient](https://myrient.erista.me/files/Redump/Sony%20-%20PlayStation%202/Jak%20II%20%28USA%29%20%28En%2CJa%2CFr%2CDe%2CEs%2CIt%2CKo%29%20%28v2.01%29.zip), [Archive.org](https://archive.org/download/RedumpSonyPS2NTSCU/Jak%20II%20%28USA%29%20%28En%2CJa%2CFr%2CDe%2CEs%2CIt%2CKo%29%20%28v2.01%29.7z)
	- [showcase](https://www.youtube.com/watch?v=oMU1Z17Fvf4)
#### 🌟 [Apotris](https://akouzoukos.com/apotris) (Tetris)
Tetris engine that's a Game Boy Advance homebrew project, somehow.
	Extremely customizable and ultra-responsive. This is my go to way to play Tetris.
	- [play in browser](https://akouzoukos.com/apotris/play/)
#### [YARG](https://yarg.in/) (Guitar Hero / Rock Band)
Rhythm game which can use the full band of plastic instrument controllers.
	YARG (Yet Another Rhythm Game) is very similar to [Clone Hero](https://clonehero.net/), but unlike Clone Hero, YARG is [open source](https://github.com/YARC-Official/YARG) and supports vocals, pro-keys, and more, in addition to the 5-fret guitar, drums, and riffmaster that Clone Hero supports.
	YARG has a number of [official setlists](https://wiki.yarg.in/wiki/List_of_setlists) you can download using the game's launcher. You can also add sets from [a number of sources](https://opensource.yarg.in/), such as the Rock Band/Guitar Hero games by providing their data. You can also use Clone Hero charts, so anything charted for it works in YARG. Chorus Encore below seems to be the primary site.
	Unlike Clone Hero, inputs are not tied to the game's frame rate, and the game has customizable hit windows (so you can make the game more strict or forgiving depending on your preference). YARG is also more faithful to the GH/RB games by penalizing strumming off note during HOPOs, but some people prefer the way CH does it where the game doesn't penalize you at all. I'm a casual so this doesn't effect me much either way.
	YARG is under pretty heavy development and updates regularly, unlike Clone Hero which updates pretty rarely. I think YARG is overall the better engine. Both are free so see which you prefer if you get deep in.
	YARG runs natively on Windows and Linux. 
	- [Chorus Encore](https://www.enchor.us/) (song search) / [Bridge](https://github.com/Geomitron/Bridge) (Chorus desktop client)
	- [r/CloneHero's chart spreadsheet](https://docs.google.com/spreadsheets/d/13B823ukxdVMocowo1s5XnT3tzciOfruhUVePENKc01o/edit?gid=1870223413#gid=1870223413)
	- [showcase](https://www.youtube.com/watch?v=Q_y0R21zyVA)
#### 🌟 [TF2 Classified](https://tf2classified.com/) (Team Fortress 2)
Free Sourcemod that aims to build off the foundations from early TF2.
	Formerly known as TF2 Classic. New features range from weapons and maps to gamemodes such as VIP and Four-Team.
	If you're sick of vanilla TF2's bots, lack of support from Valve, and general shitty state, try this out.
	- [Steam listing](https://store.steampowered.com/app/3545060/Team_Fortress_2_Classic/)
#### [Open Fortress](https://openfortress.fun/) (Team Fortress 2)
Free Sourcemod for TF2, sort of an original arena shooter built atop TF2's foundation.
	The game only has one class, and that is more fun than you would think.
	It's primary gamemode is a free-for-all deathmatch inspired by Quake, but there's also other gamemodes balanced around the new class like CTF, mercenary domination, team deathmatch, and infection. Oh, and all cosmetics are unlocked from the start.
	Isn't actually open source like the name implies.
	- [Steam listing](https://store.steampowered.com/app/3561320/Open_Fortress/)
#### [Saphi](https://5ever.crashteamranking.com/) (Crash Team Racing)
CTR custom track time trials.
	Adds 20 custom tracks at the time of writing, with hundreds of players and thousands of submissions. Lets you race ghosts, see leaderboards, achieve ranks on each track (set by saphi devs, like S Ranks, etc.), track your PB history, and so on.
	- [Showcase](https://www.youtube.com/watch?v=znqVHwsCTRk)
	- I believe tracks are pulled from [CTRCustomTracks.com](https://ctrcustomtracks.com/)
	- CTR ISO: [Myrient](https://myrient.erista.me/files/Redump/Sony%20-%20PlayStation/CTR%20-%20Crash%20Team%20Racing%20%28USA%29.zip) / PSX Bios: [Myrient](https://myrient.erista.me/files/Redump/Sony%20-%20PlayStation%20-%20BIOS%20Images%20%28DoM%20Version%29/ps-41a.zip)
#### 🌟 [Mega Man 8-Bit Deathmatch](https://mm8bdm.net/home)
A total conversion* of Doom that turns it into a deathmatch arena shooter.
	Its primary gimmick is that each weapon is an ability adapted from Mega Man, and there's a ton of them. Great map design too. One of the most fun multiplayer fps games I've played, and certainly one of the most fun Mega Man games out there.
	- [gameplay showcase](https://www.youtube.com/watch?v=Dige6njiehY)
#### 🌟 [Power Bomberman](https://www.bombermanboard.com/viewtopic.php?t=1925) 
A feature-rich Bomberman fangame. supports up to 12 players, has over 650 characters, over 70 stages, and an unprecedented level of settings to tweak.
#### [Heaven Studio](https://archive.org/details/heaven-studio) (Rhythm Heaven)
A tool to create playable Rhythm Heaven custom remixes.
	There's a ton of fan-made levels and YouTube showcase videos out there, so YouTube and the Discord's level showcase channel are good places to look.
	Unfortunately, the [itch.io page](https://rheavenstudio.itch.io/heaven-studio) does not include any downloads due to a DMCA from Nintendo, but the tool is still available from the Archive.org link.
	If anyone has a collection of official Nintendo charts and minigames remade in Heaven Studio, [[Discussion|lmk]].
	- [control guide](https://heaven-studio-control-guide.super.site/)
	- [dev curated levels](https://archive.org/details/heaven-studio-devs-picks-level-pack), [levels that shipped with Heaven Studio](https://archive.org/details/heaven-studio-official-levels)
#### [RetroFab](https://itizso.itch.io/retrofab)  (Game & Watch)
A collection of simulators for various LCD games (such as the Game & Watch series), playable in browser.
	Send it to your buddies and tell them that they'll never beat your score in Ball or whatever :D
#### [DoujinSoft Store](https://diy.tvc-16.science/) (WarioWare D.I.Y.)
An online repo for WarioWare D.I.Y. microgames, playable in browser!
	WarioWare D.I.Y.'s main gimmick was basically being a really rudimentary and simple game engine that let players program their own microgames. Think of this site like an archive for all the microgames people made.
#### 🌟 [The Mother 3 Fan Translation](https://mother3.fobby.net/)
_The_ English fan-translation of Mother 3.
	This is the English translation everyone plays. It's made by Tomato, the author of Legends of Localization. Tomato has posted commentary on his translation process [here](http://legendsoflocalization.com/mother-3/). They also translated an [interview with the game's developer](https://mother3.fobby.net/interview), which they consider required reading if you're a fan of the series (after you beat the game, of course).
	I also recommend checking out the [HQ audio](https://github.com/MusicTheorist/MOTHER-3-HQ-Audio) hack for higher quality audio! Mother 3 is pretty reliant on rhythm and the GBA has infamously bad audio, so this helps. Albeit this mod apparently sounds good even on official hardware.
	- Mother 3 ROM: [Myrient](https://myrient.erista.me/files/No-Intro/Nintendo%20-%20Game%20Boy%20Advance/Mother%203%20%28Japan%29.zip), [Archive.org](https://archive.org/download/ni-roms/roms/Nintendo%20-%20Game%20Boy%20Advance.zip/Mother%203%20%28Japan%29.zip)
	- v1.3 Pre-Patched (Myrient): [En-Translation](https://myrient.erista.me/files/T-En%20Collection/Nintendo%20-%20Game%20Boy%20Advance%20%5BT-En%5D%20Collection/Mother%203%20%28Japan%29%20%5BT-En%20by%20Chewy%20%26%20Jeffman%20%26%20Tomato%20v1.3a%5D.zip), [En-Translation+HQ audio](https://myrient.erista.me/files/T-En%20Collection/Nintendo%20-%20Game%20Boy%20Advance%20%5BT-En%5D%20Collection/Mother%203%20%28Japan%29%20%5BT-En%20by%20Chewy%20%26%20Jeffman%20%26%20Tomato%20v1.3a%5D%20%5BHQ%20audio%20mix%20by%20MusicTheorist%5D.zip) 
