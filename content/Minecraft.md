---
title: 🐝 Minecraft
description:
tags:
  - videogame
  - minecraft
---
# Play
#### [Prism Launcher](https://prismlauncher.org/)
An open source Minecraft launcher with the ability to manage multiple instances, accounts and mods. If you do anything but pure vanilla minecraft, you should be using this in my opinion. Has a built in mod, shader, and resource pack downloader, skin manager, lets you manage saves, screenshots, everything. Can pull updates and automatically pulls dependencies. Incredibly useful.
Note the ability to download [april fools](https://minecraft.wiki/w/April_Fools%27_Day_jokes) versions, and experiments like the [combat tests](https://minecraft.wiki/w/Java_Edition_Combat_Tests) too!
#### [Betacraft](https://betacraft.uk/)
a popular launcher for beta versions of minecraft. The proxy and the launcher aim to fix some of the biggest flaws of the official Minecraft launcher in regard to legacy versions. For example, they provide fixes for skins, capes, lack of sound effects, client crashes, etc. You can get archived versions of the game over at [OmniArchive](https://omniarchive.net/)
That said, i use prism to launch my beta 1.7.3 instance and it seems to work fine, but i know this is used for a reason so if you run into any problems, try this.
#### [Minecraft Classic](https://classic.minecraft.net/)
for Minecraft's 10th anniversary, mojang began to host pre-indev classic with a creative inventory for use in browser. Neat little distraction to be sure.
#### [Eaglercraft](https://deev.is/)
The bane of middleschool IT admins. A pirated [open-source](https://git.eaglercraft.rip/explore/repos) thing that uses a TeaVM to run a couple different minecraft updates in your browser. They like, made an OpenGL emulator and reverse engineered LWJGL for this. Its crazy. Of particular interest is 1.8.8 and beta 1.7.3. 1.12.2 is also in development
Also has an .html downloads available in case the site is blocked on your network or if the site goes down, which you can open from them being saved onto a USB. (select version then click offline download)
There's a lot of fake versions out there that claim to have this or that, but they're all kinda shady. Albeit eaglercraft is built to be easily mirrored (thus you can even self-host it)
[showcase video](https://www.youtube.com/watch?v=0qOCuLgX_lw), [server list (unofficial)](https://servers.eaglercraft.com/)
#### [Bedrock \*Nix Launcher](https://minecraft-linux.github.io/)
lets you play Bedrock edition on Linux and other nix systems (such as MacOS). Requires you own the game via Google Play.

# Mods
#### [Modrinth](https://modrinth.com/)
an [open source](https://github.com/modrinth) minecraft mod distribution platform which has been widely adopted by the MC modding community in favor of curseforge. Has sections for fabric/quilt / (neo)forge mods and modpacks, server plugins, datapacks, resource packs, and shaders. You can also install mods from within prism launcher, and have them pull from modrinth's api. Its also really easy to make your own modpacks which you can just tell people to plug into prism for playing on your modded server.
#### [MCArchive](https://mcarchive.net/)
archives old minecraft mods and makes them easier to find, and keeps them publicly accessable even after creators delist or discontinue them. They only provide downloads to mods not available from their original source, else, they direct you to the original source.
## Performance and Optimization
####  [Fabulously Optimized](https://modrinth.com/modpack/fabulously-optimized) / [Adrenaline](https://modrinth.com/modpack/adrenaline) / [Vulkan Optimized](https://modrinth.com/modpack/vulkan-optimized)
> [!warning]- This section may be out of date
> This section was written around Spring 2025, and is highly subject to changing over time. 

- [Fabulously Optimized](https://modrinth.com/modpack/fabulously-optimized) is essentially a [drop-in replacement for optifine](https://wiki.download.fo/give-up-optifine). If you liked optifine for its bells and whistles like zoom, capes, resource pack features, etc., then go with FO. [Perforium](https://modrinth.com/modpack/performium-was-taken) also comes with many optifine features, but isn't a drop in replacement. It probably runs better on your system, so its worth checking out if you want a middle-ground there. Additive is ran by the adrenaline team and also acts as an optifine alternative, and even Vital which is an alternative to essential can act as an alternative to optifine. Point is: optifine should be dead, do not use it.
- [Vulkan Optimized](https://modrinth.com/modpack/vulkan-optimized) straight up replaces the entire OpenGL rendering engine with a Vulkan one using [VulkanMod](https://modrinth.com/mod/vulkanmod). You'll need a newer graphics card to take advantage, but on the correct hardware the performance gains are in their own league at normal render distances. I'd recommend a 64bit system with a GTX600 / Radeon HD 7000 or greater, as well as 8GB ram or more if you plan to use this mod. I know this makes it sound like its demanding, but if you meet the system requirements this pack will perform the best. In the future, this mod may also not be necessary since Mojang is planning on adding vulkan support in the future.
- [Adrenaline](https://modrinth.com/modpack/adrenaline) is, as far as i know, the most performant modpack (on average, at 18-22 chunks, that doesn't outright replace the rendering engine of the game like Vulkan Optimized does) at the time of writing. This said, [Simply Optimized](https://modrinth.com/modpack/sop) is a close second (less than 1% performance distance, within margin of error). Both do not include QoL mods.
- **tl;dr** Fabulously Optimized to replace optifine, Vulkan Optimized if your system can run it, Adrenaline if your system can't.
if you dont want to use a modpack, start with lithium and sodium at the very least, and then look at the mods used in the latest version of Adrenaline/Simply and go from there.
#### [Nvidium](https://modrinth.com/mod/nvidium) / [Distant Horizons](https://modrinth.com/mod/distanthorizons)
These throw a wrench in the recommended performance mods above, and i'm not sure what the best mods to pair these with would be. Perhaps just use Adrenaline as a base. Nevertheless,
- **Nvidium** is a replacement rendering backend for sodium that only supports Nvidia GPUs. Its main advantage is that the developer used black magic (mesh shaders) to allow for insane render distances. Like we're talking rendering all of hermitcraft season 8 at once. This mod does not use LoD. Its all rendered in real time, as fully loaded chunks.
- **Distant Horizons** on the other hand does use LoD (Level of Detail), which is a common technique used by most 3D games. Essentially, non-loaded chunks aren't loaded, and appear as simplified, fake terrain. Yes, this works with player made structures.
#### [Bobby](https://modrinth.com/mod/bobby)
Many servers force players to play with low render distances, since the server has to handle the chunks around a player. Bobby allows you to have view distances greater than what the server you're connecting to allows for. Basically, it caches chunks onto your system and loads them client side. Optionally, can also use a singleplayer world as a fallback if you've never loaded a given chunk on the server before, if you happen to have the server's seed.
Of course, in both these contexts bobby would leave you in the dark to any changes other players may have made to un-cached or out of date cached chunks.
Bobby does not cost the server any performance.
#### Custom Player Models
>[!warning] CPM needs link and description

- [Mario Skin Pack](https://ko-fi.com/Post/SUPER-MARIO-Minecraft-CPM-Skin-Pack-FREE-DOWNLO-F1F5WL0H5) Custom model skin pack for Super Mario characters. [trailer](https://www.youtube.com/watch?v=fy2re9YKYQM)
- [Mother/Earthbound Skin Pack](https://ko-fi.com/Post/MOTHER-1-2-SKIN-PACK-Minecraft-CPM-Skin-Pack-FR-U6U7158MER) Custom model skin pack for Mother characters. [trailer](https://www.youtube.com/watch?v=OF81QGA4iCk)
- [Mob Psycho 100 Skin Pack](https://ko-fi.com/Post/Mob-Psycho-100-Minecraft-CPM-Skin-Pack-FREE-DOW-R6R5YME0J) Custom model skin pack for Mob Psycho 100 characters. [trailer](https://www.youtube.com/watch?v=tUyT_TcLU2Y)
## Resource Packs
#### [Vanilla Tweaks](https://vanillatweaks.net/)
a bunch of very nice little texture tweaks to make minecraft just a tad better. As of 1.21.4 i use [this pack](https://vanillatweaks.net/share#Nd8Ew9) which is a cancellable direct download that'll show you which i have selected.
#### [Redstone Tweaks](https://modrinth.com/resourcepack/redstone-tweaks)
a bunch of very nice texture tweaks to redstone to improve conveyance. Vanilla Tweaks includes some, but redstone tweaks has much more. You're able to configure it with [ResPackOpts](https://modrinth.com/mod/respackopts)
#### [Visual Shulker Labels](https://ewanhowell.com/resourcepacks/visual-shulker-labels)
[Visual Shulker Labels 2D](https://ewanhowell.com/resourcepacks/visual-shulker-labels-2d-display) is recommended in addition for cleaner labels
Lets you name your shulkerbox to put an image of the named item on it. For example, you can name a shulkerbox "food and farm stuffs - Apple" to have it display an apple as its label.
Does not actually require optifine. See give up optifine on this page for more info.
#### [xali's Potions](https://modrinth.com/resourcepack/xalis-potions)
[xali's potions addon](https://modrinth.com/resourcepack/xalis-potions-addon) is recommended in addition for potions xali's original is missing
gives every potion a unique texture so that they can be visually told apart from one another
[Many alternatives exist](https://modrinth.com/resourcepacks?q=potion&s=downloads)
#### [xali's Enchanted Books](https://modrinth.com/resourcepack/xalis-enchanted-books)
gives every enchanted book a unique texture so that they can be visually told apart from one another
[Many alternatives exist](https://modrinth.com/resourcepacks?q=enchant&s=downloads)
#### [Visual Armor Trims](https://modrinth.com/resourcepack/visual-armor-trims)
gives every armor trim a unique texture, so you can tell trims apart.
#### [Mob Crates](https://modrinth.com/resourcepack/mob-crates)
"replaces" spawn eggs with spawn crates. Gives every mob spawn egg a unique texture that's easy to visually distinguish.
Note as of snapshot 25w08a mojang has overhauled mob egg sprites to be easy to visually distinguish, making this resource pack a bit redundant, but its useful in older versions i suppose.
## Data Packs
#### [Vanilla Tweaks](https://vanillatweaks.net/)
a bunch of very nice datapacks and crafting tweaks that make minecraft just a tad better. I use armor statues, name colors, silence mobs, more effective tools, spectator conduit power, spectator night vision, unlock all recipes, graves, spawning spheres, track (raw) statistics, workstation highlights, and sometimes double shulker shells if i'm feeling fancy. On the crafting tweaks side i use dropper to dispenser, universal dying, straight to shapeless, blackstone cobblestone, and unpackable ice.
#### [Mini Blocks](https://modrinth.com/datapack/mini-blocks-datapack)
More miniblocks than the VanillaTweek's datapack provides, uses their textures as well as textures from Minecraft Heads below. Throw a block into a stonecutter to get a "mini" version of the block (a playerhead textured to look like the block). Existing miniblocks should continue to work even if this datapack is removed from your world.
## Creative Tools
#### [Axiom](https://modrinth.com/mod/axiom/)
>[!warning] Axiom Description Needed
#### Block Blender
>[!warning] Block Blender link and description needed
## Shaders
all shaders besides complimentary + euphoria are just for fun
#### [Complimentary](https://www.complementary.dev/shaders/) + [Euphoria Patches](https://www.euphoriapatches.com/)
Complimentary is the most popular minecraft shader at the time of writing, and is required for euphoria. Euphoria basically just gives you more settings to further tweak it than what complimentary provides by default. My settings look little like default complimentary, as i'm trying to accomplish my interpretation of a "mojang" style shader. You can download my settings at the time of writing for import [here](https://files.catbox.moe/oij11y.txt), it should work in both reimagined and unbound, though i use reimagined. This is loosely based on demonjoeTV's settings if you'd like an approximation: [showcase](https://www.youtube.com/watch?v=N9WjsUZOYl8)
#### [Rudimentary](https://modrinth.com/shader/rudimentary-ps1) and [minecraft-psx](https://github.com/ckosmic/minecraft-psx)
two seperate cracks at making minecraft look like a playstation 1 game, with v-snapping, texture warping, and distance fog. Rudimentary also has a "horror mode" that looks fun, and minecraft-psx is used in the MCSX horror modpack below.
#### [PixelCraft](https://modrinth.com/shader/pixelcraft-shaders)
a complimentary shaders edit meant to make the game look like pixel art, sort of like the paintings. Check out the gallery. Cool for neat screenshots
#### [Epoch](https://modrinth.com/shader/epoch) and [MC VHS](https://modrinth.com/shader/mc-vhs)
Epoch is a vintage/low-fi emulating shader, and MC VHS is a shader meant to replicate the look of old VHS recordings. Both are neat for screenshots and the like.
#### [Acid Shaders](https://modrinth.com/shader/acidshaders15)
a fan-made remaster of the original acid shaders by mininggodbruce. Super cool. If you want an idea of what you'll get, mininggodbruce's music videos are a good place to start. here's [Subtlety by Topaz](https://www.youtube.com/watch?v=C1ZN_NRBWwI) as an example. Bruce is currently working on Acid Engine, which has yet to be released, but should prove to be even better than acid shaders. Note that Euphoria has an option for similar functionality under its "fun" tab.
## Modpacks
#### [Better Than Adventure](https://www.betterthanadventure.net/) a beta 1.7.3 continuation
Better Than Adventure is essentially an extensive fork of beta 1.7.3. It asks "what if mojang kept the game design sensibilities of beta, before the adventure update?" So sick. I highly recommend you check out their [trailers](https://www.youtube.com/@BetterthanAdventure/videos), starting from the release 1.7.7.0 trailer.
Mods and servers for BTA are available on their discord :T
#### [Raspberry Flavoured](https://www.curseforge.com/minecraft/modpacks/raspberry-flavoured)
My favorite modpack of all time, maybe the only one i've seen with its design as well thought out as it is, with as much attention to detail as it has. Intrinsically motivated players will thrive in this sandbox focused mod. Controversially, it removes villagers, the end, and xp. However the systems it replaces these mechanics with i think serve the game very, very well.
#### [Re-Console](https://modrinth.com/modpack/legacy-minecraft)
recreates the feeling of legacy console edition in java. Nice if you're nostalgic about xbox 360 edition like i am :)
Re-Console's pitch is "if legacy console edition never ended", so it still has features from newer versions of the game. [Re-Console: Legacy](https://github.com/ViolaFlower/Re-Console-Legacy) is meant to emulate the experience of legacy versions outright, without the new features, and is made by the same developer.
Re-console and re-console: legacy are modpacks using the [Legacy 4j](https://modrinth.com/mod/legacy4j) mod.
#### [MCSX](https://www.curseforge.com/minecraft/modpacks/mcsx-minecraft-ps1-edition)
a cute little horror/arg modpack that pretends its a cursed PlayStation 1 release of minecraft. Uses a modified version of the minecraft-psx shader above.
# Other
## Worlds / Minigames
#### [Skyblock (Standard)](https://modrinth.com/datapack/standard-skyblock)
Standard skyblock is exactly what it sounds like, the basic skyblock map you know, but with an infinite void. And yes, biomes and structure bounding boxes. Also very small starting nether/end islands. Standard benefits from other companion mods in their [collection](https://modrinth.com/collection/QcjV0vVX) for things like [advancements](https://modrinth.com/datapack/skyblock-advancements) and [making unobtainables obtainable](https://modrinth.com/datapack/sky-void-additions), as well as the [vanilla one block](https://modrinth.com/datapack/xb16810H) challenge.
#### [Legacy Console Edition Tutorial World Collection](https://www.curseforge.com/minecraft/worlds/tutorial-world-collection)
a collection of every tutorial world from legacy console edition. Minigame maps are also available at both sources.
#### [Minecraft 10th Anniversary Map](https://www.minecraft.net/en-us/article/get-your-free-anniversary-map)
a minecraft map by blockworks commissioned by mojang to celebrate the game's 10th anniversary. i had a lot of fun with this when it came out, and its quite pretty. [wiki](https://minecraft.wiki/w/10_Years_of_Minecraft)
There's also two official maps for Minecraft's 15th anniversary, but i haven't tried them. [15 year journey (wiki)](https://minecraft.wiki/w/15_Year_Journey) is the officially commissioned one and is bedrock exclusive, and [java multiplayer madness](https://www.minecraft.net/en-us/article/java-multiplayer-madness) is meant to specifically celebrate minecraft java realm's 10th anniversary, and is a collaboration between 100+ volunteer map makers. Though you can download the map for use outside of realms no problem
#### [The Uncensored Library](https://uncensoredlibrary.com)
a map made by blockworks commissioned by Reporters Without Borders which is meant to be a novel means to deliver important often censored journalism via loophole and educate the minecraft playing youth on the importance of uncensored journalistic integrity. Updated in 2021. Really cool and novel. [making of trailer](https://www.youtube.com/watch?v=vFKvjEV6muc)
IP: `visit.uncensoredlibrary.com`
#### [Tunnel Rats](https://xisumavoid.com/tunnelrats/)
Tunnel Rats is a minigame designed by the original creator of bedwars (xisumavoid), and its honestly more interesting than bedwars to me. 
Underground, two teams dig through symmetrical terrain towards each other, collecting materials and meeting in the middle for a pvp skirmish a bit of the ways into the game. Destroy the other teams bed then kill them all to win. Tons of variance and cool stuff is possible with the level editor, but many maps are packaged in by default as well.
You could even build a map for disposable use in survival if you wanted, which is actually how xisuma first designed the game. Available for java for free as well as the marketplace. [trailer](https://www.youtube.com/watch?v=ECf2Fm649k8), [gameplay showcase](https://www.youtube.com/watch?v=XRWnIuNew2w), [level editor tutorial/showcase](https://www.youtube.com/watch?v=tALmU9GaWRY)
#### [EarthMC](https://earthmc.net/download)
a recreation of earth as a 1:500 scale minecraft map. There's two versions available for download, and the third version is only playable on their server.
#### [Yet Another Bingo / Lockout](https://modrinth.com/mod/yet-another-minecraft-bingo)
>[!warning] needs description
#### [Five Nights at Freddy's in Minecraft](https://www.planetminecraft.com/project/1-17-five-nights-at-freddy-s/) / [FNAF 2](https://www.planetminecraft.com/project/fnaf-2-6052044/) / [FNAF 3](https://www.planetminecraft.com/project/fnaf-3-miramappa/) / [FNAF 4](https://www.planetminecraft.com/project/fnaf-4-miramappa/)
>[!warning] needs description
#### [MCKart 2](https://mckart.skyblocksquad.de/)
IP: `skyblocksquad.de`
>[!warning] needs description
#### [World in a Jar Remastered](https://www.planetminecraft.com/project/world-in-a-jar-3-fanmade/)
>[!warning] needs description
#### [Kitatcho Labs Chapter 3](https://www.minecraftmaps.com/49957-the-kitatcho-laboratories-chapter-3)
>[!warning] needs description
#### [Evergrowth](https://gm4.co/evergrowth/)
[trailer](https://youtu.be/fkBs9pX8sQo)
>[!warning] needs description
#### [WiiParty Plus](https://www.planetminecraft.com/project/wii-party-in-minecraft-6519651/)
WiiParty re-created in minecraft, super impressive. [trailer](https://youtu.be/o0kxHLr_Swc?si=NQpG_pKL60vw84TC)
they also have an official server, but its a public lobby `wiiparty.spmc.co`
#### [Warioware in Minecraft](https://www.planetminecraft.com/project/warioware-inc-in-minecraft/)
>[!warning] needs description
## Servers
#### Self Host: [Minecraft Docker Server](https://docker-minecraft-server.readthedocs.io/en/latest/)
[setupmc.com](https://setupmc.com/java-server/) can be used to help build a docker server compose script, which is what i use :)
This is way easier than it sounds, but if you really dont want to do the setup yourself then consult the chart for a minecraft server host: [Minecraft Dedicated Server Host Testing Data by CygnusMC](https://docs.google.com/spreadsheets/d/1HZE7Pi6FPEhbN-JQtXKX69Udp6dA5OBOu4Kpdzz53MI)
you can use a generic [VPS](https://vpspricetracker.com/), but best practice is to use a minecraft host since their hardware is chosen specifically for the game, and you'll get better price to performance that way.
#### Automatic Multiplayer Mods:
##### [Vital](https://usevital.github.io/) (Essential alternative)
Vital is an alternative to the [kinda scummy](https://notessential.blurry.gay/#why-not?) Essential-mod and Optifine as well. Vital simply bundles the suggestions made in NotEssential into a modpack.
##### [World Host](https://modrinth.com/mod/world-host)
This is what vital uses for multiplayer, and has a friends system. UPnP mode is tried first. Your client tries to open a temporary port forward in your router that your friends client can use to connect to you directly. If UPnP fails, then your client tells the server to use Proxy mode. The server will then give your friend's client the same "proxy IP" as `/worldhost ip` does.
##### [e4mc](https://modrinth.com/project/qANg5Jrr)
similar to World Host but is better for heavily modded instances. e4mc is a reverse tunneling reverse proxy for Minecraft. In simpler terms, it's a software that allows you to temporarily expose a local Minecraft server to the internet. Make sure your mod lists are identical so you dont desync!
#### Server List Sites
generally speaking you'll find higher quality, more interesting servers via personal recommendation, youtube showcases, from patreon whitelisted servers from your fav content creators, or in your existing community's minecraft server, but server lists like these still provide some value, so:
- [The Official Minecraft Server List](https://findmcserver.com/)
	something not many people know exists, but it does. Licensed and affiliated with mojang, by gamersafer. Its pretty heavily moderated and squeaky clean, but y'know, its a place to start.
- [NameMC](https://namemc.com/minecraft-servers)
	as far as i know, NameMC literally just keeps a list of every server they come across and lists them by a mix of playercount and likes. Their primary thing is keeping track of players and their skins, so they haven't started taking money for higher listings or whatever... yet. Also there's not a ton of annoying animations and banners.
#### [Minecraft Speedrunning Ranked](https://mcsrranked.com/)
MCSR Ranked is a ranked speedrunning server giving each player an ELO score to determine matchmaking. In a game, two players are placed on copies of the same curated seed. First player to defeat the dragon and exit the end wins. You have to use their client to connect, so download that in your favorite launcher from the above link.
	[MinecraftSpeedrunning.com](https://www.minecraftspeedrunning.com/home)
	website compiling useful resources for minecraft speedrunning. Tools, maps for practice, information and resources, etc.
	[MCSR Practice Map](https://github.com/Dibedy/The-MCSR-Practice-Map)/ [MiniPracticeKit](https://github.com/Knawk/mc-MiniPracticeKit)
	Practice map that combines all important practices into one map. the next is a set of command block kits you can save to your creative menu to automatically create drills in a new world, i recommend setting these up for use in singleplayer worlds in your MCSR client :3
#### [Modern Beta](https://modernbeta.org)
a recreation of beta 1.7.3, playable from modern minecraft versions. Works with both modern java and bedrock if you connect with the play IP, and you can connect with a b1.7.3 client by using the beta IP
IP: `play.modernbeta.org` / `beta.modernbeta.org`
#### [MinecraftOnline](https://minecraftonline.com) / [Novylen](https://minecraft.novylen.net/)
These are the oldest surviving minecraft servers that have yet to go through a map reset. Both were started the day that survival multiplayer launched and are the only two surviving servers. Lots of history in both of these
I'm more familiar with MCOnline, which in my opinion is laggy and a tad mismanaged. They also have a weird free speech absolutism thing going on, so bleh.
Novylen also uses protect plugins, rather than just banning people whom happen to grief, which is more annoying in my opinion.
Pick your poison i suppose!
These are cool to explore, idk about playing on them as much, though.
IP: `minecraftonline.com` / `mc.novylen.net`
#### [FishOnMC](https://fishonmc.net)
wtf minecraft fishing simulator 300+ fish fishing simulator scientifically accurate fish data unique fishing mechanics different locations in the world fishing in minecraft??
how the hell do i find more unique cool and original servers like this
if you're a sweat, [FishOnTools](https://dannypx.github.io/FishOnTools/) and the [FishOnMC wiki](wiki.fishonmc.net) may prove useful
IP: `play.fishonmc.net`
#### [Library of Babel](https://doteye.online/projects/mclob/)
The [library of babel](https://libraryofbabel.info/) (inspired by the [short story](https://archive.org/details/TheLibraryOfBabel)), playable in minecraft. A direct download for the library of babel would be ~400 petabytes large, so you have to either join on the server or host the custom server software yourself to explore.
IP: `mclob.doteye.online`
#### Combat Reforged / CombatEnhanced.fun / nanexia \[all dead?]
From around mid 2019 to late 2020, jeb would sometimes post to reddit experimental combat snapshots which radically changed combat systems in the game significantly. here's a showcase of what the combat is like. These are servers for the Combat Test Snapshot (CTS) community. 
>[!warning] showcase still needed. all these servers might be dead?
#### Seemingly Best of Genre
i've done light research into each of these, but dont play them all. These are mostly my first instinct if i want to play these types of game modes for a bit. if you have suggestions or any of these seem wrong, say as much in the discussion page please!
- SMP / Factions: [OG Network](https://www.og-network.net/)
	The pitch is that its meant to be the go-to basic gamemodes like SMP and Factions and such. PvP / Griefing is allowed. SMP has a player run marketplace, etc.
	Griefing in SMP is lightly discouraged with a reputation system. You can give players + or - rep which everyone can see, but else its just allowed.  enough - rep takes away /tpa, /spawn, etc. at -15 rep everyone can see your position at all times. Pretty neat.
	They also have og survival games but it doesn't seem like anyone plays it, which is a shame because that's probably the only place where getting a game going is possible. I'd like to see them add skyblock personally.
	Its ran by a [slop YouTuber](https://www.youtube.com/@TheMisterEpic), but one of those that has made a lot of videos duping on pay-to-win lootcrate servers and is sort of immersed in that sort of part-dirtbag part gaming-needs-to-do-better cultures, so the bullshit is very minimum and he seems to care about making a good server.
	IP: `og-network.net`
	Else, just join your friend's server for SMP lol. Or maybe your favorite creator's patreon or something idk.
- Anarchy: [2b2t.org](https://2b2t.org) / [Constantiam](https://constantiam.net) 
	2b2t is "the oldest anarchy server in minecraft", recently updated to more modern versions after being stuck on 1.12 for forever. Lots of documentaries about the server on youtube and such, though they're all a bit overly serious and melodramatic. Regardless, its neat.
	if the queue is long for you, constantiam is probably the best alternative. A lot of 2b2t veterans fled here around 2016. Its the oldest alternative at 9 years old, and was the first notable anarchy server to upgrade from 1.12
	of course, both servers have 4chan and adjacent culture. Comes with the territory. That said, Constantiam's culture isn't quite like 2b's, and that's by design. Don't just go griefing everything you see. Like, you can, just don't be a dweeb about it.
	IP: `2b2t.org` / `constantiam.net`
	- if you want a museum of projects built on 2b2t and Constantiam, there's an unofficial museum server at the IP `thearchive.world`
- Battle Royale / Survival Games / Hunger Games: [Hoplite](https://hoplite.gg/)
	To be quite honest, more interesting than any oldschool hunger games ever was. Its sort of its own thing with custom weapons and such, but the vanilla game is certainly still in here. [Rekrap's Hoplite videos](https://www.youtube.com/@rekrap1/search?query=hoplite) will give you an idea on how the server plays.
	IP: `hoplite.gg`
- PvP: [PvP Legacy](https://pvplegacy.net/)
	this is the primary server I've been told about for PvP. You can make custom kits and fight players in an arena with those kits
	IP: `play.pvplegacy.net`
- Parkour: [CyloneMC](https://CyloneMC.net)
	this is that parkour server you see in all the ai slop vids on your fyp. Players can build their own parkour maps then add them to the public database, and a speedrunning leaderboard is maintained, so there's hundreds of parkour maps for every skill level. Its nice.
	IP: `mc.cylonemc.net` 
- Skyblock: [Skyblock.net](https://skyblock.net)
	This one i'm not so sure about, but it is owned by NoobCrew, the original designer of the gamemode. So i guess it has that going for it, despite everything else going on in the server and how [litigious about their copyright](https://skyblock.net/threads/skyblock-and-the-minecraft-marketplace-a-legal-battle.145369/) they are.
	IP: `skyblock.net`
- MMO: [Wynncraft](https://wynncraft.com) / [Monumenta](https://playmonumenta.com) / [Megido Abyss](https://medigo.xyz)
	- Wynncraft is probably Minecraft's largest MMO project next to hypixel skyblock, and is the original. Very visually impressive, cool spell systems, custom resource pack. Its been in development for over a decade and it shows. Very nias.
	  IP: `play.wynncraft.com`
	- Monumenta stays closer to vanilla mechanics and goes in a dungeon crawler direction. One dungeon of note is Darkest Depths, which is procedurally generated dungeon that wipes your character and gives you abilities only for this one dungeon over the course of the run... yes... its a roguelike. its neat. Regions in architect 3 are also so pretty.
	  IP: `server.playmonumenta.com`
	- Megido Abyss is another MMO server, but this one has souls-like combat. Perries, dodging, bosses. y'know how it be. Unfortunately, the player count is quite low.
	  IP: `play.medigo.xyz`
- Hypixel Competitor 1: [CubeCraft](https://cubecraft.net)
	probably hypixel's #1 competitor thanks to its presence on the bedrock featured servers list. The bedrock server is more popular, but the java server is plenty active. Some argue that hypixel bedwars ripped off cubecraft eggwars swag
	IP: `play.cubecraft.net`
- Hypixel Competitor 2: [MC Championship Island](https://mcchampionship.com/island/)
	Minecraft Championship's public half, actually play the minecraft championship minigames from those tournaments
	IP: `play.mccisland.net`
- Manhunt: [MC Manhunt](https://mcmanhunt.com)
	There's also deathswap and random item challenges. Its neat.
	IP: `mcmanhunt.com`
## Websites and tools
#### [Official Minecraft Wiki](https://minecraft.wiki/)
Recently the Minecraft Wiki has moved from fandom to minecraft.wiki, support them so they move up in search results. Not to mention that the old fandom wiki is now falling apart due to poor maintenance :)
You can use the bang `!mcw` in DuckDuckGo to search the wiki, or use [[Customization#[Indie Wiki Buddy](https //getindie.wiki/)|Indie Wiki Buddy]] to auto redirect from fandom
#### [Totem Generator](https://skinmc.net/totem)
cute tool to automatically generate a totem based on your skin
#### [Minecraft Heads](https://minecraft-heads.com/)
Minecraft has a feature that lets you load in player heads as a block, this is a database of player heads that make for good decorative blocks. On each head's page, a command is provided to add the head to your in-game inventory without mods, which will work so long as you have op permissions on a cheats enabled world. If you want a good way to get some in survival, check out Vanilla Tweaks and Mini Blocks above. [freshcoal](https://freshcoal.com/maincollection.php) also has a heads collection which may prove useful.
#### [Need Cooler Shoes Skin Editor](https://needcoolershoes.com)
This is the best skin editor i know of. they also have a [banner editor](https://needcoolershoes.com/banner)
(though a lot of people use [Planet Minecraft's Skin Editor](https://www.planetminecraft.com/skin-editor/) and [banner editor](https://www.planetminecraft.com/banner/))
#### [blockcolors.app](https://blockcolors.app/) / [blockpalette.com](https://www.blockpalettes.com)
tools that makes it really easy to create a simple block palette for your next build.
#### [plotz](https://www.plotz.co.uk/)
easily generate shapes like spheres, circles, and more with voxels. Also makes it easy to copy off of for survival building.
#### [Buildpaste](https://buildpaste.net/)
a database of minecraft structure files for pasting into your minecraft world or building with litematica ^^
#### [MCSeed Map](https://mcseedmap.net/)
lets you hunt for a seed meeting your specified parameters
#### [Gneiss' 1.21 Color World](https://www.youtube.com/watch?v=bQ_dgs02zoc)
interactive minecraft world that displays blocks based on their texture color. This is good for pallettes, gradients, and seeing relationships between block colors. 
#### [MapArtCraft](https://rebane2001.com/mapartcraft/) / [mc wiki: map item format](https://minecraft.wiki/w/Map_item_format#Map_pixel_art)
easily generate minecraft map art from image. The minecraft wiki article also has a table for pixel color values with their correlating blocks, if you wanted to manually draw pixel art in a program like [[Hardware and Software#[Aseprite](https //github.com/aseprite/aseprite)|Aseprite]]. Map art is 128×128px. I also recommend checking the faq on mapartcraft
#### [minecraftart](https://minecraftart.netlify.app/)
does something similar, but for those billboarded pixel art images.
#### [MCStacker](https://mcstacker.net/)
gui for generating minecraft commands. [minecraftjson.com](https://www.minecraftjson.com/) is good for `/tellraw` commands. [r/minecraftcommands resources](https://www.reddit.com/r/MinecraftCommands/wiki/resources/) is also a good place to go if you're interested in this sort of thing.
#### [web nbt editor](https://irath96.github.io/webNBT/)
lets you view and edit nbt data in your browser
#### [mcutils](https://mcutils.com/)
far from perfect. In fact its quite flawed, but its still useful for things like creating fireworks, banners, gradients etc. [1280px's hueblocks](https://1280px.github.io/hueblocks/) can also be used for block gradients
#### [A Minecraft Timeline](https://minecraft-timeline.github.io/)
can't remember what minecraft version you first played, or what update added what? Use this. Has timelines for java and bedrock (pocket edition). My first version i remember playing was java release 1.2 :3
for legacy console editions (pre better together update), see [here](https://minecraft.wiki/w/Legacy_Console_Edition_version_history)
#### [Blockbench](https://web.blockbench.net)
>[!warning] needs description

also notable is their [title generator](https://web.blockbench.net/?plugins=minecraft_title_generator)
## Misc.
#### [Minecraft Game Design by Jeb](https://archive.org/details/minecraft-game-design/mode/1up)
During the 2020 Minecraft Live, Jeb shared a book he wrote for mojang staff detailing a couple of his axioms for minecraft. It wasn't supposed to be public, but due to swedish law shenanigans it had to be added to a library, meaning it could be rented, meaning it could be preserved online. The above link lets you read it on Archive.org :)
#### Snapshot/update coverage [xisumavoid](https://www.youtube.com/playlist?list=PL7VmhWGNRxKixIX8tWEQn-BnYKE9AaAXk), [slicedlime](https://www.youtube.com/@slicedlime/videos)
Xisumavoid and slicedlime both have their own running series which cover new minecraft snapshots in a timely fashion so you can keep up to date on game changes, and they both also post a recap covering all the new changes and additions for major releases. Xisuma has nice thumbnails and editing, slicedlime is the java edition tech lead. pick your poison.