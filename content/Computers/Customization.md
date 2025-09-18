---
title: ⚗️ Customization
description: Browser extensions, userscripts, and software mods.
---
> [!tip] Also check out [[Videogames#[SteamGridDB](https //www.steamgriddb.com/)|SteamGridDB and Millennium]] for Steam customization!
# Browser Extensions
>[!important]- Having very few extensions is good privacy etiquette
>The more extensions you have the more unique your fingerprint is, which can be used to track you. If only 1000 users in the world have the same extensions you do, then it will be infinitely easier to use other identifying information in tandum with that to de-anonymize you. This is also true for 10, and 10000. Get uBlock Origin (or use Brave Shields) no matter what.
#### 🌟[uBlock Origin](https://ublockorigin.com/)
Adblocker, trojan/phishing blocker, tracker, "enable third-party cookies" blocker, custom blocker. Blocks the visible AND invisible shittyness that comes with ads and other bullshit. The internet's condom. A must install, if possible.
> [!info]- uBO will break on chromium based browsers soon. | **[Youtube video with more info](https://youtu.be/nmO5dvn8jN0)** | Try firefox or brave **[[Hardware and Software#Web Browsers|(click to jump)]]**.
> This is due to google's push for manifest v3 and its seemingly targeted approach to crippling adblock. If you want to use uBO, userscripts, and other extensions which rely on how manifest v2 handles extensions, please switch to firefox and harden it. Alternatively, brave has support for uBO and a few select other manifest v2 extensions built in.
* [uBlock Origin Lite](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh) If your browser does not support [Manifest v2](https://youtu.be/nmO5dvn8jN0) extensions and you insist on using a browser other than brave or firefox, use lite.
* [uBO Filterlists](https://github.com/yokoffing/filterlists/tree/main)/ [r/uBlockOrigin's popular site solutions](https://www.reddit.com/r/uBlockOrigin/wiki/solutions/) Some extra filters and guidelines on how to filter properly if you're wanting to get into the weeds. I like some of the stuff under Annoyances (which remove stuff like "enable third-party cookies" and such). For example, i use [this filter](https://rentry.co/cfdx9d6w) to remove things that annoy me on twitter.
#### 🌟[Sponsorblock](https://sponsor.ajay.app/)
Skip youtube sponsors. Works better than you'd think it would. Also offers options to skip recaps, non-music sections of music videos, self-promo, and more.
#### [DeArrow](https://dearrow.ajay.app/)
Alternative community sourced title/thumbnails to reduce clickbait. I recommend changing some settings to have the show original button to always display, and have the original title/thumb to display by default. That way you can just click a button next to a click-baity video to see the dearrow submitted title/thumbnail manually. I like this since it has a bad habit of spoiling some videos, and imo titles/thumbs are "part" of the video, artistically.
#### [Image Search Options](https://saucenao.com/tools/)
Reverse image search tool offered by SauceNao.
#### [OneTab](https://www.one-tab.com/) 
Save a ton of ram and clean up your tab bar with a single click. It'll roll all (or individual) tabs into a single tab as a list. It's OP, great for tab hoarders like myself.
#### [Indie Wiki Buddy](https://getindie.wiki/) 
Fuck Fandom Wiki! If a community has an independent wiki not hosted on fandom, this extension gives you options to add a redirect link, automatically redirect you, and/or remove fandom-hosted wiki results from search engines. Here's a [list](https://getindie.wiki/listings/) of wikis they support. For wikis that are still on Fandom, it also gives you options to view those wikis on alternative frontends like Breezewiki.
>[!note]- Unfortunately, IWB doesn't redirect wikis that have moved to [wiki.gg](https://wiki.gg/wikis/)
>but you can check wiki.gg's list (linked) for wikis they host. wiki.gg hosts many, and was created by a former Fandom and Gamepedia staff pair. It's essentially Gamepedia 2. It's not independent, but anything is preferable to fandom.
#### [Sky Follower Bridge](https://github.com/kawamataryo/sky-follower-bridge) (for Bluesky/bsky)
Scans your following page on twitter and attempts to automatically find any matches for those users' respective accounts on bluesky. Isn't 100% accurate and may miss a couple, but as far as i'm concerned its 95% accurate. a disposable extension, uninstall when you're done with it.
#### [Annotations Restored](https://github.com/isaackd/AnnotationsRestored)
Restores archived YouTube annotations. I only use this when I know a video used to have annotations and hope they were preserved.

# Userscripts
>[!important]- userscripts will break in chromium browsers with manifest v3
> To continue using userscripts in chromium browsers i believe many developers of userscript extensions (such as violentmonkey) require you to turn on developer mode and configure from there. Follow the instructions that the developer of your preferred extension provides
#### [Violentmonkey](https://violentmonkey.github.io/) 
An extension that lets you load userscripts. Think of them like modifications to websites, without being their own full extension. If an extension has a userscript version, jump for it. You can find some of the userscripts I use below. Violentmonkey is private and open source. You can also use [Greasemonkey](https://www.greasespot.net/) if you're having compatibility issues, but it's not as lightweight nor is it FOSS.
#### [Tampermonkey scripts list](https://www.tampermonkey.net/scripts.php)
Page listing resources for finding new userscripts.
#### [4chan X](https://www.4chan-x.net/) 
Chan boards it supports are much more annoying to navigate without it. Thread watcher, view full image on hover, board hotbar, catalog default, keybinds, etc.
#### [BetterTTV](https://betterttv.com/) 
More emotes, features, etc for twitch. Select "other" browser even if your browser is supported for the userscript.
#### [Show Twitter Censored Media](https://greasyfork.org/en/scripts/491744-show-twitter-censored-media). 
Automatically unspoilers sensitive images when browsing a user's media tab on twitter
#### [Twitter One Click Block](https://greasyfork.org/en/scripts/482477-one-click-copy-link-button-for-twitter-x) 
adds a block button next to people's usernames on twitter
#### [TwitchAdSolutions](https://github.com/pixeltris/TwitchAdSolutions?tab=readme-ov-file) 
video-swap-new and vaft are userscripts provided on this page which can block ads on twitch, sense those tend to get through adblock.
#### [Video Speed Buttons](https://greasyfork.org/en/scripts/30506-video-speed-buttons) 
lets you increase the playback of youtube videos past 2x. I recommend editing the userscript and changing the controller to VSC, since in my experience VSB slowly causes youtube to become unresponsive (changing it is easy).
# Discord Modifications
#### [Vencord](https://vencord.dev/) 
A modified desktop client. However, this one comes bundled with all of its plugins, and the plugins can be enabled and disabled as you wish. Tons of useful stuff here. You can also create/import custom themes using css
#### 🌟 [Vesktop](https://github.com/Vencord/Vesktop)
A Discord client based on the browser version of the app, with vencord pre-installed. Offers better privacy as well as screenshare support on linux with wayland. Its also noticeably more lightweight. This is the client I recommend if you're on linux.
#### 🌟 [Bunny](https://github.com/pyoncord/Bunny)
A modified client for Discord's mobile app. If you don't know if your device is rooted, it isn't. Get plugins from [bn-plugins](https://bn-plugins.github.io/vd-web/) or by installing [Nexpid's Plugin Browser](https://bn-plugins.github.io/vd-proxy/vendetta.nexpid.xyz/plugin-browser/) (available on bn-plugins). You're also able to use themes from [Revenge's Discord](https://discord.com/invite/ddcQf3s2Uq).
#### [Discord Embedder](https://discord.nfp.is/) 
Not an addon, just a website that lets you paste links to videos that may not be embedding in discord, and (sometimes) fixes them. Works with catbox. If you remember how the fnaf movie was being passed around awhile ago, it was using this.
#### [Rebane's Discord Color Text Generator](https://rebane2001.com/discord-colored-text-generator/) 
Not an addon, just a website that lets you generate colored text for discord. [Here's a video explaining it](https://www.youtube.com/watch?v=VtdOJCEIpvQ)
#### [BetterDiscord](https://betterdiscord.app/) 
Betterdiscord is a modified client for Discord on desktop. It does not come with all its plugins pre-installed like vencord does. You can find plugins from the [BetterDiscord Plugins](https://betterdiscord.app/plugins) site