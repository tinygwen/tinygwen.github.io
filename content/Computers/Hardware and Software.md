---
title: 🖥️ Hardware and Software
description: Program, browser, search engine, and operating system recommendations. With a dash of hardware resources.
---
# Hardware
>[!tip]- Enterprise Liquidation
>When companies upgrade their hardware (say laptops, chairs), they often flood the second-hand market with whatever particular model they bought in bulk, and at extremely cheap prices. A laptop can be 4 years old and be worth 3000 when it released and sell for 300. Same for chairs, etc.
>Snoop local auction sites and you may be be surprised at what you find.
#### [LTT PC Building Guide (2024)](https://youtu.be/s1fxZ-VWs2U)
a sort of "choose your own adventure" style mega-video as a PC building guide, use youtube chapters to learn about whatever specific part you're interested in, or just watch the whole thing if you're starting from scratch.
#### [PC Master Race Explained in 9 minutes](https://www.youtube.com/watch?v=RRY1jrIDhvU)
an incredibly entertaining animation styled to look like it was made in flipnote studio. Talks about the pros and cons of buying phones, laptops, gaming laptops, pre-built PCs, and custom-built PCs. Also talks a bit about right to repair. Highly recommend you give this a watch if you're in the market for a new device or care about computers at all.
>[!tip] This video is also available in **[Japanese](https://www.youtube.com/watch?v=AKKBuCinOKM), [Mandarin](https://www.youtube.com/watch?v=-MgOV6BQnl8), [Russian](https://www.youtube.com/watch?v=fFsJU7CKP-I), [Korean](https://www.youtube.com/watch?v=q4heFXEaZ0g)**, and **[Cantonese (incomplete)](https://www.youtube.com/watch?v=8sMxMID96gM)**.
#### [PC Part Picker](https://pcpartpicker.com/)
a site that pulls from a number of part distributors which helps you to create a pc build of parts that are compatible with one another. Compare different parts (both in terms of price and performance), share your hypothetical build for feedback, etc.
# Software
## Programs
#### 🌟 [AlternativeTo](https://alternativeto.net/)
You've probably used AlternativeTo before, but it really is just good for finding software for any particular case, and comparing pieces of software against eachother. Their filters are very strong, and it lets you compare programs against eachother. I like to filter by Linux and Open Source.
#### 🌟 [qBitTorrent](https://www.qbittorrent.org/)
Torrenting client. One of the very few that are worth a damn imo.
#### [NewPipe](https://newpipe.net/)
A FOSS mobile app that lets you watch YouTube on your phone without signing in to Google. 
It also allows you to download videos, listen to them in the background, skip ads, and skip sponsored segments. Basically everything YouTube Premium offers and more. 
Also supports bandcamp and soundcloud for music streaming. 
Admittedly, it breaks a lot. I've added the download page to my app drawer as a PWA for easy access to the latest .apk for when it does break, though.
#### [ReVanced](https://revanced.app/)
A manager to apply mods to various android apps. Especially useful to remove ads on apps like YouTube. 
Most people prefer this over NewPipe since it lets you use the actual YouTube app (or any other apps it modifies).
#### [youtube-dlp](https://github.com/yt-dlp/yt-dlp)
Command line program for downloading vids from youtube and [others](https://ytdl-org.github.io/youtube-dl/supportedsites.html). Use this if you just want the command line utility and dont want the gui that tartube provides. If you dont know what this means, get tartube.
#### [Tartube](https://tartube.sourceforge.io/)
a gui frontend for yt-dlp and others. Basically, it's a video downloader. Never search "youtube mp3 converter" or "youtube downloader" again. Supports more sites than just YouTube. Also downloads mp3s and thumbnails. Be sure to use yt-dlp in tartube
#### [cobalt.tools](https://cobalt.tools)
site that lets you download media from youtube, twitter, twitch, tiktok, reddit, instagram, snapchat, facebook, tumblr, and more and more and more. Just paste the link in and you're off. It's also open-source, so you can host your own instances by pulling from their [github](https://github.com/imputnet/cobalt)
#### [Alpaca](https://jeffser.com/alpaca/)
an Ollama client which lets you run source-available large language models (AI) locally. These have no connection to the internet, so you can use your gaming PC instead of boiling water in some server farm somewhere so some suit can farm your personal data. The latest version of Llama is usually on par with chatgpt at the time of writing.
#### [JDownloader](https://jdownloader.org/)
Download manager. Scrape websites, read the clipboard for links to downloads, etc. Have them all in a neat list. Especially useful for archive.org collections or for when you have a slow internet connection.
#### [Handbrake](https://handbrake.fr/)
Video transcoder. Compress, convert, etc. Throw videos in and choose which format you want and watch the file size shrink.
#### [ShareX](https://getsharex.com/)
Best screenshot software there is. Still sad there isn't a linux version.
#### [Open Broadcast Software (OBS)](https://obsproject.com/)
Best video recording, screen recording, and streaming software there is. Pretty self-explanatory.
#### 🌟 [Davincibox](https://github.com/zelikos/davincibox/) ([DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve))
an unofficial DaVinci Resolve Linux installer. DaVinci Resolve is natively supported on linux, but only really for Rocky Linux for some reason. This sets up a distrobox instance that'll have DaVinci running as if it's a native application on any distro!
DaVinci resolve is in my opinion the only video editor that's a viable alternative to adobe premiere for most editing heavy usecases. If you just need to cut a few things many other video editors will be fine, though.
#### 🌟 [Photopea](https://www.photopea.com/)
A free "remake" of Adobe Photoshop in browser. Doesn't upload files to the cloud, and works better than it has any right to. Use [Photopea Adblock](https://greasyfork.org/en/scripts/422431-anti-anti-adblock-on-photopea-com) as well (i had to change the value in the script to 320). uBlock already blocks ads on photopea, but the space is still reserved for the ad. Using this will fill the whole screen and remove the adspace. This is a [userscript](#userscripts).
#### 🌟 [Obsidian.md](https://obsidian.md/)
<<<<<<< Updated upstream
writing/note taking app that stores all documents you make in human-readable markdown. You can use community plugins (built in plugin store)to store your vault to the cloud. The content of this site is actually written in obsidian and deployed with [Quartz](https://quartz.jzhao.xyz/). [Recommendation video](https://www.youtube.com/watch?v=DbsAQSIKQXk)
=======
writing/note taking app that stores all documents you make in human-readable markdown. You can use community plugins (built in plugin store)to store your vault to the cloud. The content of this site is actually written in obsidian and deployed with [Quartz](https://quartz.jzhao.xyz/). 
[Recommendation video](https://www.youtube.com/watch?v=DbsAQSIKQXk)
- [LogSeq](https://logseq.com/) is an open source alternative to Obsidian, though I have yet to try it personally. Unless you have a particular use-case that would cause you to prefer one over the other, just choose one and start working.
#### 🌟 [Photopea](https://www.photopea.com/)
a free "remake" of Adobe Photoshop in browser. Doesn't upload files to the cloud, and works better than it has any right to. Use [Photopea Adblock](https://greasyfork.org/en/scripts/422431-anti-anti-adblock-on-photopea-com) as well (i had to change the value in the script to 320). uBlock already blocks ads on photopea, but the space is still reserved for the ad. Using this will fill the whole screen and remove the adspace. This is a [userscript](#userscripts).
#### [Excalidraw](https://excalidraw.com/)
online whiteboard, great for what you would use a whiteboard for, but online. Lets you easily draw diagrams with a bunch of easy to use tools, and lets you collaborate by sharing your whiteboard as a link, and just generally brainstorm. The fonts and lines are beautiful. I like it a lot more than using mspaint and discord's whiteboard app, or anything similar. If i had a drawing tablet, maybe even more than a real whiteboard. Infinite canvas, dark mode, and more. Oh, and its FOSS and E2EE.
>>>>>>> Stashed changes
#### [Kommiku](https://flathub.org/apps/info.febvre.Komikku)
a nice manga/comic reader i like, made with Adwaita theming for GNOME. Comes with pirate comic/manga repositories built in, somehow. Not to be confused with the android app of the same name, its a different project.
#### [List of Adobe Alternatives](https://twitter.com/XdanielArt/status/1434611199140896772)
Sick list of alternatives to adobe suite software. Useful for linux or if you just hate adobe (But, of course, pirating their software will always be moral :P )
#### [Aseprite](https://github.com/aseprite/aseprite)
([official website](https://www.aseprite.org/), [linux compile script (dnf/apt)](https://github.com/mak448a/compile-aseprite-linux))
A pixel art illustration program loved by both hobbyists and professionals. Fun fact many don't know about aseprite, it uses a license which is sort of adjacent to open-source software. They charge for it, but their license actually permits compiling aseprite from source for free for both personal AND commercial use. The only limitation is that you're not allowed to re-distribute a compiled aseprite (so not open-source... but anyways). I link it here to encourage you to compile it from source so you can use it for free, legally, even in art you intend to sell :)
## Web Browsers
>[!warning]- Anti-Recommendations
> edge, google chrome, and opera browsers like gx or zen are all shady as hell [and only good for one thing](https://www.youtube.com/watch?v=IXhmu1aQSOY) (and equivalent to each other in their shittyness, do not fool yourself).
>There's no reason to use any of these when the alternatives below exist. If you're using any of these, its quite easy to export bookmarks, passwords, etc and import data into a new browser.
> Safari (webkit) is okay... All browsers on ios are actually forced to be webkit based, so heads up on that. Apparently [Orion](https://kagi.com/orion/) is an okay webkit based browser that can use chrome and firefox extensions, but they have yet to open-source it at the time of writing as they had promised.

> [!note]- I primarily recommend "mainstream" browsers
  at least as daily drivers. You need to trust that security updates (or updates in general) will be delivered in a timely and stable manner. The less niche and more users, the better. Venture out if you wish, just know the risks. 
#### 🌟 [Firefox](https://www.mozilla.org/en-US/firefox/new/)
Unlike (virtually) every other browser under the sun, firefox is Gecko based, not Chromium based. Supports virtually all standard features you'd expect from a web-browser and a few others. Supports manifest v2 extensions, and even many extensions on its mobile app, too. However, Firefox does not support Progressive Web Apps (PWA). You can use extensions for this, but idk, i think that's lame as hell
>[!warning]- **Please** [**Harden Firefox and disable bloat**](https://www.privacyguides.org/en/desktop-browsers/#firefox)
>Oh, and If you want an easier alternative to arkenfox, try [Betterfox](https://github.com/yokoffing/BetterFox)
>its supposedly easier than Arkenfox, but i'm not sure its as legitimate or respected. If you can handle arkenfox, please use it. But betterfox is almost certainly better than using neither.
>If you want to go to a step further, the archwiki has a [firefox tweaks](https://wiki.archlinux.org/title/Firefox/Tweaks) article

>[!tip]- Customize the look of Firefox with the [FirefoxCSS Store](https://firefoxcss-store.github.io/) 
>Don't like how firefox looks? Want to theme it to be minimal, look like chrome, opera gx, edge, or any number of other looks? You can use other people's css scripts, or make one yourself if you know or are willing to write some css. You may also want to check out [r/FirefoxCSS](https://www.reddit.com/r/FirefoxCSS) if this seems interesting to you, since the store is just a collection someone curated.

>[!tip]- More Gecko based browsers
>There's a lot of good alternative community maintained browsers out there, though i dont quite trust their teams as much to be able to deliver security updates as fast as mozilla can, but I'd still like to share them if you know what you're getting into.
>- [Librewolf](https://librewolf.net/) is basically the de-facto privacy respecting daily driver if you dont want to harden firefox. "unmozilla'd firefox", if you will. **does not have automatic updates without an external package manager** (on windows you can click the checkbox in the component selection on install for auto-updates).
>- [Floorp](https://floorp.app/en) has been popular in some spaces for having okay privacy defaults, being highly customizable, and having good performance, as well as supporting PWA out of the box. [showcase](https://www.youtube.com/watch?v=6OUjWdAtGbs). [Firedragon](https://github.com/dr460nf1r3/firedragon-browser) is a fork that uses KDE integration patches and custom branding for Garuda
>- [Zen Browser](https://zen-browser.app/) a very clean looking browser with a large focus on vertical tabs and okay privacy defaults.
>- [Mercury](https://thorium.rocks/mercury) is the gecko-based sideproject from the [thorium](https://thorium.rocks/) developers. I dont recommend you use them as they're basically never up to date (a big problem in terms of security), but if you're looking for speed above all, these two are interesting.
#### 🌟 [Brave Browser](https://brave.com/)
If you want to have a chromium based browser, brave is the only one I really like. Unlike firefox, it's generally privacy respecting out of the box. Comes with Brave Shields, which is a built in ad/tracker blocker, but also supports ublock origin as an alternative, unlike most other chromium browsers. There's a bunch of side features too, but the only one i really like is speedreader.
>[!warning]- **Please** [**Configure**](https://www.privacyguides.org/en/desktop-browsers/#brave) and [**Debloat**](https://www.youtube.com/watch?v=W6cKFliWW6Q) Brave
> The Privacy Guides link above will guide you through improving the privacy/security of brave. Additionally, disable "brave rewards" and their other crypto bullshit on install. 

>[!warning]- You will have compromised anonymity when accessing .onion domains
> Brave is not as resistant to fingerprinting as Tor, and far fewer people browse the Tor network with Brave than with Tor, so you will stand out. So please do not use brave to surf Tor if your threat model requires strong anonymity.

>[!info]- Brave supports uBlock Origin, despite being chromium based
>Brave has uBO baked into it, so if you prefer uBO over brave shields, disable brave shields and go to Settings > Extensions > Manifest v2 extensions > Enable uBlock Origin
#### 🌟 [Mullvad Browser](https://mullvad.net/en/browser)
Mullvad browser is a firefox/tor-based browser, and is a collaboration between Mullvad and the Tor Project. Basically, the idea is tor, but instead of using the tor network, it uses a VPN. You probably ought to use the same etiquette as you do with tor. Don't do anything that'd make your browser stand out, sign in to any accounts, etc. But its good if you're just websurfing and aren't, say, logging into your bank or anything that could identify you. Tor is better if you really want to make sure you're anonymous
#### [Tor Browser](https://www.torproject.org/download/)
A firefox based browser that helps to anonymize you. Ideally, makes your browser look the same as all other Tor users, which makes it very hard to distinguish between users. Do not modify any defaults. Read about [proper etiquette](https://tb-manual.torproject.org/) or else it'll be useless. Allows you to access .onion domains. Numberphile has a [great video](https://www.youtube.com/watch?v=QRYzre4bf7I) about the technical details of how the tor network helps to keeps you anonymous. Also, it's gonna be slow.
>[!danger]- Do not use Tor with a VPN. Do not daily drive. Do not install any extensions*
> except maybe ublock origin (a common... enough... install to make it okay... probably).

>[!tip] Check out Tails under Operating Systems below **[[Hardware and Software#Desktop Operating Systems|(jump)]]** if you're interested in a private/secure/anonymous temporary operating system
## Search Engines
I recommend just adding all of these engines as [search shortcuts](https://support.mozilla.org/en-US/kb/assign-shortcuts-search-engines) to be honest, though you could always use bangs in ddg/brave/kagi.
#### 🌟 [DuckDuckGo](duckduckgo.com)
My daily driver; usually gets the job done. Search results are sourced bing, but unlike bing it's good about user privacy. Bing results aren't as bad as they're meme'd to be. Also uses [bangs](https://duckduckgo.com/bangs), which lets you search other sites (ex `!w` for wikipedia). Very useful.
#### [Kagi](https://kagi.com/)
is a search engine that is funded by a paid-subscription model. They're good about user privacy. They source their results from a number of other engines, including some indexing they've done themselves. Kagi supports bangs (and lets you add your own), and their results are very high quality. You can have kagi automatically summarize an article, which will have AI give you a tl;dr of it's contents. My favorite feature from kagi are their [lenses](https://www.youtube.com/watch?v=ho9J6OKMxR8), which let you change the "type" of search results you get. Maybe instead of getting listicles, you want actual user discussion. Maybe you're looking for recipes specifically, or you're troubleshooting your code, etc. There's even a "small web" lens, which will highlight indie sites. It also lets you create your own lens, if that's up your alley. You can also promote or demote a site for your future searches, or block them entirely (get fucked fandom). Give their free trial a shot. It's premium quality, but it comes at a premium cost. It's priced at $10/mo (or $108/yr) for unlimited searching. They also offer family plans if you want to try and throw in together with the homies.
#### [Brave Search](https://search.brave.com/)
From the guys that made the web browser. Brave's biggest advantage in addition to being privacy respecting is that they have an independent search index. This means they source their searches themselves, and they dont rely Bing or Google. The results are better than you'd expect them to be. So if you want to resist big tech monopoly, this is probably the engine you want to go to. Also supports bangs, like ddg does.
#### [SearX](https://searx.space/)
SearX is a bit different in that it's open source and decentralized. This means that no one can really own SearX, and everyone knows exactly how it works. kind of like Mastodon if you're familiar with that. Privacy respecting, but you have to trust the host you're using, which can generally be done by making sure they're running vanilla. You could also disable javascript if you want to be extra sure you're searching privately. You can even host it yourself if you want to go the extra mile. It aggregates from a number of other engines and sort of mixes them all together and sorts based on relevance. You can select what search engines it pulls from in it's settings, which will effect response times. Super neat. Oh, and it also has an anonymous page viewer if you want to preview sites without tracking through a proxy. Note that I've linked a SearXNG repo, which is basically SearX with a nicer UI
#### 🌟 [Startpage](https://www.startpage.com/)
Startpage is sort of like ddg, but it indexes from google. So if you want a private google front-end, here's the search engine for you. Also has the anonymous preview feature SearX has.
#### 🌟 [SauceNAO](https://saucenao.com/)
Specifically for reverse image searching, and it's very good. Always my first line of fire. When it fails, there are hotlinks to google and yandex for additional reverse image searching, as well as a few other reverse image search engines. Pairs well with their [Image Search Options](https://saucenao.com/tools/) extension.
#### [Mycroft Project](https://mycroftproject.com/)
Not a search engine, but a tool for adding more secondary "engines". Typing into the omnibar in your browser to do a search shows little buttons at the bottom labeled "search this time with" with icons for various websites. These are called search shortcuts. This feature should be self explanatory, click the wikipedia button, search with wikipedia. If you do this on a website, if they support it, you can add that website's search to that list in your omnibar. Not all sites you can search on have native support for this feature, though. Mycroft allows people to write scripts for websites that dont support this. I use this for SteamGridDB and HowLongToBeat, for example.
- Brave Browser has a feature called "site search" that lets you do something similar, but with a custom browser-level bang instead. If you're on brave, you can access it [here](brave://settings/searchEngines). [here's](https://files.catbox.moe/yseu0s.png) an example i made for the official minecraft wiki, should be easy to figure out how to make your own from there.
## Media Servers
#### [Jellyfin](https://jellyfin.org/)
Basically, host your own damn netflix! Free open source software, lets you stream media from your own server. You can even just give family and friends the website, username, and password, and they can stream your library too. Movies, Tv, Music, as well as a group watch feature which automatically syncs the video between viewers in case you're watching online together and dont want to have to manually sync every time someone wants to pause. Supports [a ton of devices](https://jellyfin.org/clients/).
#### [Plex](https://www.plex.tv)
Similar to jellyfin, but with more bells, whistles, and plug-in support. Unfortunately, not open source, and contains paywalled features. I don't like it as much, but it's valid.
- [dizquetv](https://github.com/vexorian/dizquetv) A plug-in for plex which lets you create a live "TV channel" auto populated from content on your plex server. You could even add TV Bumpers.
- [Retroarcher](https://github.com/RetroArcher) A plug-in for plex which also lets you stream videogames. Under heavy development. I haven't used it myself, but it seems cool.
## Desktop Operating Systems
>[!note]- I recommend you only use "flagship" or mainline distros as daily drivers. 
>You need to trust security updates (or updates in general) will be timely, stable, and consistent. You also need to trust the people actually maintaining your distro. If no one is actually reviewing the code then you have no idea what the system is actually doing. The less niche the better. Venture out if you wish, just know the risks.

<<<<<<< Updated upstream
### Linux distros [?](https://en.wikipedia.org/wiki/Linux_distribution)
operating systems which are based on the same open source, liberated kernel. Linux can be almost anything you want it to be. It can be easy or hard. It can be simple or complex. It can hold your hand or trust you know what you're doing. It can be immediately functional or customized excruciatingly to your liking. It can be liberating or spyware. It isn't one thing.
It's not obvious how bad windows or even MacOS is until after you've switched. You don't know there's something better until you have it. Even if you "dont want to think about computers", linux is for you in current year.
>[!tip]- Defining Distros
> Distros are not defined by their desktop environments or themes, those can be installed anywhere. Instead, they are defined by their package managers, release cycles, out-of-the-box-experiences, and teams. 
=======
#### Linux distros [?](https://en.wikipedia.org/wiki/Linux_distribution)
Operating systems which are based on the same open source, liberated kernel. Linux can be almost anything you want it to be. It can be easy or hard. It can be simple or complex. It can hold your hand or trust you know what you're doing. It can be immediately functional or customized excruciatingly to your liking. It can be liberating or spyware. It isn't one thing.
It's not obvious how bad windows or even MacOS is until after you've switched. You don't know there's something better until you have it. Even if you "dont want to think about computers", linux is for _you_ in current year. The only case where someone shouldn't be using it is if they specifically _need_ windows/macos for a _good reason_.
>[!tip]- Defining "Distro"
> Distros are not defined by their desktop environments or themes, those can be installed anywhere. Linux is typically modular. That is, you can remove or replace most of its individual parts as you please. Instead, distros are defined by their package managers, release cycles, out-of-the-box-experiences, and the teams managing them.
>>>>>>> Stashed changes
##### [But, Linux Is Bad! / OK, Who Is Linux NOT For?](https://rentry.co/95we932b)
A couple short paragraphs I wrote which I wanted to move off of the list to save space. Read it if the title seems relevant to you. (Yes, it is actually not for some people.)
Oh, and also: [Linux gets more fps than windows](https://www.youtube.com/watch?v=CJXp3UYj50Q). Better battery life too, if you're portable.
##### [Rufus](https://rufus.ie/en/)
is a program for creating bootable USBs, because windows doesn't have that functionality built in (windows moment). So you'll need it to install linux if you're switching from windows.
- [Etchdroid](https://play.google.com/store/apps/details?id=eu.depau.etchdroid) can be used to create a bootable linux USB instead of rufus if you have an Android phone, but you'll need a way to write to a USB (i used an otg usb adapter, some phones come with one)
#### [Linux Mint](https://linuxmint.com)
a "just werks"/"beginner" linux distro based on ubuntu. Fine for linux newcomers. If you dont know what to pick and dont know what all the jargon means, you can pick this to get started. Good for if you miss Windows 7, since it ships with Cinnamon (though you could also use the Cinnamon Fedora Spin for that). Good for grandmas. Better Than Windows:tm:.
* [Pop_OS!](https://pop.system76.com/) a very similar ubuntu-based distro which ships with Cosmic, their own custom DE. I only highlight Mint over Pop because mint is community maintained whereas pop is maintained by a for-profit company, but they're basically the same. Pick your poison.
#### 🌟 Fedora ([Workstation](https://fedoraproject.org/workstation/), [KDE Plasma](https://fedoraproject.org/kde/))
a great distro. This is what I currently daily-drive. Fedora's intent is to stay up to date without breaking your system, Its an incredibly straightforward distro with a great out of the box experience. a fully-featured blank-slate. Utilitarian. The two versions are to pick your preferred DE (gnome or KDE). If you're not sure which version to get, try both on a live-usb and see which you prefer. I use Workstation.
- [Fedora Workstation Spins](https://fedoraproject.org/spins/) if you dont like gnome or kde, Fedora has "spins" for other desktop environments such as Xfce, Cinnamon, Sway, and more pre-installed.
- [Fedora Silverblue](https://fedoraproject.org/atomic-desktops/silverblue/) Fedora Workstation, but atomic. There's also [Fedora Kinoite](https://fedoraproject.org/atomic-desktops/kinoite/) for the KDE equivalent. The long-term goal of Silverblue is to transform Workstation and its spins into atomic distributions.
- [Bazzite](https://bazzite.gg/) a Fedora Silverblue-based distro which is basically better SteamOS. Good for your handheld gaming computers (including steamdeck) or if you want to turn a desktop into a gaming console. Not good for much else. You can absolutely reproduce bazzite's ootb experience in silverblue, but if you're looking to set up a console-like experience this is just easier. Its the \#GAMER distro. Also check out [Bacotara](https://batocera.org/) if you're interested in turning a USB into an OTG [distro focused on emulation](https://emulation.gametechwiki.com/index.php/Recommended_Linux_distros#Emulation-focused).
#### [Arch](https://archlinux.org/)
Arch is cool, if Arch is for you. If you want to use it, you ought to know how to read. You'll have to "know what you're doing". Read the docs. Anyways, Arch is a rolling release distro that ships bleeding edge software, so be prepared for things to break when you're updating. Stuff isn't tested, so you'll have to fix stuff often, but you also get everything before anyone else. Using Arch also gives you access to the Arch User Repository (AUR), which is full of community maintained packages (dont use it if you dont know what you're doing, but you ought to if you're using Arch). Try it if you like control and fixing things. Oh, and its super lightweight too (since it sort of comes with nothing), so put it on your old laptop if u want.
>[!warning]- Arch forks, install scripts
>I'd also like to anti-recommend arch-based distros like manjaro or endeavor. They are very poorly made in my view. Manjaro is infamous for its jank releases.
>There's also part of me that doesn't want to recommend install-scripts for your first Arch install. On the one hand, its an easy way to get a bootable arch system with little hassle and you can go from there, then you get a nice lightweight distro out of it. On the other, you really should know how the system works to fix problems, and the installation is kind of like a tutorial in a way. Plus, doing everything manually gives you more control, which is kind of what Arch is about. Given its about control, though, the choice is ultimately up to you.
#### [OpenSUSE Tumbleweed](https://www.opensuse.org/#Tumbleweed)
is very similar to Fedora in many ways. They reproduce a lot of the same work and use the same package manager as Fedora, but OpenSUSE might be a bit better if you're something like a sysadmin. The main advantage over Fedora in my opinion is [YaST](https://yast.opensuse.org/), which is a really nice settings suite. It doesn't sound all that hot on paper, but its cool. OpenSUSE is also rolling release like Arch, but they test packages for two weeks before shipping, which means stuff breaks less often.
#### [NixOS](https://nixos.org/)
an atomic, immutable, reproducible, declarative distro. Stability on the bleeding-edge. "better arch", if you're brave enough to say such a thing. Both nixpkgs stable and unstable have more packages (more fresh packages at that) than the AUR, which is impressive. You can also configure your whole system in one file, easily reproduce it on another machine, roll back when something goes wrong, use a stable, rolling, (or both) release model, and more. Try out people's dotfiles from github and just insta undo them if they suck. Its cool. [showcase video](https://www.youtube.com/watch?v=CwfKlX3rA6E)
#### [Tails](https://tails.net/)
a portable and ephemeral operating system meant to run off of a USB which is focused on privacy. Get in, do your business, and get out. It's meant to launch on any computer and leave virtually little trace once you shut it down and unplug. Uses the Tor network. Give it to people trying to arrange an out of state abortion, those stuck in domestic abuse situations, journalists, activists, anyone who needs to turn any computer into their private machine for a bit. Not for daily use. If you want something more long term that can be for daily use, look into [Qubes](https://www.qubes-os.org/) (just know you're not exactly going to be gaming on it.)
#### [Awesome Linux Software](https://luong-komorebi.github.io/Awesome-Linux-Software/)
([github](https://github.com/luong-komorebi/Awesome-Linux-Software)\) a list of linux applications and tools. Could be useful if you're just starting linux for the first time.
#### [AreWeLibAdwaitaYet](https://arewelibadwaitayet.com/)
a list of linux applications using Adwaita. Huge if you use gnome, since everything will look well integrated into your DE :)
#### Fuck windows, but
Yes, Windows is dogshit spyware. If you haven't tried something else you do not know how much better it can be. Regardless, If you MUST use it for whatever reason, the following tools may prove useful.
* [Microsoft Activation Scripts](https://github.com/massgravel/Microsoft-Activation-Scripts) Microsoft supplies free download links to much of their software (including [Windows 11](https://www.microsoft.com/software-download/windows11)) on their site, so you can just download the ISO officially, then activate it with MAS instead of paying.
- [Winaero Tweaker](https://winaerotweaker.com/) a registry quick-editor to easily customize windows to your liking and remove bloatey bullshit you don't need like spyware, ads, cortana, etc. Works for Windows 7 through 11 at the time of writing. Not to be confused with Win10 Tweaker. [Showcase Video](https://www.youtube.com/watch?v=08JNHHRQQZw)
- [winutil](https://github.com/ChrisTitusTech/winutil) sorta like winaero tweaker. Meant to streamline installs, debloat, help troubleshooting, and fix Windows updates.