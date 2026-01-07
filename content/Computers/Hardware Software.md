---
title: 🖥️ Hardware and Software
description: Application, browser, search engine, and operating system recommendations. With a dash of hardware resources.
tags:
  - computers
---
# Hardware
#### [LTT's PC Building Guide (2024)](https://youtu.be/s1fxZ-VWs2U
Sort of a "choose your own adventure" style mega-video as a PC building guide.
	Use YouTube chapters to learn about whatever specific part you're interested in, or just watch the whole thing if you're starting from scratch.
	-  [LTT's Laptop Buying Guide (2024)](https://www.youtube.com/watch?v=vddu2jmfVbI))
#### [PC Master Race Explained in 9 minutes](https://www.youtube.com/watch?v=RRY1jrIDhvU)
Entertaining animation that talks about the pros and cons of buying various kinds of electronics, styled to look like it was made in flipnote studio.
	Also talks a bit about right to repair. Highly recommend you give this a watch if you're in the market for a new device or care about computers at all.
>[!tip] This video is also available in **[Japanese](https://www.youtube.com/watch?v=AKKBuCinOKM), [Mandarin](https://www.youtube.com/watch?v=-MgOV6BQnl8), [Russian](https://www.youtube.com/watch?v=fFsJU7CKP-I), [Korean](https://www.youtube.com/watch?v=q4heFXEaZ0g)**, and **[Cantonese (incomplete)](https://www.youtube.com/watch?v=8sMxMID96gM)**.
#### [PC Part Picker](https://pcpartpicker.com/)
Helps you to create a desktop build of parts that are compatible with one another.
	Compare different parts (both in terms of price and performance), share your hypothetical build for feedback, etc.
#### [ComparisonTables](https://comparisontabl.es/)
Spreadsheets comparing E-readers, smart phones, handheld gaming pcs, soundbars, bluetooth speakers, cloud services, and more.
	Compares by specifications, features, availability, pricing, and much much more.
#### Liquidation, refurbishment, and the second hand market
Find stuff for cheap!
	Electronics, office/gaming chairs, and even furniture, home appliances, cars, and more can be found for much cheaper than buying new. (and in the case of CRTs: be found at all)
	There's a reason ThinkPads are a Linux nerd meme: Businesses regularly flood the second-hand market for a ton of different reasons, and often at extremely cheap prices. A laptop can be 4 years old selling at half the price as it would if it were new.
>[!important]- Security EoL
>Especially for devices which rely on the manufacturer to supply security updates (phones, tablets, etc), you'll want to be aware if your device is actually secure. [Endoflife.date](https://endoflife.date/) can help you track when your hardware/software will stop receiving security updates.

>[!warning]- (Laptop) part replacement
>Search "(laptop name) teardown" to see if whatever you're buying has other replaceable parts. May be a viable avenue if you're finding a unit with an obvious single broken part that the seller would rather flip than repair.
>You should also search common problems for whatever model you're looking at, as any given laptop will have its individual weak points or places where it's likely to initially fail.
>**Hard drives** are often ripped out by professional bodies for security reasons. Though tbqh, I wouldn't trust used hard drives for most use-cases (old and used ones love to fail). Those you should generally buy new _when you're able_. If you can't, back up your data regularly. 
>**Batteries** degrade with time, so you may have to replace the battery if it wasn't well taken care of by the previous owner. Used batteries will inevitably require sooner replacement.
>**Screens** can be expensive to replace, but also one of the best things to upgrade for a better experience. Anything more than 1440p on a laptop isn't going to make a difference and will just drain your battery for no reason.
>**RAM, CPU, GPU, I/O, etc.** is often _not_ replaceable. What you buy is what you get.
>If you care a lot about repairability, upgradability, and modularity, look into [Framework](https://frame.work/)'s laptops.

Some places to start:
	[This video](https://www.youtube.com/watch?v=NsTobnTfsYw) by Salem Tech may help you on your journey.
	- Multiple Countries: [FB Marketplace](https://www.facebook.com/marketplace/), [EBay](https://www.ebay.com/), [MaxSold](https://maxsold.com/)
	- US: [Craigslist](https://www.craigslist.org/), 
	- CA: [Kijiji](https://www.kijiji.ca/) 
	- UK/AU: [GumTree](https://www.gumtree.com/)
	- I've heard good things about [Refurbed.ie](https://www.refurbed.ie/) for computers/laptops, and [Auctionxchange](https://www.auctionxchange.ie/) for everything else. Some hardware manufacturers also have sale pages dedicated to refurbished units
	- [[Discussion|Let me know]] of any sites you've had luck with that aren't listed here
	State/county/municipal warehouses and electronics recycling centers, local (asset, office, misc.) liquidators, school, university, and medical center auctions, local electronic repair shops, thrift stores, yard/garage sales, personal auctions, and thrift stores are all your friend.
# Software
## Desktop Applications
#### 🌟🌐 [AlternativeTo](https://alternativeto.net/)
Find software alternatives.
	You've probably used AlternativeTo before, but it really is just good. Especially for replacing non-libre and annoying software, and for comparing software against each other. I used to sleep on it in the past.
	Their filters are very strong, and it lets you compare programs against each other. I like to filter by Linux and Open Source.
#### 🌟 [qBitTorrent](https://www.qbittorrent.org/)
The torrenting client I prefer.
	- [Deluge](https://deluge-torrent.org/) - Also fine
	- [Transmission](https://transmissionbt.com/) - Good if you want a bare bones UI. Also offers a CLI interface
	- [LibreTorrent](https://gitlab.com/proninyaroslav/libretorrent) - Good Android torrent client
	- uTorrent is sketchy and ass, stop using it
#### 🌟 [NewPipe](https://newpipe.net/)
FOSS mobile app that lets you watch YouTube on your phone without signing in to Google.
	It also allows you to download videos, listen to them in the background, skip ads, and skip sponsored segments. Basically everything YouTube Premium offers and more. 
	Also supports Bandcamp and SoundCloud for music streaming. 
	Admittedly, it breaks a lot, but you can use [Obtainium](https://obtainium.imranr.dev/) to update it easily when it does.
#### 🌟 [ReVanced](https://revanced.app/)
Manager to apply mods to various Android apps.
	Especially useful to remove ads on apps like YouTube, Twitter, TikTok, Tumblr, and more.
	Most people prefer this over NewPipe since it lets you use the actual YouTube app (or any other apps it modifies), but obviously that requires signing in to Google.
#### 🌟 [YouTube-dlp](https://github.com/yt-dlp/yt-dlp)
Command line utility for downloading vids from YouTube and [others](https://ytdl-org.github.io/youtube-dl/supportedsites.html).
	Use this if you just want the command line utility and dont want the gui that Tartube provides. If you dont know what this means, get Tartube.
#### [Tartube](https://tartube.sourceforge.io/)
GUI frontend for yt-dlp and others. Basically, it's a video downloader.
	Never search "youtube mp3 converter" or "youtube downloader" again. Supports more sites than just YouTube. Also downloads mp3s and thumbnails. Be sure to use yt-dlp in Tartube.
#### 🌟 [Cobalt.tools](https://cobalt.tools) (web)
Browser tool to download media from various sites.
	YouTube, Twitter, Twitch, TikTok, Reddit, Instagram, Snapchat, Facebook, Tumblr, and more and more and more are supported.
	Just paste the link in and you're off. It's also open-source, so you can host your own instances by pulling from their [GitHub](https://github.com/imputnet/cobalt). YouTube has blocked their primary instance, but community instances can still download from yt. Else check out yt-dlp/tartube above
#### [Copyparty](https://github.com/9001/copyparty/)
a portable file server. This is a lot more powerful than it sounds. Watch the showcase.
	- [Showcase](https://www.youtube.com/watch?v=15_-hgsX2V0)
#### 🌟 [Localsend](https://localsend.org/)
Does what it says on the tin. Share files to nearby devices that also have LocalSend.
#### 🌟 Magic Wormhole
Protocol that allows E2EE transfers of files of any size from one computer directly to another.
	Use this instead of uploading files to some random server when you're trying to send something to a friend
	The following are various clients for Wormhole, for end-users:
		- [Warp](https://apps.gnome.org/Warp/) - Flathub package made for Gnome (Linux)
		- [Winden](https://winden.app/) - Web client
		- [Destiny](https://f-droid.org/packages/com.leastauthority.destiny/) - Android and iOS
		- [Rymdport](https://github.com/Jacalz/rymdport) - Cross-platform desktop (Windows/MacOS/Linux)
		- [magic-wormhole](https://github.com/magic-wormhole/magic-wormhole) - Python CLI
		- [wormhole-william](https://github.com/psanford/wormhole-william) - Go CLI
		- [magic-wormhole.rs](https://github.com/magic-wormhole/magic-wormhole.rs/) - Rust CLI
		- and more! These are all recommended in the Magic Wormhole documentation [here](https://magic-wormhole.readthedocs.io/en/latest/ecosystem.html#end-user-client-applications).
#### [JDownloader](https://jdownloader.org/)
Download manager.
	Scrape websites, read the clipboard for links to downloads, etc.
	Have them all in a neat list. Especially useful for archive.org collections or for when you have a slow internet connection.
#### [Handbrake](https://handbrake.fr/)
Video transcoder. Compress, convert, etc.
	Throw videos in and choose which format you want and watch the file size shrink. Though you could consider working with FFmpeg directly, or using something like [Constrict](https://github.com/Wartybix/Constrict) on Linux.
#### [ShareX](https://getsharex.com/)
Best screenshot software there is.
	Windows only. Still sad there isn't a Linux version.
#### 🌟 [Open Broadcast Software (OBS)](https://obsproject.com/)
Best video recording, screen recording, and streaming software there is.
#### [Raycast](https://www.raycast.com/)
MacOS and Windows app which adds a bunch of different functionalities, improving workflow.
	Replaces spotlight and does quite a bit. Kinda gives you a single search bar that can search your system, do math, copy emoji. Just type into the bar and it figures out whatever you're trying to do.
	- [showcase](https://www.youtube.com/watch?v=ppHPoKPgf1k)
#### 🌟 [Davincibox](https://github.com/zelikos/davincibox/) ([DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve))
DaVinci Resolve is in my opinion the only video editor that's a viable alternative to Adobe Premiere for most editing heavy use cases.
	If you just need to cut a few things many other video editors will be fine, though.
	This is an unofficial DaVinci Resolve Linux installer. DaVinci Resolve is natively supported on linux, but only really for Rocky Linux for some reason. This sets up a distrobox instance that'll have DaVinci running as if it's a native application on any distro!
#### 🌟 [Obsidian.md](https://obsidian.md/)
Writing/note taking app that stores all documents you make in human-readable markdown.
	You can use community plugins from the built-in plugin store to store your vault to the cloud. The content of this site is actually written in Obsidian.
	- [Obsidian Recommendation video](https://www.youtube.com/watch?v=DbsAQSIKQXk)
	- [LogSeq](https://logseq.com/) - An open source alternative to Obsidian, though I have yet to try it personally. Unless you have a particular use-case that would cause you to prefer one over the other, just choose one and start working
#### 🌟 [Photopea](https://www.photopea.com/) (web)
Free "remake" of Adobe Photoshop in browser.
	Doesn't upload files to the cloud, and works better than it has any right to. This said, they're in a bit of an arms race of anti-adblocking which can be a bit annoying.
#### 🌟 [Excalidraw](https://excalidraw.com/) (web)
Online whiteboard.
	Lets you easily draw diagrams with a bunch of easy to use tools, and lets you collaborate by sharing your whiteboard as a link, and just generally brainstorm. The fonts and lines are beautiful. I like it a lot more than using MS Paint and discord's whiteboard app, or anything similar. If i had a drawing tablet, maybe even more than a real whiteboard. Infinite canvas, dark mode, and more. Oh, and its FOSS and E2EE.
#### [JS Paint (MS Paint remake)](https://paint.js.org/) (web)
JavaScript remake of Microsoft Paint that runs in browser.
	Install it as a PWA if u want :)
#### 🌐 [List of Adobe Alternatives](https://twitter.com/XdanielArt/status/1434611199140896772)
Somewhat old list of alternatives to Adobe Suite software.
	Useful for Linux or if you just hate Adobe (But, of course, pirating their software will always be moral)
#### [Aseprite](https://github.com/aseprite/aseprite)
Pixel art illustration program loved by both hobbyists and professionals.
	Fun fact many don't know about Aseprite: it uses a license which is sort of adjacent to open-source software. They charge for it, but their license actually permits compiling from source for free, for both personal AND commercial use. The only limitation is that you're not allowed to re-distribute a compiled Aseprite (thus its not actually open-source, just source-available).
	- [official website](https://www.aseprite.org/)
	- [linux compile script (dnf/apt)](https://github.com/mak448a/compile-aseprite-linux)
## Mobile Applications
#### [Fossify](https://www.fossify.org/apps/) (Android)
Suite of open-source, add free basic Android applications.
	They ship a calendar, contacts, file manager, gallery, and messages app.
	All are available on Google Play, F-Droid, and Github.
#### [Privacy Friendly Apps](https://secuso.aifb.kit.edu/english/105.php) (Android)
Collection of Android apps by the Security Usability Society, which are all available on F-Droid.
	There's apps for fitness/health, tools, games, security, etc.
	I personally use 2048. My grandmother loves to play Solitaire on her phone but was using really sketchy apps from GPlay to do so, so i got her their Solitaire app and she likes it fine. 
	- [GitHub](https://github.com/SecUSo)
#### [Librepods](https://github.com/kavishdevar/librepods?tab=readme-ov-file) (Android, Linux)
Unlocks Apple's exclusive AirPods features on Android and other non-Apple devices.
	Noise control modes, adaptive transparency, ear detection, hearing aid, customized transparency, battery status, and more.
	Unfortunately requires root on Android due to a [bug in the Android Bluetooth stack](https://issuetracker.google.com/issues/371713238) that hasn't been fixed at the time of writing. But it should work on non-rooted devices once this is fixed by Android, and still works on Linux fine.
## Web browsers
>[!warning]- Anti-Recommendations
> Edge, Google Chrome, and Opera browsers like Opera GX or Air are all shady as hell [and only good for one thing](https://www.youtube.com/watch?v=IXhmu1aQSOY). (And equivalent to each other in their shittyness, do not fool yourself).
>There's no reason to use any of these when the alternatives below exist. If you're using any of these, its quite easy to export bookmarks, passwords, etc and import data into a new browser.
> Safari (webkit) is okay... All browsers on ios are actually forced to be webkit based, so heads up on that. Apparently [Orion](https://kagi.com/orion/) is a good webkit based browser, but its closed-source it at the time of writing so I've decided to exclude it.
> Vivaldi i'm skeptical of. Supposedly they're moving towards open source, but who knows when and if that'll actually happen.

> [!note]- You need to trust your browser provider
  At least as daily drivers. You need to trust that security updates (or updates in general) will be delivered in a timely and stable manner. The less niche and more users, the better. Not to mention selling out or pivoting like Arc did, or eroding privacy like Mozilla Firefox has. Venture out if you wish, just know the risks. 
### Firefox (Gecko) Based
>[!warning]- Gecko based browsers are less secure
>Per [GraphineOS](https://grapheneos.org/usage#web-browsing):
>	"Avoid Gecko-based browsers like Firefox as they're currently much more vulnerable to exploitation and inherently add a huge amount of attack surface. Gecko doesn't have a WebView implementation (GeckoView is not a WebView implementation), so it has to be used alongside the Chromium-based WebView rather than instead of Chromium, which means having the remote attack surface of two separate browser engines instead of only one. Firefox / Gecko also bypass or cripple a fair bit of the upstream and GrapheneOS hardening work for apps. Worst of all, Firefox does not have internal sandboxing on Android. This is despite the fact that Chromium semantic sandbox layer on Android is implemented via the OS `isolatedProcess` feature, which is a very easy to use boolean property for app service processes to provide strong isolation with only the ability to communicate with the app running them via the standard service API. Even in the desktop version, Firefox's sandbox is still substantially weaker (especially on Linux) and lacks full support for isolating sites from each other rather than only containing content as a whole. The sandbox has been gradually improving on the desktop but it isn't happening for their Android browser yet."
>
>Imo, It depends on your threat model. I dont think this should be an issue for most people but its something to be aware of.
#### (Hardened) [Firefox](https://www.mozilla.org/en-US/firefox/new/)
The vanilla Gecko browser.
	Its backed by Mozilla, so it'll have strong support and timely security updates as the upstream, but Mozilla has [sold out hard and is kind of corrupt](https://digdeeper.club/articles/mozilla.xhtml).
	Its privacy defaults are abysmal, and in my experience Firefox has worse compatibility than Chromium, is slower at that. Though, forks can improve on both fronts.
	I mostly recommend it because it makes a lot of sense when you harden it, as it'll provide many of the same privacy protections as alternatives without the need to trust more parties.
>[!warning]- **Please** [**Harden Firefox and disable bloat**](https://www.privacyguides.org/en/desktop-browsers/#firefox)
>If you want an easier alternative to Arkenfox, try [Betterfox](https://github.com/yokoffing/BetterFox)
>its supposedly easier than Arkenfox, but I'm not sure its as legitimate or respected. If you can handle Arkenfox, please use it. But Betterfox is certainly better than using neither.
>If you want to go to a step further, the ArchWiki has a [Firefox tweaks](https://wiki.archlinux.org/title/Firefox/Tweaks) article.
#### [Zen Browser](https://zen-browser.app/)
Spiritual successor to Arc with a very diehard fanbase.
	It has a lot of neat, useful features in the UI and workflow department, so i think its worth checking out and learning. Has a large focus on vertical tabs.
	Uses privacy defaults based on Betterfox, but will also never use privacy settings that could break anything, even in edge cases, so i wouldn't call it privacy focused. [Some think its a honeypot](https://discuss.privacyguides.net/t/zen-browser/20312) so compile from source yourself or get the binary from a third-party you trust if you're sus'd.
#### [Floorp](https://floorp.app/en)
Highly customizable, Supports PWA out of the box.
	Its not amazing on the privacy front due to it not being a focus, though its not malicious either. You can harden it too (see above). [showcase](https://www.youtube.com/watch?v=6OUjWdAtGbs).
	- [Firedragon](https://github.com/dr460nf1r3/firedragon-browser) is a fork that uses KDE integration patches and custom branding for Garuda
#### [Librewolf](https://librewolf.net/)
Basically the de facto privacy respecting daily driver, if you dont want to harden Firefox yourself. "unmozilla'd Firefox", if you will.
	Breaks a ton of websites and functionality in the name of privacy, and also requires you trust more people between you and your browser, but it has its place. You can also just harden vanilla firefox above yourself for the same functionality (which i'd sooner recommend).
	Does not have automatic updates without an external package manager (on windows you can click the checkbox in the component selection on install for auto-updates).
#### 🌟 [Mullvad Browser](https://mullvad.net/en/browser)
Tor, but instead of using the Tor network, uses a VPN.
	Based on Tor, and is a collaboration between Mullvad and the Tor Project. Not a daily driver.
	You probably ought to use the same etiquette as you do with Tor. Don't do anything that'd make your browser stand out, sign in to any accounts, etc. But its good if you're just web surfing and aren't, say, logging into your bank or anything that could identify you. Tor is better if you really want to make sure you're anonymous.
#### [Tor Browser](https://www.torproject.org/download/)
Lets you browse the internet anonymously*, and access .onion domains. Not a daily driver.
	Ideally, makes your browser look the same as all other Tor users, which makes it very hard to distinguish between users.
	Do not modify any defaults. Read about [proper etiquette](https://tb-manual.torproject.org/) or else it'll be useless.
	Numberphile has a [great video](https://www.youtube.com/watch?v=QRYzre4bf7I) about the technical details of how the tor network helps to keeps you anonymous.
	Also, it's gonna be slow.
>[!danger]- Do not use Tor with a VPN. Do not daily drive. Do not install any extensions*
> except maybe [uBlock Origin](https://ublockorigin.com/) (a common... enough... install to make it okay... probably).

>[!tip] Check out Tails under Operating Systems below **[[Hardware Software#Desktop Operating Systems|(jump)]]** if you're interested in a private/secure/anonymous temporary operating system
### Chromium Based
#### [Helium](https://helium.computer/)
User respecting black-slate with good OOTB defaults and built in bang support.
	Helium is made by the same devs behind Cobalt.tools, which is a green enough flag in my book. However, its still quite new and is managed by a small team, so i'm reluctant to overwhelmingly recommend it. It seems to be born out of a frustration with many considering Brave to be the best browser.
	Claims good privacy defaults.
	Still in beta at time of writing. Its become my daily driver, but reluctantly so.
	- [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium)
		What Helium is based on. Its worth a mention, though i think it has some serious issues for the uninitiated. (Still a great browser if you can look past and deal with these issues, though.)
		You can't install extensions from the Chome extension store (only via .CRX files, no automatic updates), doesn't have automatic updates (for the browser it's self. at least without external package management for it), and is more geared towards technical users, as its seemingly designed for users to poke around and configure chromium flags themselves. [also maybe not the best security](https://discuss.privacyguides.net/t/browser-account-isolation-with-seperate-browsers/17609/4).
#### [Brave](https://brave.com/)
Generally privacy respecting.
	Comes with Brave Shields, which is a built in ad/tracker blocker. Also supports uBlock Origin.
	There's a bunch of side features too, but the only one i really like is speedreader.
>[!warning]- **Please** [**Configure**](https://www.privacyguides.org/en/desktop-browsers/#brave) and [**Debloat**](https://www.youtube.com/watch?v=W6cKFliWW6Q) Brave
> The Privacy Guides link above will guide you through improving the privacy/security of brave. Additionally, disable "Brave Rewards" and their other crypto bullshit on install. 

>[!warning]- You will have compromised anonymity when accessing .onion domains
> Brave is not as resistant to fingerprinting as Tor, and far fewer people browse the Tor network with Brave than with Tor, so you will stand out. So please do not use Brave to surf Tor if your threat model requires strong anonymity.

>[!warning]- Brave has a couple [controversies](https://www.reddit.com/r/browsers/comments/1j1pq7b/list_of_brave_browser_controversies), so you may want to steer clear.
>Ultimately, Brave is ran by a for-profit company. So they do a bunch of shady and lame shit in the name of profitability. Other times they're Just Weird.
## Search engines
I recommend just adding all of these engines as [search shortcuts](https://support.mozilla.org/en-US/kb/assign-shortcuts-search-engines), though you could always use bangs in DDG/Brave/Kagi/Helium.
#### 🌟 [DuckDuckGo](https://duckduckgo.com)
The most popular privacy respecting engine. My default. Usually gets the job done. 
	DDG pays Microsoft to source results from Bing, but unlike Bing it's good about user privacy. Bing results aren't as bad as they're meme'd to be.
	Also uses [bangs](https://duckduckgo.com/bangs), which lets you search other sites (ex `!w` for wikipedia, `!yt` for youtube). Very useful.
#### [Kagi](https://kagi.com/)
Paid search engine. They're pretty good about user privacy.
	They source their results from a number of other engines, including some indexing they've done themselves. 
	Kagi supports bangs (and lets you add your own), and their results good. They have a bunch of little features.
	My favorite feature from kagi are their [lenses](https://www.youtube.com/watch?v=ho9J6OKMxR8), which let you change the "type" of search results you get. There's a "small web" lens, which will highlight indie sites. It also lets you create your own lens, if that's up your alley.
	You can promote or demote a site for your future searches, or block them entirely. They have modes to filter AI generated image results, they have little banners showing if a result if from a surveillance entity, and probably more idk about.
	I should note they pay Brave, if you have ethical issues with them. They also argue against providing mental health resources when users query self-harm and related stuff.
#### [Brave Search](https://search.brave.com/)
Seemingly private search engine with a bespoke index.
	From the company that made the web browser. They source their results themselves, so that they dont have to rely on Bing or Google.
	I didn't think the results were very good last time i used it.
	Supports bangs, like ddg does.
>[!warning]- Brave has a couple [controversies](https://www.reddit.com/r/browsers/comments/1j1pq7b/list_of_brave_browser_controversies), so you may want to steer clear.
>Ultimately, Brave is ran by a for-profit company. So they do a bunch of shady and lame shit in the name of profitability. Other times they're Just Weird.
>
#### [SearX](https://searx.space/)
Open source and decentralized engine that aggregates results from multiple engines.
	Due to its open source and decentralized nature, no one can really own SearX, and everyone knows exactly how it works. Kind of like Mastodon if you're familiar with that. 
	Vanilla SearX is privacy respecting on the back-end, but you have to trust the host you're using, which can generally be done by making sure they're running vanilla. You could also disable JavaScript if you want to be extra sure you're searching privately. You can even host it yourself if you want to go the extra mile.
	It aggregates from a number of other engines and sort of mixes them all together and sorts based on relevance. You can select what search engines it pulls from in it's settings, which will effect response times.
	Also has an anonymous page viewer if you want to preview sites without tracking through a proxy. Note that I've linked a SearXNG repo, which is basically SearX with a nicer UI.
#### [Startpage](https://www.startpage.com/)
Sort of like DDG, but it indexes from Google instead of Bing.
	If you want a private Google front-end, this might be your best bet. Though imo Google's results have degraded a lot in recent years, and they're still ultimately collecting your searches with Startpage as a proxy.
	Also has the anonymous preview feature SearX has.
#### 🌟 [SauceNAO](https://saucenao.com/)
Amazing reverse image search tool for art.
	Always my first line of fire. When it fails, there are hotlinks to other engines for searching the image you're looking into.
	Pairs well with their [Image Search Options](https://saucenao.com/tools/) extension, though you have to load it as a .crx in Chrome since it looks like its been taken off the extension store.
## Homelab
>[!note]- I'm not personally into homelabbing, I will be eventually
>Unfortunately due to the way my current ISP is set up, I'm not actually able to host anything myself or open any ports, but I really want to deep-dive into homelabbing once I move. Once I jump down that rabbit-hole homelabbing will probably get its own dedicated page. As for now, this is stuff I host either just for myself or which friends whom homelab have recommended to me.
#### 🌟 [Jellyfin](https://jellyfin.org/)
Self-host Movie/TV streaming service. Host your own damn Netflix!
	Free open source software. You can even just give family and friends the website, username, and password, and they can stream your library too.
	Lets you stream movies, TV, music, and more. 
	Jellyfin also has a group watch feature, which automatically syncs the video between all viewers. Watch online together without having to manually sync at start or to pause.
	Supports [a ton of devices](https://jellyfin.org/clients/).
	- [Feishin](https://github.com/jeffvli/feishin) spotify like client for Navidrome and Jellyfin
#### [Plex](https://www.plex.tv)
Similar to jellyfin, but with more bells, whistles, and plug-in support.
	Unfortunately, not open source, and contains paywalled features. I don't like it as much.
	- [dizquetv](https://github.com/vexorian/dizquetv) A plug-in for plex which lets you create a live "TV channel" auto populated from content on your plex server. You could even add TV Bumpers.
	- [Retroarcher](https://github.com/RetroArcher) A plug-in for plex which also lets you stream video games. Under heavy development. I haven't used it myself, but it seems cool.
#### [Tunarr](https://github.com/chrisbenincasa/tunarr/)
Create a classic TV experience with Plex/Jellyfin/Emby
	Creates an IPTV using your localhost streaming services, set up multiple channels schedules, and more.
	I think you can even set up your own commercial breaks and bumpers if you're into that sort of thing
#### [Navidrome](https://www.navidrome.org/)
Self-host music streaming service. Host your own damn Spotify!
	Free open source software. similar to jellyfin in all the good ways, but for music. I have a friend that swears by it.
	- [Feishin](https://github.com/jeffvli/feishin) spotify like client for Navidrome and Jellyfin
## Linux ([?](https://en.wikipedia.org/wiki/Linux_distribution))
Operating systems which are based on the same open source, liberated kernel.
	Linux can be almost anything you want it to be. It can be easy or hard. It can be simple or complex. It can guide you like a baby bird or ask you to do wheelies with no hands. It can be immediately functional or customized excruciatingly to your liking. It can be liberating or spyware. It isn't one thing.
	It's not obvious how bad Windows or even MacOS is until after you've switched to something good, especially when it fits your needs.
	You don't know there's something better until you have it. Even if you "dont want to think about computers", linux is _probably_ for you in current year.
### Desktop Workstation Distros

>[!tip]- Defining distro
> Distros are not defined by their desktop environments or themes, those can (technically) be installed anywhere. Instead, they are defined by their package managers, release cycles, out of the box (OOTB) experiences, and teams.

>[!note]- I recommend significantly popular distros from reputable teams as daily drivers. 
>You need to trust security updates (or updates in general) will be timely, stable, and consistent. You also need to trust the people actually maintaining your distro. If no one is actually reviewing the code then you have no idea what the system is actually doing. The less niche the better. Venture out if you wish, just know the risks.

>[!note]- Distros i don't mention, and why
>- **Manjaro, Endeavor, Omarchy, Cachy, and other similar arch-based distros** - Make Arch too easy.
>     - For example, Endeavor is "like Arch for new or normal people"... If you're new and normal, you shouldn't be using Arch. 
>     - This isn't me being petty or elitist. These systems are basically just Arch, so you'll have "basically just Arch" problems (like broken/manual-intervention updates). 
>     - The AUR is dangerous, people break stuff and dont understand how to RTFM, or configure things weirdly with band-aid solutions to get stuff working. It's just too much power too accessibly. Other distros like Fedora strike a much better balance, imo. Arch expects certain behaviors and skills from its users, and installing these distros don't ensure you have those skills or exhibit those behaviors at all.
>     - Cachy - Neat but its performance gains are too slim and inconsistent to outrun my issues with Arch derivatives.
>     - Manjaro - Especially egregious. Its infamous for its jank releases, and is especially bad in the "timely/working security updates" department. Once their certificates expired and their solution for users was to roll their clocks back to before the certs expired!! Like what!! Absolutely unacceptable.
>     - SteamOS - I think I could tolerate, if it didn't _force_ an account to do anything. Not to mention opt-out telemetry that you can only opt-out of after logging in. Chromebook-ass system. Just use Bazzite, even on your Steam Deck. [Its better in many ways](https://docs.bazzite.gg/General/SteamOS_Comparison). See its entry under Fedora below.
>     - Omarchy - Similarly bad as something like Endeavor, but jankier, bloaty, and is run by an alt-right loser. Its not even really a distro, It's just a rice script. Even ArchInstall is preferable. So try that with Hyprland or Niri if Omarchy is tempting you.
>     - Here my actual elitist take: Arch is a hobbyist distro about control. Why are you letting someone else do the hobby of configuring Arch for you?
>- **Ubuntu** - Just use Mint or Pop to avoid Canonical's bullshit (looking at you, snaps). I appreciate the want to go upstream but I think Mint/Pop are more valuable for the niche Ubuntu is trying to fill. I'd also sooner point people to Fedora KDE than Kubuntu.
>- **LMDE** - Does not have the Kernel Manager or Driver Manager that Mint offers, which i think is Mint's biggest strength. Worse hardware support (ex. printers, new graphics cards). Can be hard or impossible to update some software like Mesa drivers. Slower to update than Mint, gets less attention from the Mint team for bugs, etc. At a certain point I want to point people elsewhere, the technicalities defeat the purpose. [Here's a good article](https://www.webpronews.com/linux-mint-vs-lmde-which-should-you-choose/) comparing LMDE and Mint by someone that actually prefers LMDE.
>- **Pop_OS!** - Has fallen behind in recent years due to their focus on developing their Cosmic DE. I only don't recommend it now because their current Gnome setup isn't really up to snuff, but once Cosmic hits its first stable release I'll likely consider it on par with Mint. 
> 	 Here's what i had to say when it was a bullet under mint: 
> 	 A very similar Ubuntu-based distro. I only highlight Mint over Pop because Mint is community maintained whereas Pop is maintained by a for-profit company, but they're very similar. Pick your poison.
>- **ElementaryOS** - Underwhelming. It's made by a small team that's given themselves a pretty heavy workload. Their updates tend to be a bit slow... I dont hate it! The developers seem cool, and they care about accessibility a good bit more than most. I just really dont care for the aesthetics and personally don't think it feels like MacOS like many claim. It's worth checking out if mint and pop don't work for you. but i dont see any particularly strong reasons to use it. Cut to reduce choice paralysis.
>- **Nobara** - Cut in favor of Bazzite. Nobara targets intermediate users who also want a desktop workstation, but i think i would rather encourage people to go upstream and configure Fedora to play their games if they're competent enough to use Nobara in the first place. Meanwhile, Bazzite is good for noobs and offers a good OOTB consolization experience, which is a use case I think is worth installing over Fedora at times.
>- **Kali/Parrot** - Are you pen testing? Doing some digital forensic analysis? Security research? If you are, Parrot is fine. Hell Kali is too. Not for this list. This list is for the average user's daily-driver desktop workstation use case.
>- **Deepin** - Might be spyware, forked Flatpak for 0 reason, has a DE that's incredibly under-powered, their aesthetics break as soon as you get software not made for their DE, and their DE also has frequent enough security issues that SUSE stopped offering it, as Deepin's security culture was very poor and because they had a hard time working with them to push security fixes upstream \[[source](https://en.wikipedia.org/wiki/Deepin#OpenSUSE_removal_of_Deepin_Desktop_Environment)\]. No. Also its really just the DE, so:
>- **KDE Neon, Gnome OS, and other distros from DE teams** - Don't serve much of a point in my opinion. Just use the DE in a more established OS.
>- **Gentoo** - I know. Gentoo has its place. I (really do) respect the name. Anyone using this list probably doesn't need it. Arch fits the niche for this list. Yes i understand they're not the same. Honorable mentions go out to it, though. I dont want to compile firefox for 72 hours. You're valid its ok i promise. You're just bored waiting for your 4th compile today, its ok. You dont have to beat me up, you're loved, this is a safe space.
>- **My Blindspots** - Distros I just don't know enough about them. Namely Zorin, and Void. I also need to look into a lightweight recommendation that's more simple than arch ootb. contenders are AntiX, Lubuntu, Peppermint, Puppy, and probably not TinyCore, but i'm noting it for myself since it may get an honorable mention.
>- **Distros no one's ever fucking heard of maintained by like one guy** - Who is this guy? IDK! is anyone reading his code? Fuck No! Can he be trusted to reliably get security updates out in a quality, timely manner? Nope! Random guy! Do you trust him to not push (accidentally or purposefully) malicious software? You shouldn't! Not to mention poor documentation and non-existent support. Its an immediate red-flag when anyone recommends distros like these. Not because they're malicious, but it shows they're either ill-informed or irresponsible. "oh, but ssh is maintained by one guy." Okay, ssh is also used by millions. There's actually eyes reading that code, and people trying to break it too! A lot of people and companies are invested in ssh being secure, and make sure that's the case. No one's reading the code for epicshitpissy-linux.
#### [Linux Mint](https://linuxmint.com)
"Just werks"/"beginner" distro based on Ubuntu (which is based on Debian). 
	If you dont know what to pick and dont know what all the jargon means, you can pick this to get started. Good for grandmas.
	That said, I dont like that its a fork of a fork, atop some other nitpicks. 
	- **If you're not afraid of computers, I'd like to push you to get Fedora**, even if you're new to Linux. Check it out below.
	- If you still want a noob-friendly distro and mostly just want to play games, check out Bazzite under Fedora.
#### 🌟 Fedora ([Workstation](https://fedoraproject.org/workstation/), [KDE Plasma](https://fedoraproject.org/kde/))
Fully-featured blank-slate with great OOTB defaults. Utilitarian.
	This is what I currently daily-drive. Fedora's intent is to stay up to date without breaking your system.
	The two versions are to pick your preferred DE (Gnome or KDE). If you're not sure which version to get, you can try both on a live-usb and see which you prefer. Pawsonally, I prefer Workstation.

Distros similar to or derived from Fedora:
	[Fedora Spins](https://fedoraproject.org/spins/)
		If you dont like Gnome or KDE, Fedora has "spins" for other desktop environments such as Xfce, Cinnamon, Sway, and more.
	[Universal Blue](https://universal-blue.org/)
		Series of images based on [Fedora Silverblue](https://fedoraproject.org/atomic-desktops/silverblue/) / [Kinoite](https://fedoraproject.org/atomic-desktops/kinoite/) of which Bazzite is one. With atomic distros, the less packages you layer on, the less surface area your OS has to break. I trust this team, so I think its a good idea to download one of these over Silverblue if it ships with what you'd be using on your system. Probably [Aurora](https://getaurora.dev/en) for general use.
	🌟 [Bazzite](https://bazzite.gg/)
		Noob-friendly distro based on [Fedora Silverblue](https://fedoraproject.org/atomic-desktops/silverblue/) / [Kinoite](https://fedoraproject.org/atomic-desktops/kinoite/), which makes it [immutable](https://youtu.be/9hiPFEUoUyI?t=86) (or "atomic" as Fedora likes to call it).
		A great alternative to SteamOS. Good for your handheld gaming PCs (including Steam Deck), or if you want to turn a desktop into a gaming console. Honestly can also serve you well as a regular desktop workstation if you're ok with your system being immutable. The \#GAMER distro.
	[Fedora Asahi Remix](https://asahilinux.org/fedora/)
		Made specifically to take advantage of the M-series chips on Apple Silicon Mac systems
		Takes a lot of bespoke work since the chips are mostly undocumented. I recommend Asahi only if your system uses one of those chips and under no other circumstance.
	 [OpenSUSE Tumbleweed](https://www.opensuse.org/#Tumbleweed)
		Not based on Fedora, but is similar in many ways.
		They reproduce a lot of the same work and use the same package manager as Fedora, but OpenSUSE might be a bit better if you're something like a sysadmin. The main advantage over Fedora in my opinion is [YaST](https://yast.opensuse.org/), which is a really nice settings suite. It doesn't sound all that hot on paper, but its cool. OpenSUSE is also rolling release, but they test packages for two weeks before shipping, which means stuff breaks less often. Very cool.

>[!warning]- Beware Fedora repackages
>Fedora often repackages software from other developers themselves, which would normally be fine, but they tend to break software a lot.
>I have no idea why they still insist on doing this and developers hate it.
>At the very least when installing from Flathub, always make sure you're installing the Flathub package, and not Fedora's Flatpak repackaging. Off the top of my head, i know that Bottles, OBS, and VLC are all jank when using Fedora's repackages instead of the official Flatpaks.
#### [Arch](https://archlinux.org/)
The hobbyist's DIY distro. If you want to use it, you ought to know how to [RTFM](https://en.wikipedia.org/wiki/RTFM)
	Arch is a rolling release distro that ships bleeding edge software, so be prepared for things to break when you're updating. Though, you also get everything before anyone else, and for the newest hardware.
	Using Arch also gives you access to the Arch User Repository (AUR), which is full of community maintained packages (dont use it if you dont know what you're doing, but you ought to if you're using Arch).
	Try Arch if you like control and fixing things.
	Oh, and its super lightweight too (since it sort of comes with nothing), so put it on your old laptop if u want.
	If you install Arch, please do some [basic security control](https://wiki.archlinux.org/title/Security).
	- [ArchInstall](https://github.com/archlinux/archinstall) - A script that helps you install Arch automatically and leaves you with a bare bones, bootable install that you can configure to your liking. Read more in the install script warning below.
>[!warning]- On ArchInstall (and other scripts)
>Part of me that doesn't want to recommend install-scripts for your first time.
>On the one hand, its an easy way to get a bootable Arch system with little hassle and you can go from there, then you get a nice lightweight distro out of it.
>On the other, you really should know how the system works to fix problems, and the installation is kind of like a tutorial in a way. Plus, doing everything manually gives you more control, which is kind of what Arch is about.
>Given its about control, though, the choice is ultimately up to you.
#### [NixOS](https://nixos.org/)
An immutable, reproducible, declarative distro. "Stability on the bleeding-edge". "Better arch", if you're brave enough to say such a thing.
	Both Nixpkgs stable and unstable have more packages (more fresh packages at that) than the AUR, which is impressive. Though a lot of these packages are unmaintained. Still impressive. 
	You configure your whole system in one file. Nix lets you easily reproduce it on another machine, roll back when something goes wrong, use a stable, rolling, (or both) release model, and more. Try out people's dotfiles from GitHub and just instantly undo them if they suck. Its cool. Not to mention flakes.
	To really utilize nix, you really need to sit down and learn how it works.
	 - [No Boilerplate's overview](https://www.youtube.com/watch?v=CwfKlX3rA6E), [Diinki's overview](https://www.youtube.com/watch?v=GkMEYlUHvTE)
### Other Usecase Distros
#### [Debian](https://www.debian.org/) 
Lightweight, reliable distro that lets you put machines to work.
	Shove it on your old devices and have them run localhost stuff, Minecraft or Jellyfin servers, or just compute this or that in the background. I love Debian.
	That said, its _not good as a daily-driver desktop workstation_.
	Debian is pretty late to update basically everything, which is very necessary for desktop. Once, there was a ram leak in Gnome 28 that Debain left unfixed for ~3 years, despite Gnome pushing a fix for it pretty quickly. Not to mention falling behind on features and improvements in all software you install on Debian.
	You can sometimes use Flatpaks to work around this limitation, but otherwise in the interest of not making a frankendebian, I recommend you use another distro for your daily driver.
#### [Bacotara](https://batocera.org/) 
Turn a USB into a portable emulation-focused distro running ES-DE.
	There's [a few other projects](https://emulation.gametechwiki.com/index.php/Recommended_Linux_distros#Emulation-focused) aiming for similar things, but most target raspberry-pi hardware or something similar.
#### [Qubes](https://www.qubes-os.org/)
Desktop comprised of virtual machines, so you can containerize everything.
	You're not going to be doing any serious gaming or anything else that requires a heavy workload on Qubes, but if you care a lot about privacy it may serve you well as a daily driver workstation, so long as you can handle the bottleneck inherent to running everything in a VM.
#### [Tails](https://tails.net/)
Privacy focused ephemeral OS running off a USB.
	Get in, do your business, and get out. Not a daily driver.
	It can launch on any computer you're able to pick the boot drive for and leave virtually little trace once you shut it down and unplug the usb. Uses the Tor network.
	Give it to people trying to arrange an out of state abortion, those stuck in domestic abuse situations, etc. Journalists, activists, and others whom need to turn any computer into their private machine for a bit will also benefit.
### Tools and Info
#### [But, Linux Is Bad! / OK, Who Is Linux NOT For?](https://rentry.co/95we932b)
A couple short paragraphs I wrote which I wanted to move off of the list to save space.
	Read it if the title seems relevant to you. (Yes, it is actually not for some people).
	Oh, and also: [Linux gets more FPS than Windows](https://www.youtube.com/watch?v=CJXp3UYj50Q). Better battery life too, if you're portable.
#### [Rufus](https://rufus.ie/en/)
Program for creating bootable USBs
	Because Windows doesn't have that functionality built in (Windows moment).
	You'll need it to install Linux if you're switching from windows.
	- [Etchdroid](https://play.google.com/store/apps/details?id=eu.depau.etchdroid) - Can be used to create a bootable linux USB instead of Rufus if you have an Android phone, but you'll need a way to write to a USB (i used an otg usb adapter, some phones come with one)
#### 🌐 [Awesome Linux Software](https://luong-komorebi.github.io/Awesome-Linux-Software/)
List of Linux applications and tools. Could be useful if you're just starting Linux for the first time.
	- [GitHub](https://github.com/luong-komorebi/Awesome-Linux-Software)
#### 🌐 [AreWeLibAdwaitaYet](https://arewelibadwaitayet.com/)
List of Linux applications using Adwaita.
	Huge if you use Gnome, since everything will look well integrated into your DE :)
## Fuck Windows, but...
Yes, Windows is dogshit spyware. If you haven't tried something else, you do not know how much better it can be.
Regardless, If you MUST use it for whatever reason, the following tools may prove useful.
#### [Microsoft Activation Scripts](https://github.com/massgravel/Microsoft-Activation-Scripts)
Easily activate Windows for free.
	Microsoft supplies free download links to much of their software (including [Windows 11](https://www.microsoft.com/software-download/windows11)) on their site, so you can just download the ISO officially, then activate it with MAS instead of paying.
#### [Windows 10 Updates after End Of Life (MAS)](https://massgrave.dev/windows10_eol)
Microsoft Activation Scripts' guide on getting security updates on Windows 10 after its EoL.
#### [Win11Debloat](https://github.com/Raphire/Win11Debloat)
Light PowerShell script to remove bullshit you dont need like spyware and Cortana.
	Does more too. Works for both 10 and 11.
#### [Winutil](https://github.com/ChrisTitusTech/winutil)
Registry quick-editor to easily customize Windows to your liking.
	Can also remove bloatey bullshit you don't need like spyware, ads, Cortana, etc. Meant to streamline installs, debloat, help troubleshooting, etc.
	Don't disable windows updates, dork.