---
title: 🐝 Minecraft
description: Minecraft resources and recommendations
tags:
  - videogame
---
# Play
#### 🌟 [Prism Launcher](https://prismlauncher.org/)
An open source Minecraft launcher with the ability to manage multiple instances, accounts and mods.
	If you do anything but pure vanilla Minecraft, you should be using this in my opinion. Has a built in mod, shader, and resource pack downloader, skin manager, lets you manage saves, screenshots, everything. Can pull updates and automatically pulls dependencies. Incredibly useful.
	Note the ability to download [April Fools](https://minecraft.wiki/w/April_Fools%27_Day_jokes) versions, and experiments like the [combat tests](https://minecraft.wiki/w/Java_Edition_Combat_Tests) too!
#### [Betacraft](https://betacraft.uk/)
Popular launcher for beta Minecraft.
	The proxy and the launcher aim to fix some of the biggest flaws of the official Minecraft launcher in regard to legacy versions. For example, they provide fixes for skins, capes, lack of sound effects, client crashes, etc.
	You can get archived versions of the game over at [OmniArchive](https://omniarchive.net/)
	As a note, I use Prism to launch my beta 1.7.3 instance and it seems to work fine, but I know this is used for a reason, so if you run into any problems, try this.
#### [Minecraft Classic](https://classic.minecraft.net/)
Minecraft pre-indev classic, free, official, and in browser.
	For Minecraft's 10th anniversary, Mojang began to host pre-indev classic with a creative inventory for use in browser. Neat little distraction to be sure.
#### [Eaglercraft](https://deev.is/)
A pirated [open-source](https://git.eaglercraft.rip/explore/repos) thing that runs a couple different Minecraft versions in browser.
	The bane of middle school IT admins.
	They like, made an OpenGL emulator and reverse engineered LWJGL for this. Its crazy. Uses TeaVM.
	Of particular interest is 1.8.8 and beta 1.7.3. 1.12.2 is also in development. 
	Also has .html downloads available in case the site is blocked on your network or if the site goes down, which you can open from them being saved onto a USB. (select version then click offline download)
	There's a lot of fake versions out there that claim to have this or that, but they're all kinda shady. Albeit Eaglercraft is built to be easily mirrored (thus you can even self-host it)
	- [showcase video](https://www.youtube.com/watch?v=0qOCuLgX_lw
	- [server list (unofficial)](https://servers.eaglercraft.com/)
#### [Bedrock \*Nix Launcher](https://minecraft-linux.github.io/)
Lets you play Bedrock edition on Linux and other (U)nix systems (such as MacOS).
	Requires you own the game via Google Play.
# Mods
#### 🌟🌐 [Modrinth](https://modrinth.com/)
Minecraft mod distribution platform which has been widely adopted by the MC modding community.
	[Open source](https://github.com/modrinth).
	Has sections for Fabric/Quilt/(Neo)Forge mods and modpacks, server plugins, datapacks, resource packs, and shaders.
	You can also install mods from within Prism launcher, and have them pull from Modrinth's api.
	Its also really easy to make your own modpacks which you can just tell people to plug into Prism for playing on your modded server.
	iNote, some modpack creators still opt for [CurseForge](https://www.curseforge.com/). 
#### [MCArchive](https://mcarchive.net/)
Easily find old Minecraft mods, including de-listed projects.
	Mods are kept publicly accessible even after creators delist or discontinue them, hence "archive".
	They only provide downloads to mods not available from their original source, else, they direct you to the original source.
## Performance and Optimization
####  [Fabulously Optimized](https://modrinth.com/modpack/fabulously-optimized) / [Adrenaline](https://modrinth.com/modpack/adrenaline) / [Vulkan Optimized](https://modrinth.com/modpack/vulkan-optimized)
> [!warning]- This entry may be out of date
> This was written around Spring 2025, and is highly subject to expiry. 

- [Fabulously Optimized](https://modrinth.com/modpack/fabulously-optimized)
	Essentially a [drop-in replacement for optifine](https://wiki.download.fo/give-up-optifine).
	If you liked Optifine for its bells and whistles like zoom, capes, resource pack features, etc., then go with FO. [Perforium](https://modrinth.com/modpack/performium-was-taken) also comes with many Optifine features, but isn't a drop in replacement. It probably runs better on your system, so its worth checking out if you want a middle-ground there. Additive is ran by the adrenaline team and also acts as an Optifine alternative, and even Vital which is an alternative to essential can act as an alternative to Optifine. Point is: Optifine should be dead, do not use it.
- [Vulkan Optimized](https://modrinth.com/modpack/vulkan-optimized)
	Straight up replaces the entire OpenGL rendering engine with a Vulkan one using [VulkanMod](https://modrinth.com/mod/vulkanmod)
	You'll need a newer graphics card to take advantage, but on the correct hardware the performance gains are in their own league at normal render distances. I'd recommend a 64-bit system with a GTX600 / Radeon HD 7000 or greater, as well as 8GB ram or more if you plan to use this mod. I know this makes it sound like its demanding, but if you meet the system requirements this pack will perform the best. In the future, this mod may also not be necessary since Mojang is planning on adding Vulkan support in the future.
- [Adrenaline](https://modrinth.com/modpack/adrenaline)
	As far as I know, this is the most performant modpack (on average)
	and when rendering at 18-22 chunks, and which doesn't outright replace the rendering engine of the game like Vulkan Optimized does. At the time of writing.
	This said, [Simply Optimized](https://modrinth.com/modpack/sop) Is a close second (less than 1% performance distance, within margin of error). Both do not include QoL mods.
- **tl;dr** Fabulously Optimized to replace Optifine, Vulkan Optimized if your system can run it, Adrenaline if your system can't.
	If you dont want to use a modpack, start with [Lithium](https://modrinth.com/mod/lithium) and [Sodium](https://modrinth.com/mod/sodium) at the very least, and then look at the mods used in the latest version of Adrenaline/Simply and go from there. Nvidium and Distant Horizons throw a wrench in these, and I'm not sure what the best mods to pair with them would be. Perhaps just use Adrenaline as a base? Nevertheless:
#### [Nvidium](https://modrinth.com/mod/nvidium)
Rendering backend for Nvidia GPUs that gives extreme, uncompromised render distance.
	Uses black magic (mesh shaders) to render a lot of game. We're talking rendering all of Hermitcraft season 8 at once.
	This mod does not use LoD. Its all rendered in real time, as fully loaded chunks.
#### [Distant Horizons](https://modrinth.com/mod/distanthorizons) / [Voxy](https://modrinth.com/mod/voxy)
Uses LoD (Level of Detail), to simulate extreme render distances.
	Essentially, non-loaded chunks aren't loaded, and appear as simplified, fake terrain. Yes, both works with player made structures.
	I'm not sure which one is better at the time of writing, but I've heard great things about both, so try each out and see which you prefer for your usecase.
	- [Voxy Showcase, vs Distant Horizons pros and cons](https://youtu.be/Fs6Ag6Eq-bQ)
#### [Bobby](https://modrinth.com/mod/bobby)
Caches chunks to the client, allowing for higher render distances than the server would normally allow.
	Many servers force players to play with low render distances, since the server has to handle the chunks around a player, Bobby gets around this.
	Optionally, can also use a singleplayer world as a fallback if you've never loaded a given chunk on the server before, if you happen to have the server's seed.
	Of course, in both these contexts Bobby would leave you in the dark to any changes other players may have made to un-cached or out of date cached chunks, so Bobby may not reflect the actual state of a chunk.
	Bobby does not cost the server any performance.
#### [Custom Player Models](https://modrinth.com/plugin/custom-player-models)
Mod that does what it says on the tin. As a note, others will need to have the mod to see your custom model.
	- [Mario Skin Pack](https://ko-fi.com/Post/SUPER-MARIO-Minecraft-CPM-Skin-Pack-FREE-DOWNLO-F1F5WL0H5)
		Custom model skin pack for Super Mario characters. [Trailer](https://www.youtube.com/watch?v=fy2re9YKYQM)
	- [Mother/Earthbound Skin Pack](https://ko-fi.com/Post/MOTHER-1-2-SKIN-PACK-Minecraft-CPM-Skin-Pack-FR-U6U7158MER)
		Custom model skin pack for Mother characters. [Trailer](https://www.youtube.com/watch?v=OF81QGA4iCk)
	- [Mob Psycho 100 Skin Pack](https://ko-fi.com/Post/Mob-Psycho-100-Minecraft-CPM-Skin-Pack-FREE-DOW-R6R5YME0J)
		Custom model skin pack for Mob Psycho 100 characters. [Trailer](https://www.youtube.com/watch?v=tUyT_TcLU2Y)
	- [Sonic the Hedgehog Skin Pack](https://ko-fi.com/s/4d0a726c26)
		Custom model skin pack for Sonic the Hedgehog and friends. [Trailer](https://www.youtube.com/watch?v=qph8ML9eSHs)
	- [Hatsune Miku Skin Pack](https://ko-fi.com/s/d0aef38ca6)
		Custom model skin pack for Hatsune Miku, featuring multiple skins and emotes. [Trailer](https://www.youtube.com/watch?v=ro4EqO5RXyI)
	- [Batman Skin Pack](https://ko-fi.com/s/b65439a007)
		Custom model skin pack for Batman, with 3 suits (Arkham, 1970's, and Beyond)
	- [Dungeon Meshi / Delicious in Dungeon Skin Pack](https://ko-fi.com/s/8c52aa39c9)
		Custom model pack for Dungeon Meshi, featuring Laios, Marcille, Chilchuck, Senshi, and Izutsumi.
	- [Bocchi The Rock! Skin](https://ko-fi.com/s/1d944c6634)
		Custom model for Bocchi from Bocchi The Rock!
	- [Alphs' Unreleased Model Library](https://ko-fi.com/s/6bb8506f09)
		Members only (paid) skin pack for Alphs' unreleased models. Sora, Fortnite, Lethal Company, Wario/Waluigi, Family Guy, Dragon Ball, Joker, Bocchi, and more.
## Resource Packs
#### 🌟 [Vanilla Tweaks](https://vanillatweaks.net/)
A bunch of very nice little texture tweaks to make Minecraft just a tad better.
	As of 1.21.4 I use [this pack](https://vanillatweaks.net/share#Nd8Ew9) which is a (cancellable) direct download that'll show you which I have selected.
#### [Redstone Tweaks](https://modrinth.com/resourcepack/redstone-tweaks)
A bunch of very nice texture tweaks to redstone textures, which improves conveyance.
	Vanilla Tweaks includes some, but redstone tweaks has much more. You're able to configure it with [ResPackOpts](https://modrinth.com/mod/respackopts)
#### [Visual Shulker Labels](https://ewanhowell.com/resourcepacks/visual-shulker-labels)
Lets you name your shulker box to put an image of the named item on it.
	For example, you can name a shulker box "food and farm stuffs - Apple" to have it display an apple as its label.
	Does not actually require Optifine. See above for more info.
	- [Visual Shulker Labels 2D](https://ewanhowell.com/resourcepacks/visual-shulker-labels-2d-display) addon for cleaner labels.
#### [Xali's Potions](https://modrinth.com/resourcepack/xalis-potions)
Gives every potion a unique texture, so that they can be visually told apart from one another.
	- [Xali's potions addon](https://modrinth.com/resourcepack/xalis-potions-addon) addon for potions Xali's original is missing.
	- [Many alternatives exist](https://modrinth.com/resourcepacks?q=potion&s=downloads)
#### [Xali's Enchanted Books](https://modrinth.com/resourcepack/xalis-enchanted-books)
Gives every enchanted book a unique texture, so that they can be visually told apart from one another.
	- [Many alternatives exist](https://modrinth.com/resourcepacks?q=enchant&s=downloads)
#### [Visual Armor Trims](https://modrinth.com/resourcepack/visual-armor-trims)
Gives every armor trim a unique texture, so you can tell trims apart.
#### [Mob Crates](https://modrinth.com/resourcepack/mob-crates)
"Replaces" spawn eggs with spawn crates, which is more visually distinguishable.
	As of snapshot 25w08a, Mojang has overhauled mob egg sprites to be easy to visually distinguish, making this resource pack a bit redundant. That said, its useful in older versions.
## Data Packs
#### 🌟 [Vanilla Tweaks](https://vanillatweaks.net/)
A bunch of very nice datapacks and crafting tweaks that make Minecraft just a tad better.
	I use armor statues, name colors, silence mobs, more effective tools, spectator conduit power, spectator night vision, unlock all recipes, graves, spawning spheres, track (raw) statistics, workstation highlights, and sometimes double shulker shells if I'm feeling fancy. On the crafting tweaks side I use dropper to dispenser, universal dying, straight to shapeless, blackstone cobblestone, and unpackable ice.
#### [Mini Blocks](https://modrinth.com/datapack/mini-blocks-datapack)
More miniblocks than the VanillaTweek's datapack provides.
	Uses their textures as well as textures from Minecraft Heads below. Throw a block into a stonecutter to get a "mini" version of the block (a playerhead textured to look like the block). Existing miniblocks should continue to work even if this datapack is removed from your world.
## Creative Tools
#### 🌟 [Axiom](https://modrinth.com/mod/axiom/)
Worldedit on steroids. Basically turns minecraft into a 3D creative software suite.
	Makes creative building, prototyping, and sculpting extremely simple and easy, all in real-time. Completely free for non-commercial use.
#### [Voxel-Vision](https://www.voxel-vision.com/)
Convert blender models to Minecraft blocks.
	Most videos on YouTube were made when it was called BlockBlender, so look that up. Its pretty impressive.
	This said, they only allow you to import models as stone in the free version.
## Shaders
> [!note] All shaders aside from Complimentary + Euphoria are just for fun
#### 🌟 [Complimentary](https://www.complementary.dev/shaders/) + [Euphoria Patches](https://www.euphoriapatches.com/)
Complimentary is the most popular Minecraft shader at the time of writing.
	Euphoria basically just gives you more settings to further tweak it than what complimentary provides by default.
	My settings look little like default complimentary, as I'm trying to accomplish my interpretation of a "Mojang" style shader somewhere between the vibrant visuals and the trailers. You can download my settings at the time of writing for import [here](https://files.catbox.moe/oij11y.txt), It should work in both Reimagined and Unbound, though I use Reimagined. This is loosely based on demonjoeTV's settings if you'd like an approximation: [showcase](https://www.youtube.com/watch?v=N9WjsUZOYl8)
#### [Rudimentary](https://modrinth.com/shader/rudimentary-ps1) and [Minecraft-PSX](https://github.com/ckosmic/minecraft-psx)
Two separate cracks at making Minecraft look like a Playstation 1 game, with v-snapping, texture warping, and distance fog.
	Rudimentary also has a "horror mode" that looks fun, and minecraft-psx is used in the MCSX horror modpack below.
#### [PixelCraft](https://modrinth.com/shader/pixelcraft-shaders)
Complimentary shaders edit meant to make the game look like pixel art, sort of like the paintings.
	Check out the gallery. Cool for neat screenshots
#### [Epoch](https://modrinth.com/shader/epoch) and [MC VHS](https://modrinth.com/shader/mc-vhs)
Epoch is a vintage/low-fi emulating shader, and MC VHS replicates the look of old VHS recordings.
	Both are neat for screenshots and the like.
#### [Acid Shaders](https://modrinth.com/shader/acidshaders15)
Fan-made remaster of the original acid shaders by MiningGodBruce.
	Super cool. If you want an idea of what you'll get, MiningGodBruce's music videos are a good place to start. Here's [Subtlety by Topaz](https://www.youtube.com/watch?v=C1ZN_NRBWwI) as an example.
	Bruce is currently working on Acid Engine, which has yet to be released, but should prove to be even better than acid shaders.
	Note that Euphoria has an option for similar functionality under its "fun" tab.
## Modpacks
#### 🌟 [Better Than Adventure](https://www.betterthanadventure.net/)
An extensive fan-made fork of beta 1.7.3 that asks "what if Mojang kept the design sensibilities of beta?"
	So sick. I highly recommend you check out their [trailers](https://www.youtube.com/@BetterthanAdventure/videos), starting from the release 1.7.7.0 trailer.
	Mods and servers for BTA are available on their [Discord](https://www.betterthanadventure.net/discord) :T
#### 🌟 [Raspberry Flavoured](https://www.curseforge.com/minecraft/modpacks/raspberry-flavoured)
An expansion and overhaul to the intrinsically motivated sandbox that is modern Minecraft.
	My favorite modpack of all time, maybe the only one I've seen with its design as well thought out as it is, with as much attention to detail as it has.
	Controversially, it removes villagers, The End, and xp. However the systems it replaces these mechanics with I think serve the game very, very well.
#### [Re-Console](https://modrinth.com/modpack/legacy-minecraft)
Recreates the feeling of Legacy Console Edition in Java.
	Nice if you're nostalgic about Xbox 360 edition like I am :)
	Re-Console's pitch is "if Legacy Console Edition never ended", so it still has features from newer versions of the game.
	[Re-Console: Legacy](https://github.com/ViolaFlower/Re-Console-Legacy) is meant to emulate the experience of legacy versions outright, without the new features, and is made by the same developer.
	Re-console and Re-Console: Legacy are modpacks using the [Legacy 4j](https://modrinth.com/mod/legacy4j) mod.
#### [MCSX](https://www.curseforge.com/minecraft/modpacks/mcsx-minecraft-ps1-edition)
A cute little horror/arg modpack that pretends its a cursed PlayStation 1 release of minecraft.
	Uses a modified version of the Minecraft-PSX shader above.
# Other
## Worlds / Minigames
#### [Skyblock (standard)](https://modrinth.com/datapack/standard-skyblock)
The basic Skyblock map you know, but with an infinite void.
	And yes, biomes and structure bounding boxes. Also very small starting nether/end islands. Standard benefits from other companion mods in their [collection](https://modrinth.com/collection/QcjV0vVX) for things like [advancements](https://modrinth.com/datapack/skyblock-advancements) and [making unobtainables obtainable](https://modrinth.com/datapack/sky-void-additions), as well as the [vanilla one block](https://modrinth.com/datapack/xb16810H) challenge.
	- [World in a Jar Remastered](https://www.planetminecraft.com/project/world-in-a-jar-3-fanmade/) - An old-school SkyBlock derivative that I remember a bit fondly, remade for more modern Minecraft versions.
#### [Legacy Console Edition tutorial world collection](https://www.theminecraftarchitect.com/tutorial-worlds)
A collection of every tutorial world from legacy console edition.
	Minigame maps are also available.
	- [CurseForge](https://www.curseforge.com/minecraft/worlds/tutorial-world-collection)
#### [Minecraft 10th Anniversary Map](https://www.minecraft.net/en-us/article/get-your-free-anniversary-map)
Blockworks map commissioned by Mojang to celebrate the game's 10th anniversary.
	I had a lot of fun with this when it came out, and its quite pretty. [Wiki](https://minecraft.wiki/w/10_Years_of_Minecraft)
	There's also two official maps for Minecraft's 15th anniversary, but I haven't tried them.
	- [15 Year Journey (wiki)](https://minecraft.wiki/w/15_Year_Journey) - Officially commissioned map for Minecraft's 15th anniversary. Bedrock exclusive.
	- [Java Multiplayer Madness](https://www.minecraft.net/en-us/article/java-multiplayer-madness) - Meant to specifically celebrate Minecraft Java Realm's 10th anniversary, and is a collaboration between 100+ volunteer map makers. Though you can download the map for use outside of realms no problem.
#### [The Uncensored Library](https://uncensoredlibrary.com)
Blockworks map commissioned by Reporters Without Borders, circumventing and teachings regarding journalistic censorship.
	Uses a pretty novel loophole to educate the Minecraft playing youth on the importance of uncensored journalistic integrity. Updated in 2021. Really cool and novel.
	- [Making of trailer](https://www.youtube.com/watch?v=vFKvjEV6muc)
	- IP: `visit.uncensoredlibrary.com`
#### [Tunnel Rats](https://xisumavoid.com/tunnelrats/)
Multiplayer minigame designed by the original creator of BedWars (Xisumavoid), and its honestly more interesting than BedWars to me.
	Underground, two teams dig through symmetrical terrain towards each other, collecting materials and meeting in the middle for a pvp skirmish a bit of the ways into the game. Destroy the other teams bed then kill them all to win. Tons of variance and cool stuff is possible with the level editor, but many maps are packaged in by default as well.
	You could even build a map for disposable use in survival if you wanted, which is actually how Xisuma first designed the game. Available for Java for free as well as the marketplace.
	- [Trailer](https://www.youtube.com/watch?v=ECf2Fm649k8), [Gameplay Showcase](https://www.youtube.com/watch?v=XRWnIuNew2w), [Level Editor Tutorial/Showcase](https://www.youtube.com/watch?v=tALmU9GaWRY)
#### [EarthMC](https://earthmc.net/download)
A recreation of earth as a 1:500 scale Minecraft map.
	There's two versions available for download, and the third version is only playable on their server.
#### [Yet Another Bingo / Lockout](https://modrinth.com/mod/yet-another-minecraft-bingo)
Multiplayer minigame to find items or complete objectives before others, in survival.
	If you've seen those bingo/lockout videos by creators like [SmallAnt](https://www.youtube.com/playlist?list=PLZg5oPXUrUNL5OBshKOGp9T9SWZhkA-1f) and others, I'm pretty sure this is the mod they use. Regardless, this is a high quality, polished, and very configurable rendition of the concept.
	Players/teams are given a bingo card full of objectives in their gui, make a line to score, or make it so that everyone shares the card and only one player/team can score a tile, where most points win.
#### [Five Nights at Freddy's in Minecraft](https://www.planetminecraft.com/project/1-17-five-nights-at-freddy-s/) / [FNAF2](https://www.planetminecraft.com/project/fnaf-2-6052044/) / [FNAF3](https://www.planetminecraft.com/project/fnaf-3-miramappa/) / [FNAF4](https://www.planetminecraft.com/project/fnaf-4-miramappa/)
A cute mapset that recreates FNAF 1-4 in Minecraft.
	Pretty self-explanatory, and surprisingly high quality.
	- [Trailer](https://www.youtube.com/watch?v=4cqZ3iSva5M), [2 Trailer](https://www.youtube.com/watch?v=nA-yW67-dnk), [3 Trailer](https://www.youtube.com/watch?v=xK0MCOiscjE), [4 Trailer](https://www.youtube.com/watch?v=q7DAjiuFMjI)	
#### [Kitatcho Labs chapter 3](https://www.minecraftmaps.com/49957-the-kitatcho-laboratories-chapter-3)
A puzzle map with an original ost, full voice acting, etc.
	They're going for a sort of Portal like thing. You do not need to play the first two chapters to enjoy chapter 3
#### [Evergrowth](https://gm4.co/evergrowth/)
A Sokoban puzzle map. I like it :)
	 - [Trailer](https://youtu.be/fkBs9pX8sQo)
#### [WiiParty Plus](https://www.planetminecraft.com/project/wii-party-in-minecraft-6519651/)
WiiParty re-created in Minecraft.
	Super impressive. They also have an official server, but it's a public lobby:
	- IP: `wiiparty.spmc.co`
	- [Trailer](https://youtu.be/o0kxHLr_Swc?si=NQpG_pKL60vw84TC)
#### [Warioware in Minecraft](https://www.planetminecraft.com/project/warioware-inc-in-minecraft/)
Cute little minigame where you play little microgames, but with Minecraft.
	Singleplayer and multiplayer.
## Servers
#### Self Host: [Minecraft Docker Server](https://docker-minecraft-server.readthedocs.io/en/latest/)
[setupmc.com](https://setupmc.com/java-server/) can be used to help build a Docker server compose script, which is what I use :)
	This is way easier than it sounds, but if you really dont want to do the setup yourself then consult the chart for a Minecraft server host: [Minecraft Dedicated Server Host Testing Data by CygnusMC](https://docs.google.com/spreadsheets/d/1HZE7Pi6FPEhbN-JQtXKX69Udp6dA5OBOu4Kpdzz53MI)
	You can use a generic [VPS](https://vpspricetracker.com/), but best practice is to use a Minecraft host since their hardware is chosen specifically for the game, and you'll get better price to performance that way.
>[!warning]- Be sure to secure your server properly with a reverse-proxy or something similar when self-hosting
>Docker is containerized, which can help with security. However, you still dont want to be forwarding your ports to the open internet without a proper setup. e4mc below is a mod that does this automatically.

#### Automatic Multiplayer Mods:
##### [Vital](https://usevital.github.io/) (Essential alternative)
Alternative to the [kinda scummy](https://notessential.blurry.gay/#why-not?) Essential-mod, and Optifine as well.
	Vital simply bundles the suggestions made in NotEssential into a modpack.
##### [World Host](https://modrinth.com/mod/world-host)
What Vital uses for multiplayer, and has a friends system.
	UPnP mode is tried first. Your client tries to open a temporary port forward in your router that your friends client can use to connect to you directly. If UPnP fails, then your client tells the server to use proxy mode. The server will then give your friend's client the same "proxy IP" as `/worldhost ip` does.
##### [e4mc](https://modrinth.com/project/qANg5Jrr)
Similar to World Host but is better for heavily modded instances.
	e4mc is a reverse tunneling reverse proxy for Minecraft. In simpler terms, it's a software that allows you to temporarily expose a local Minecraft server to the internet. Make sure your mod lists are identical so you dont desync!
#### Server List Sites
Sites that index MC Servers
	Generally speaking, you'll find higher quality, more interesting servers via personal recommendation, YouTube showcases, from Patreon whitelisted servers from your fav content creators, or in your existing community's Minecraft server, but server lists like these still provide some value, so:
	- [The Official Minecraft Server List](https://findmcserver.com/)
		Licensed and affiliated with Mojang, by GamerSafer.
		Something not many people know exists, but it does. Its pretty heavily moderated and squeaky clean, but y'know, its a place to start.
	- [NameMC](https://namemc.com/minecraft-servers)
		As far as I know, NameMC literally just keeps a list of every server they come across and lists them by a mix of player count and likes. Their primary thing is keeping track of players and their skins, so they haven't started taking money for higher listings or whatever... yet. Also there's not a ton of annoying animations and banners.
#### [Minecraft Speedrunning Ranked](https://mcsrranked.com/)
Ranked speedrunning server, gives each player an ELO score to determine matchmaking.
	In a game, two players are placed on copies of the same curated seed. First player to defeat the dragon and exit the end wins. You have to use their client to connect, so download that in your favorite launcher from the above link.
	- [MinecraftSpeedrunning.com](https://www.minecraftspeedrunning.com/home)
		Website compiling useful resources for Minecraft speedrunning. Tools, maps for practice, information and resources, etc.
	- [MCSR Practice Map](https://github.com/Dibedy/The-MCSR-Practice-Map)/ [MiniPracticeKit](https://github.com/Knawk/mc-MiniPracticeKit)
		Practice map that combines all important practices into one map. the next is a set of command block kits you can save to your creative menu to automatically create drills in a new world, I recommend setting these up for use in singleplayer worlds in your MCSR client :3
#### [Modern Beta](https://modernbeta.org)
A recreation of beta 1.7.3, playable from modern Minecraft versions. Java and Bedrock.
	Works with both modern Java and Bedrock if you connect with the play IP, and you can connect with a b1.7.3 client by using the beta IP.
	- IP: `play.modernbeta.org` / `beta.modernbeta.org`
#### [MinecraftOnline](https://minecraftonline.com) / [Novylen](https://minecraft.novylen.net/)
The oldest surviving Minecraft servers that have yet to go through a map reset.
	Both were started the day that survival multiplayer launched and are the only two surviving servers. Lots of history in both of these
	I'm more familiar with MCOnline, which in my opinion is laggy and a tad mismanaged. They also have a weird free speech absolutism thing going on, so bleh.
	Novylen also uses protect plugins, rather than just banning people whom happen to grief, which is more annoying in my opinion.
	Pick your poison I suppose!
	These are cool to explore, idk about actually playing on them, though.
	- IP: `minecraftonline.com` / `mc.novylen.net`
#### [FishOnMC](https://fishonmc.net)
wtf Minecraft fishing simulator 300+ fish fishing simulator
	Scientifically accurate fish data unique fishing mechanics different locations in the world fishing in minecraft??
	If you're a sweat, [FishOnTools](https://dannypx.github.io/FishOnTools/) and the [FishOnMC wiki](https://wiki.fishonmc.net) may prove useful
	- IP: `play.fishonmc.net`
#### [Library of Babel](https://doteye.online/projects/mclob/)
The [library of babel](https://libraryofbabel.info/) (inspired by the [short story](https://archive.org/details/TheLibraryOfBabel)), playable in Minecraft.
	A direct download for the Library of Babel would be ~400 petabytes large, so you have to either join on the server or host the [custom server software](https://github.com/DotEye/Minecraft-Library-of-Babel) yourself to explore.
	- IP: `mclob.doteye.online`
### (Seemingly) best of genre
I've done light research into each of these, but dont play them all. These are mostly my first instinct if I want to play these types of game modes for a bit. if you have suggestions or any of these seem wrong, say as much in the [[Discussion]] page please!
#### SMP / Factions: [OG Network](https://www.og-network.net/)
One of the few authentic ones left. PvP / Griefing is allowed. SMP has a player run marketplace, etc.
	Griefing in SMP is lightly discouraged with a reputation system. You can give players + or - rep which everyone can see, but else it's just allowed.  Enough - rep takes away /tpa, /spawn, etc. At -15 rep everyone can see your position at all times. Pretty neat.
	They also have og survival games, but it doesn't seem like anyone plays it, which is a shame because that's probably the only place where getting a game going is possible. I'd like to see them add SkyBlock personally.
	Its ran by a [slop YouTuber](https://www.youtube.com/@TheMisterEpic), but one of those that has made a lot of videos duping on pay-to-win lootbox servers, and is sort of immersed in that sort of part-dirtbag part gaming-needs-to-do-better culture, so the bullshit is very minimum and he seems to care about making a good server.
	Else, just join your friend's server for SMP lol. Or maybe your favorite creator's Patreon or something idk.
	- IP: `og-network.net`
#### Anarchy: [2b2t.org](https://2b2t.org) / [Constantiam](https://constantiam.net) 
The two most important Anarchy MC servers
	Both of these servers will have a lot that's reminiscent of the Chan cultures they derive from, but despite this I do still think both servers have value due to their storied histories, impressive builds, and interesting happenings.
	2b2t
		"the oldest anarchy server in minecraft"
		Recently updated to more modern versions after being stuck on 1.12 for forever. Lots of documentaries about the server on YouTube and such, though they're all a bit overly serious and melodramatic. Regardless, its neat.
		If the queue is long for you, Constantiam is probably the best alternative. 
		- IP: `2b2t.org` 
	Constantiam
		A lot of 2b2t veterans fled here around 2016, seemingly due to the flood of newgens from YouTube.
		Its the oldest alternative at 9 years old, and was the first notable anarchy server to upgrade from 1.12
		Constantiam's culture isn't quite like 2b's, and that's by design. Don't just go griefing everything you see. Like, you can, just don't be a dweeb about it.
		- IP: `constantiam.net`
	Museum of 2b2t and Constantiam
		This unofficial museum server archives world downloads of various builds made on both servers before they've been griefed.
		- IP: `thearchive.world`
#### Battle Royale / Survival Games / Hunger Games: [Hoplite](https://hoplite.gg/)
More interesting than any old-school Hunger Games server ever was, imo.
	Its sort of its own thing with custom weapons and such, but the vanilla game is certainly still in here. [Rekrap's Hoplite videos](https://www.youtube.com/@rekrap1/search?query=hoplite) will give you an idea on how the server plays.
	- IP: `hoplite.gg`
#### PvP: [PvP Legacy](https://pvplegacy.net/)
This is the primary server I've been told about for PvP.
	You can make custom kits and fight players in an arena with those kits. idk anything about Minecraft PvP
	- IP: `play.pvplegacy.net`
#### Parkour: [CyloneMC](https://CyloneMC.net)
This is that parkour server you see in all the AI slop vids on your fyp.
	Players can build their own parkour maps then add them to the public database, and a speedrunning leaderboard is maintained, so there's hundreds of parkour maps for every skill level. It's nice.
	- IP: `mc.cylonemc.net` 
#### Skyblock: [Skyblock.net](https://skyblock.net)
Skyblock hosted by its original creator.
	This one I'm not so sure about, but it is... "official". So I guess it has that going for it, despite everything else going on in the server and how [litigious about their copyright](https://skyblock.net/threads/skyblock-and-the-minecraft-marketplace-a-legal-battle.145369/) they are.
	- IP: `skyblock.net`
#### MMO: [Wynncraft](https://wynncraft.com) / [Monumenta](https://playmonumenta.com) / [Megido Abyss](https://medigo.xyz)
Three MMO type MC servers
	Wynncraft
		Probably Minecraft's largest MMO project next to Hypixel SkyBlock, and is the original. Very visually impressive, cool spell systems, custom resource pack. Its been in development for over a decade and it shows. Very nias.
		  - IP: `play.wynncraft.com`
	Monumenta
		Stays closer to vanilla mechanics and goes in a dungeon crawler direction.
		One dungeon of note is Darkest Depths, which is procedurally generated dungeon that wipes your character and gives you abilities only for the course of the run... yes... its a roguelike. It's neat.
		Regions in architect 3 are also so pretty.
		 - IP: `server.playmonumenta.com`
	Megido Abyss
		This one has souls-like combat. Parries, dodging, bosses. y'know how it be. Unfortunately, the player count is quite low.
		- IP: `play.medigo.xyz`
#### Hypixel Competitors: [CubeCraft](https://cubecraft.net), [MCC Island](https://mcchampionship.com/island/)
Minigame servers
	CubeCraft
		Probably Hypixel's #1 competitor, thanks to its presence on the bedrock featured servers list. 
		he bedrock server is more popular, but the Java server is plenty active. Some argue that Hypixel BedWars ripped off CubeCraft EggWars swag.
		- IP: `play.cubecraft.net`
	MC Championship Island
		Minecraft Championship's public half. Actually play the Minecraft Championship minigames from those tournaments.
		- IP: `play.mccisland.net`
#### Manhunt: [MC Manhunt](https://mcmanhunt.com)
There's also DeathSwap and random item challenges. Neat ig.
	- IP: `mcmanhunt.com`
## Websites and tools
#### 🌟 [Official Minecraft Wiki](https://minecraft.wiki/)
The real wiki, better maintained than Fandom.
	The Minecraft Wiki actually is made up of staff that migrated off of Fandom, support them so they move up in search results. Not to mention that the old Fandom wiki is now falling apart due to poor maintenance :)
	You can use the bang `!mcw` or `!mcwiki` to search the wiki if you have a tool that can search with bangs, or use [[PC Mods Extensions#[Indie Wiki Buddy](https //getindie.wiki/)|Indie Wiki Buddy]] to auto redirect from fandom.
#### [Totem Generator](https://skinmc.net/totem)
Cute tool to automatically generate a totem based on your skin.
#### [Minecraft Heads](https://minecraft-heads.com/)
A database of decorative mini blocks
	Minecraft has a feature that lets you load in player heads as a block, this is a database of those. On each head's page, a command is provided to add the head to your in-game inventory without mods, which will work so long as you have op permissions on a cheats enabled world.
	If you want a good way to get some in survival, check out Vanilla Tweaks and Mini Blocks above.
	[Freshcoal](https://freshcoal.com/maincollection.php) also has a heads collection which may prove useful.
#### [Need Cooler Shoes Skin Editor](https://needcoolershoes.com)
This is the best skin editor I know of. They also have a [banner editor](https://needcoolershoes.com/banner).
	Though a lot of people use [Planet Minecraft's Skin Editor](https://www.planetminecraft.com/skin-editor/) and [banner editor](https://www.planetminecraft.com/banner/)
#### [BlockColors.app](https://blockcolors.app/) / [BlockPalette.com](https://www.blockpalettes.com)
Tools that make it really easy to create a simple block palette for your next build.
#### [Plotz](https://www.plotz.co.uk/)
Easily generate shapes like spheres, circles, and more with voxels.
	Also makes it easy to copy off of for survival building.
#### [Buildpaste](https://buildpaste.net/)
A database of Minecraft structure files for pasting into your Minecraft world, or for building with [Litematica](https://modrinth.com/mod/litematica) ^^
#### [MCSeed Map](https://mcseedmap.net/)
Lets you hunt for a seed meeting your specified parameters
#### [Gneiss' 1.21 Color World](https://www.youtube.com/watch?v=bQ_dgs02zoc)
Interactive Minecraft world that displays blocks based on their texture color.
	Good for pallettes, gradients, and seeing relationships between block colors. 
#### [MapArtCraft](https://rebane2001.com/mapartcraft/)
Easily generate Minecraft map art from image.
	[mc wiki: map item format](https://minecraft.wiki/w/Map_item_format#Map_pixel_art) also has a table for pixel color values with their correlating blocks, if you wanted to manually draw pixel art in a program like [[Hardware Software#[Aseprite](https //github.com/aseprite/aseprite)|Aseprite]].
	Map art is 128×128px. I also recommend checking the [FAQ](https://rebane2001.com/mapartcraft/faq).
#### [MinecraftArt](https://minecraftart.netlify.app/)
Does something similar to MapArtCraft, but for those billboarded pixel art images.
#### [MCStacker](https://mcstacker.net/)
GUI for generating Minecraft commands.
	- [minecraftjson.com](https://www.minecraftjson.com/) - Good for `/tellraw` commands.
	- [r/minecraftcommands resources](https://www.reddit.com/r/MinecraftCommands/wiki/resources/) - Good place to go if you're interested in this sort of thing.
#### [web NBT editor](https://irath96.github.io/webNBT/)
Lets you view and edit nbt data in your browser.
#### [MCUtils](https://mcutils.com/)
Tools to create fireworks, banners, gradients, etc. in browser.
	Far from perfect. In fact its quite flawed, but still useful.
	- [1280px's hueblocks](https://1280px.github.io/hueblocks/) - Can also be used for block gradients.
#### [A Minecraft Timeline](https://minecraft-timeline.github.io/)
Can't remember what Minecraft version you first played, or what update added what? Use this.
	Has timelines for java and bedrock (pocket edition). My first version I remember playing was Java release 1.2 :3
	For legacy console editions (pre better together update), see [here](https://minecraft.wiki/w/Legacy_Console_Edition_version_history)
#### 🌟 [Blockbench](https://blockbench.net)
Open-source 3D modeling software with a big focus on low-poly and voxels.
	Used by Mojang, Hytale, and more.
	Also notable is their [Minecraft title generator](https://web.blockbench.net/?plugins=minecraft_title_generator), if you just want to generate text in the Minecraft update graphic style.
## Misc.
#### [Minecraft Game Design by jeb_](https://archive.org/details/minecraft-game-design/mode/1up)
jeb_'s Minecraft game design book as featured in Minecraft Life 2020
	Details a couple of jeb's axioms for the game. It wasn't supposed to be public, but due to Swedish law shenanigans it had to be added to a library, meaning it could be rented, meaning it could be preserved online. The above link lets you read it on Archive.org :)
#### Snapshot/update coverage [Xisumavoid](https://www.youtube.com/playlist?list=PL7VmhWGNRxKixIX8tWEQn-BnYKE9AaAXk), [Slicedlime](https://www.youtube.com/@slicedlime/videos)
Minecraft snapshot overviews, in video form.
	Xisumavoid and Slicedlime both cover updated in a timely fashion, and they both also post a recap covering all the new changes and additions for major releases.
	Xisuma has nice thumbnails and editing, Slicedlime is the Java edition tech lead. Pick your poison.