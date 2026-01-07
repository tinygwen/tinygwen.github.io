---
title: ⚗️ Mods and Extensions
description: Browser extensions, userscripts, and software mods
tags:
  - computers
---
# Browser Extensions
>[!important]- Having very few extensions is good privacy etiquette
>The more extensions you have the more unique your fingerprint is, which can be used to track you. If only 1000 users in the world have the same extensions you do, then it will be infinitely easier to use other identifying information in tandum with that to de-anonymize you. This is also true for 10, and 10000. Get uBlock Origin (or use Brave Shields) no matter what.
#### 🌟[uBlock Origin](https://ublockorigin.com/)
Adblocker, trojan/phishing blocker, tracker, "enable third-party cookies" blocker, custom blocker.
	Blocks the visible AND invisible shittyness that comes with ads and other bullshit. The internet's condom. A must install, if possible.	
	* [uBlock Origin Lite](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh) If your browser does not support [Manifest v2](https://youtu.be/nmO5dvn8jN0) extensions and you insist on using a browser other than Brave, Helium, or Firefox, use lite.
	* [uBO Filterlists](https://github.com/yokoffing/filterlists/tree/main)/ [r/uBlockOrigin's popular site solutions](https://www.reddit.com/r/uBlockOrigin/wiki/solutions/) Some extra filters and guidelines on how to filter properly if you're wanting to get into the weeds. I like some of the stuff under Annoyances (which remove stuff like "enable third-party cookies" and such). For example, I use [this filter](https://rentry.co/cfdx9d6w) to remove things that annoy me on Twitter. Site solutions also has a ton of stuff like removing YouTube Shorts and the like.
> [!info]- uBO doesn't work on most chromium based browsers anymore. | **[Youtube video with more info](https://youtu.be/nmO5dvn8jN0)** | Try Firefox, Brave, or Helium. **[[Hardware Software#Web Browsers|(click to jump)]]**.
> This is due to google's push for manifest v3 and its seemingly targeted approach to crippling adblock. If you want to use uBO, userscripts, and other extensions which rely on how manifest v2 handles extensions, please switch to Firefox and harden it. Alternatively, Brave and Helium have support for uBO and a few select other manifest v2 extensions built in.
#### 🌟[Sponsorblock](https://sponsor.ajay.app/)
Skip YouTube sponsors.
	Works better than you'd think it would. Also offers options to skip recaps, non-music sections of music videos, self-promo, and more. Segments are user submitted.
#### [DeArrow](https://dearrow.ajay.app/)
Alternative community sourced title/thumbnails to reduce clickbait.
	I recommend changing some settings to have the show original button to always display, and have the original title/thumb to display by default. That way you can just click a button next to a click-baity video to see the dearrow submitted title/thumbnail manually. I like this since it has a bad habit of spoiling some videos, and imo titles/thumbs are "part" of the video, artistically.
#### [Image Search Options](https://saucenao.com/tools/)
Reverse image search tool offered by [SauceNao](https://saucenao.com/).
#### [OneTab](https://www.one-tab.com/) 
Roll all (or individual) tabs into a single tab as a list.
	Save a ton of ram and clean up your tab bar with a single click. Great for tab hoarders like myself.
#### [Distracted](https://github.com/f1shy-dev/distracted)
Puts obstacles between you and the websites you habitually check
	You can use timers, hold to unlock, randomly generated strings, or no way to bypass at all. You can block at certain times of the day, can set how long the sites unlock for, and more.
#### [Indie Wiki Buddy](https://getindie.wiki/) 
Extension to avoid Fandom Wiki. Fuck Fandom!
	If a community has an independent wiki not hosted on fandom, this extension gives you options to add a redirect link, automatically redirect you, and/or remove fandom-hosted wiki results from search engines. Here's a [list](https://getindie.wiki/listings/) of wikis they support. For wikis that are still on Fandom, it also gives you options to view those wikis on alternative frontends like Breezewiki.
>[!note]- Unfortunately, IWB doesn't redirect wikis that have moved to [wiki.gg](https://wiki.gg/wikis/)
>but you can check wiki.gg's list (linked) for wikis they host. wiki.gg hosts many, and was created by a former Fandom and Gamepedia staff pair. It's essentially Gamepedia 2. It's not independent, but anything is preferable to fandom.
#### [Sky Follower Bridge](https://github.com/kawamataryo/sky-follower-bridge) (for Bluesky/bsky)
Automatically follow the Bluesky accounts of those you follow on Twitter.
	Scans your following page on Twitter and attempts to automatically find any Bluesky matches, then follows them.
	Isn't 100% accurate and may miss a couple, but as far as i'm concerned its 95% accurate. a disposable extension, uninstall when you're done with it.
#### [Annotations Restored](https://github.com/isaackd/AnnotationsRestored)
Restores archived YouTube annotations.
	I only use this when I know a video used to have annotations and hope they were preserved.

# Userscripts
>[!important]- userscripts will break in chromium browsers with manifest v3
> To continue using userscripts in chromium browsers i believe many developers of userscript extensions (such as violentmonkey) require you to turn on developer mode and configure from there. Follow the instructions that the developer of your preferred extension provides
#### [Violentmonkey](https://violentmonkey.github.io/) 
FOSS userscript manager.
Think of userscripts as website modifications, but without needing a full extension.
If an extension has a userscript version, jump for it. You can find some of the userscripts I use below. Violentmonkey is private and open source. You can also use [Greasemonkey](https://www.greasespot.net/) if you're having compatibility issues, but it's not as lightweight nor is it FOSS.
#### [Tampermonkey scripts list](https://www.tampermonkey.net/scripts.php)
Resources for finding new userscripts.
#### [TwitchAdSolutions](https://github.com/pixeltris/TwitchAdSolutions?tab=readme-ov-file) 
Block ads on Twitch.tv
video-swap-new and vaft provided on this page, i recommend those as they can be loaded as userscripts.
#### [BetterTTV](https://betterttv.com/) 
More emotes, features, etc for Twitch.
Select "other" browser even if your browser is supported for the userscript.
#### [4chan X](https://www.4chan-x.net/) 
Improve the UX of various Chan boards.
Thread watcher, view full image on hover, board hotbar, catalog default, keybinds, etc. Sorry for enabling you...
#### [Show Twitter Censored Media](https://greasyfork.org/en/scripts/491744-show-twitter-censored-media). 
Automatically un-spoiler sensitive images when browsing a user's media tab on Twitter.
#### [Twitter One Click Block](https://greasyfork.org/en/scripts/482477-one-click-copy-link-button-for-twitter-x) 
Adds a block button next to usernames on Twitter.
#### [Video Speed Buttons](https://greasyfork.org/en/scripts/30506-video-speed-buttons) 
Increase the playback of YouTube videos past 2x.
I recommend editing the userscript and changing the controller to VSC, since in my experience VSB slowly causes youtube to become unresponsive (changing it is easy).
# Discord
#### [Discord Client Encyclopedia](https://github.com/Discord-Client-Encyclopedia-Management/Discord3rdparties)
List of Discord clients, official and third-party, modded, desktop, iOS, and Android.
	Useful to see if your project is still being updated or what the new projects are.
#### [Vencord](https://vencord.dev/)  (Desktop Client)
Modified desktop client, with built-in plugins
	The plugins can be enabled and disabled as you wish.
	Tons of useful stuff here. You can also create/import custom themes using CSS.
#### 🌟 [Vesktop](https://github.com/Vencord/Vesktop) (Desktop Client)
Discord client based on the browser app, with Vencord pre-installed. Screenshare on Wayland.
	Also noticeably more lightweight. This is the client I recommend if you're on Linux.
#### 🌟 [Kettu](https://github.com/C0C0B01/Kettu) (Android Client)
Modified client for Discord's mobile app.
	If you don't know if your device is rooted, it isn't. Get plugins [Nexpid's Plugin Browser](https://bn-plugins.github.io/vd-proxy/vendetta.nexpid.xyz/plugin-browser/). Discord mobile modding is very volatile, so cross check with the client encyclopedia above if it loses support.
#### [Discord Embedder](https://discord.nfp.is/) 
Website that lets you paste links to videos that may not be embedding in Discord, and (sometimes) fixes them.
	Works with Catbox. If you remember how the FNAF movie was being passed around awhile ago, it was using this.
#### [Rebane's Discord Color Text Generator](https://rebane2001.com/discord-colored-text-generator/) 
Website that lets you generate colored text for Discord.
	[Here's a video explaining it](https://www.youtube.com/watch?v=VtdOJCEIpvQ)
#### [UnDiscord](https://victornpb.github.io/undiscord/)
Delete all your messages in a Discord channel or DM.
#### 🌟 Embed Fixer Proxy Sites
Some websites dont embed well on Discord, these fix that.
	These developers basically pull info from the website in question themselves then sends it to Discord in a way Discord better supports. They own, say, "fixupx.com", so when you link to that you're contacting their site, then they pull from Twitter.
	Just copy the url of whatever you want to share, then change the website name to the respective source you want to use:
	- Twitter: [fixupx.com](https://fixupx.com), [fxtwitter.com](https://fxtwitter.com), [girlcockx.com](https://girlcockx.com)
	- Bluesky: [bskx.app](https://bskx.app) [bsyy.app](https://bsyy.app)
	- Mastodon: [fx.zillanlabs.tech](https://fx.zillanlabs.tech)
	- Threads: [fixthreads.net](https://fixthreads.net)
	- Instagram: [fxstagram.com](https://fxstagram.com), [eeinstagram.com](https://eeinstagram.com), [uuinstagram.com](https://uuinstagram.com)
	- TikTok: [tnktok.com](https://tnktok.com)
	- Reddit: [vxreddit.com](https://vxreddit.com), [rxddit.com](https://rxddit.com)
	- Facebook: [facebed.com](https://facebed.com)
	- Pixiv: [phixiv.net](https://phixiv.net)
	- Twitch: [fxtwitch.seria.moe](https://fxtwitch.seria.moe)
	- Spotify: [fxspotify.com](https://fxspotify.com)
	- DeviantArt: [fixdeviantart.com](https://fixdeviantart.com)
	- FurAffinity: [xfuraffinity.net](https://xfuraffinity.net)
	- Tumblr: [tpmblr.com](https://tpmblr.com)
	- YouTube: [koutube.com](https://koutube.com)
	- Billibilli: [vxbilibili.com](https://vxbilibili.com)
	- [EmbedEZ](https://embedez.com/) might work for anything else.
	If you want a Discord bot that can fix links automatically, you can use [FixTweetBot](https://github.com/Kyrela/FixTweetBot) which has support for all these sites (and many more)