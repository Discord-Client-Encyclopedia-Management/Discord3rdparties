# Discord Client Encyclopedia

<p align="center">
  <a href="https://discord.gg/3kv5yzTYQE">
    <img alt="Discord" src="https://img.shields.io/discord/1044501553731600414?color=%7767d2&label=Support%20Server&logo=discord&logoColor=%cd67d2&style=for-the-badge">
  </a>
</p>
<p align="center">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/Discord-Client-Encyclopedia-Management/Discord3rdparties?color=ec9c36&logo=github&style=for-the-badge">
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/Discord-Client-Encyclopedia-Management/Discord3rdparties?color=ec365a&logo=github&style=for-the-badge">
  <a href="https://github.com/Discord-Client-Encyclopedia-Management/Discord3rdparties/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/Discord-Client-Encyclopedia-Management/Discord3rdparties?style=for-the-badge">
  </a>
</p>



A non-exhaustive collection of third-party clients and mods for Discord.

## Table of Contents

- [Discord Client Encyclopedia](#discord-client-encyclopedia)
	- [Table of Contents](#table-of-contents)
	- [Mobile](#mobile)
		- [Android Clients \& Mods](#android-clients--mods)
		- [iOS Clients \& Mods](#ios-clients--mods)
	- [Desktop](#desktop)
		- [Official Clients](#official-clients)
		- [Mods](#mods)
			- [Plugin bundlers](#plugin-bundlers)
   		- [Wrappers/adapters/launchers for the official clients](#wrappersadapterslaunchers-for-the-official-clients)	 
		- [Third-Party Reimplementations](#third-party-reimplementations)
	- [Game console clients](#game-console-clients)
	- [Other clients](#other-clients)
	- [Third party server implementations](#third-party-server-implementations)
	- [Contributing](#contributing)
	- [Further comments](#further-comments)
	- [Disclaimer](#disclaimer)

## Mobile

### Android Clients & Mods

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Discord Android](https://play.google.com/store/apps/details?id=com.discord&fingerprint=1129189278619021403._iqMp85lJ8wwcey3i6XvuHeKLYA&attemptId=a267ef68-ca9f-435f-99a6-f6a11875cf6c) | Official Android client | [Closed source] | 🟢 Active |
| [VendroidEnhanced](https://github.com/VendroidEnhanced/Vendroid) | A fork of [Vencord/Vendroid](https://github.com/Vencord/Android) that improves upon the original project. | [![Kotlin][Kotlin-Badge]][Kotlin-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [Vendroid](https://github.com/Vencord/Vendroid) | [Vencord](https://github.com/Vendicated/Vencord) for Android! A WebView embedding the Discord site, loading [Vencord](https://github.com/Vendicated/Vencord) and adding some goodies. | [![Java][Java-Badge]][Java-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [Kettu](https://github.com/C0C0B01/Kettu) | A Discord mobile app client modification continuing [Bunny's](https://github.com/pyoncord/Bunny) mission | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Voxi](https://github.com/ApexTeamPL/voxi-bundle) | A Discord mobile app client, fork of [Revenge Classic](https://github.com/revenge-mod/revenge-bundle) with additional features | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [ShiggyCord](https://github.com/kmmiio99o/ShiggyCord) | Shiggy your Discord! Fork of [Kettu](https://codeberg.org/cocobo1/Kettu). Faster, refreshed, and with additional features. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Revenge](https://github.com/revenge-mod/Revenge) | A fork of [Bunny](https://github.com/pyoncord/Bunny) | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Aliucord](https://github.com/Aliucord/Aliucord) | A mod for the Android Discord app. | [![Kotlin][Kotlin-Badge]][Kotlin-Url] [![Java][Java-Badge]][Java-Url] | 🔵 Active *(Legacy App[^1]\)* |
| [Unbound](https://www.unbound.rip/) | Cross-platform client modification for discord on mobile. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 *(still in development state)* |
| [Revenge Next](https://github.com/revenge-mod/revenge-bundle-next) | A Discord mod for Android! | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 *(still in development state)* |
| [Rain](https://github.com/ra1ncord/rain) | A Discord mod for mobile written from the ground up by the creators of [Kettu](https://github.com/C0C0B01/Kettu) | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 *(still in development state)* |
| [ReCord](https://github.com/record-mod/record-bundle) | A work-in-progress Discord mod, inspired by mods such as Bunny and Revenge, aimed at being lightweight and user friendly. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 *(still in development state)* |
| [Wintry](https://github.com/amsyarasyiq/wintry) | Make your Discord cooler, literally | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Broken |
| [Lumi](https://github.com/C0C0B01/Lumi) | A Fork of [Wintry](https://github.com/amsyarasyiq/wintry) aiming to deliver a [Vencord](https://github.com/Vendicated/Vencord) like experience on android!| [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Bunny](https://github.com/pyoncord/Bunny) | A mod for Discord's mobile apps, fork of [Vendetta](https://github.com/vendetta-mod/Vendetta). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Vendetta](https://github.com/vendetta-mod/Vendetta) | A Discord mod that is compatible with Android and iOS! | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [CutTheCord](https://gitdab.com/distok/cutthecord) | Modular Client Mod for Discord's Android app. | [![Python][Python-Badge]][Python-Url] [![Java][Java-Badge]][Java-Url] | 🔴 Discontinued |
| [OpenCord](https://github.com/X1nto/OpenCord) | An open-source implementation of the Discord Android app | [![Kotlin][Kotlin-Badge]][Kotlin-Url] | 🔴 Discontinued |
| [Treecord](https://github.com/Treecord/Treecord) | A modded Discord client for Android! | [![Shell Script][Shell Script-Badge]][Shell Script-Url] | 🔴 Discontinued |
| Bluecord | Modded client mod for Android | [Closed source] | ⛔ Malware (scams and spying)[^8] |

### iOS Clients & Mods

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Discord iOS](https://apps.apple.com/us/app/discord-chat-talk-hangout/id985746746) | Official iOS client | [Closed source] | 🟢 Active |
| [Kettu](https://github.com/C0C0B01/Kettu) | A Discord mobile app client modification continuing [Bunny's](https://github.com/pyoncord/Bunny) mission | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [BTLoader](https://github.com/CloudySn0w/BTLoader) | Provides builds of [Kettu](https://github.com/C0C0B01/Kettu) (a fork of [Bunny](https://github.com/pyoncord/Bunny)) for iOS, but will utilise [Rain](https://github.com/ra1ncord/rain) once it is fully released.| [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Stossycord](https://github.com/Stossycord/Stossycord) | Stossycord is a Discord Client Native to iOS Devices. It is made in 100% Swift and SwiftUI for Privacy, Responsiveness and Security | [![Swift][Swift-Badge]][Swift-Url]    | 🟠🔵 Active *(In a very early beta)* |
| [Unbound](https://www.unbound.rip/) | Cross-platform client modification for discord on mobile. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 *(still in development state)* |
| [Rain](https://github.com/ra1ncord/rain) | A Discord mod for mobile written from the ground up by the creators of [Kettu](https://github.com/C0C0B01/Kettu) | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 *(still in development state)* |
| [Revenge](https://github.com/revenge-mod/Revenge) | Revenge is a fork of [Bunny](https://github.com/pyoncord/Bunny) | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Bunny](https://github.com/pyoncord/Bunny) | A mod for Discord's mobile apps, fork of [Vendetta](https://github.com/vendetta-mod/Vendetta). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Vendetta](https://github.com/vendetta-mod/Vendetta) | A Discord mod that is compatible with Android and iOS! | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Enmity](https://enmity.unbound.rip/) | The power of addons, all in your hand. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Discord Classic](https://github.com/cellomonster/iOS-Discord-Classic) | A bare-bones Discord client for iOS 5 and 6. | [![Objective-C][Objective-C-Badge]][Objective-C-Url] | 🔴 Discontinued |
| [Discord Classic (continuation)](https://github.com/ToruTheRedFox/iOS-Discord-Classic) | Discord client for Legacy iOS with enhanced UI and additional features. <br/> Based off the original Discord Classic. | [![Objective-C][Objective-C-Badge]][Objective-C-Url] | ⛔ Active. May get account banned. |

## Desktop

### Official Clients

| Name | Link | Infos |
| :---: | :---: | :---: |
| [Discord](https://discord.com) | [Web](https://discord.com/app), [Windows](https://discord.com/api/download/stable?platform=win), [macOS](https://discord.com/api/download/stable?platform=osx), [Debian/Ubuntu](https://discord.com/api/download/stable?platform=linux), [Tarball](https://discord.com/api/download/stable?platform=linux&format=tar.gz) | Main software |
| [Discord PTB](https://ptb.discord.com) | [Web](https://ptb.discord.com/app), [Windows](https://discord.com/api/download/ptb?platform=win), [macOS](https://discord.com/api/download/ptb?platform=osx), [Debian/Ubuntu](https://discord.com/api/download/ptb?platform=linux), [Tarball](https://discord.com/api/download/ptb?platform=linux&format=tar.gz) | Public Test Build |
| [Discord Canary](https://canary.discord.com) | [Web](https://canary.discord.com/app), [Windows](https://discord.com/api/download/canary?platform=win), [macOS](https://discord.com/api/download/canary?platform=osx), [Debian/Ubuntu](https://discord.com/api/download/canary?platform=linux), [Tarball](https://discord.com/api/download/canary?platform=linux&format=tar.gz) | Discord's [canary build](https://semaphoreci.com/blog/what-is-canary-deployment), releases features earlier than PTB |
| Discord Development | [Windows](https://discord.com/api/download/development?platform=win), [macOS](https://discord.com/api/download/development?platform=osx), [Debian/Ubuntu](https://discord.com/api/download/development?platform=linux), [Tarball](https://discord.com/api/download/development?platform=linux&format=tar.gz) | Essentially Discord's canary build but with updates a few days earlier |

### Mods

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [BeautifulDiscord](https://github.com/leovoel/BeautifulDiscord) | Simple Python script that adds CSS hot-reload to Discord. | [![Python][Python-Badge]][Python-Url] | 🟢 Active |
| [BetterDiscord](https://betterdiscord.app/) | BetterDiscord extends the functionality of DiscordApp by enhancing it with new features.  | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [DiscoCSS](https://github.com/mlvzk/discocss) | A tiny Discord CSS injector for Linux and Mac OS. | [![Shell Script][Shell Script-Badge]][Shell Script-Url] | 🟢 Active |
| [Kernel](https://github.com/kernel-mod) | A super small and fast Electron client mod with the most capability. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Moonlight](https://moonlight-mod.github.io/) | Yet another Discord client mod, focused on providing a decent user and developer experience. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [OpenAsar](https://openasar.dev/) | Alternative `app.asar` for Discord. Makes your client feel snappier. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![Nim][Nim-Badge]][Nim-Url] | 🟢 Active |
| [reUpdater](https://github.com/cordpackers/reUpdater) | An open-source alternative to Discord's updater.node, featuring multithreaded downloads and allowing custom desktop client patches via an alternative update API. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Replugged](https://replugged.dev) | A lightweight Discord client mod focused on simplicity and performance. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [shelter](https://github.com/uwu/shelter) | shelter is a new generation client mod built to be essentially bulletproof (i.e. Discord switch to SWC). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Equicord](https://github.com/Equicord/Equicord) | Fork of Vencord with extra plugins and features. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Vencord](https://github.com/Vendicated/Vencord) | Proper context isolation, inline patches, Custom CSS, Useful™ plugins | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Voxa](https://github.com/plyght/voxa) | Voxa is a sleek, lightweight, and native macOS Discord client built using SwiftUI. | [![Swift][Swift-Badge]][Swift-Url] | 🟢 Active |
| [VX](https://github.com/doggybootsy/vx) | A lightweight client modification for Discord, compatible with the desktop, and web browser applications. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 Active *(Variable[^2]\)* |
| [Crycord](https://crycord.geopjr.dev/) | A Discord Client modification with plugins. Uses BeautifulDiscord's CSS injector. Oh it's also written in Crystal! | [![Crystal][Crystal-Badge]][Crystal-Url] | 🟠 On hiatus, since May 2021 |
| [Aero](https://github.com/aero-mod/aero) | A next-generation Discord mod empowering users and developers alike. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Cumcord](https://web.archive.org/web/20250101015227/https://github.com/Cumcord/Cumcord) | Cumcord is a Discord client mod that focuses on making the Discord plugin development experience easier. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [DrDiscord](https://github.com/Dr-Discord/DrDiscord) | A simple client mod *(compatible with other mods such as BD)* | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [Demoncord](https://web.archive.org/web/20240224170707/https://git.ruthenic.com/Demon/demoncord-rewrite) | A Discord client mod by satanists, for satanists. |[![JavaScript][JavaScript-Badge]][JavaScript-Url] |  🔴 Discontinued |
| [Suncord](https://github.com/verticalsync/Suncord) | A fork of Vencord. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Vizality](https://vizality.com/) | An Discord app client modification, allowing for a truly customizable experience through the use of plugins, themes, and built-in settings. *Runs on web browsers too* | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [Hykord](https://github.com/xHyroM/hykord) | xHyroM's @discord client modification. Supports BD themes and is working on BD and PC/RP plugin support. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] [![Zig][Zig-Badge]][Zig-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [EndPwn](https://github.com/EndPwnArchive) | An ASAR-based client modifcation for Discord. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [Yelm](https://github.com/adryd325/yelm) |  A private Discord client mod and datamining utility used and developed around mid 2017. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [EnhancedDiscord](https://github.com/joe27g/EnhancedDiscord) | A lightweight Discord client mod. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandoned |
| Acord Premium | A client you have to pay for that stole its code. | [Closed source] | ⛔ sus behavior (Stolen code) |
| hh3 | A private client mod. | [Closed source] | ⛔ *(Status[^4]\)*|
| [GooseMod](https://goosemod.com/) | GooseMod is a new, store-driven Discord mod. *Runs on web browsers too* | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [HolyMod](https://github.com/HolyMod/HolyMod) | A lightweight client mod focused on simplicity and performance. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| Lightcord | Lightcord is a simple and customizable client for Discord. | [Closed Source] | ⛔ sus behavior (Github and other stuff missing) |
| [Powercord](https://github.com/powercord-org/powercord) | A lightweight Discord client mod focused on simplicity and performance. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Topaz](https://web.archive.org/web/20230920032845/https://topaz.goosemod.com/) | Topaz is an upcoming mod which aims to be "next-gen" by using advanced tech to add never-before-seen innovative features. *Runs on web browsers too* | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [Velocity](https://github.com/Velocity-Discord/Velocity) | Velocity is a Discord Client modification that allows you to extend discord's functionality and capabilities. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |

#### Plugin bundlers

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Ittai (AAGaming's fork)](https://git.catvibers.me/Ittai/ittai) | Fork of Ittai that can bundle plugins to BetterDiscord, Powercord and Goosemod, making a plugin cross-platform. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Ittai (Original)](https://github.com/Kyza/ittai) | Bundler for BetterDiscord, Powercord and Goosemod, making a plugin cross-platform. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [BetterDiscordBuilder](https://github.com/BetterDiscordBuilder/bdbuilder) | Simplified plugin bundler for BetterDiscord. Supports JSX/TSX and TypeScript | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |

### Wrappers/adapters/launchers for the official clients

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Datcord](https://github.com/gamingdoom/datcord) | An open-source discord client using firefox. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 On hiatus, since Feb 2025 |
| [Dorion](https://github.com/SpikeHD/Dorion) | Lightweight alternative Discord client with a smaller footprint and some fancy extensible features | [![Rust][Rust-Badge]][Rust-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url]  | 🟢 Active |
| [GoofCord](https://github.com/Milkshiift/GoofCord) | A privacy-focused client with features like message encryption, script loading, and more. Based on ArmCord. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [LegCord](https://github.com/legcord/legcord) | LegCord is a custom client designed to enhance your Discord experience while keeping everything lightweight. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Vesktop](https://github.com/Vencord/Vesktop) | Vesktop is a cross platform desktop app aiming to give you a snappier Discord experience with Vencord pre-installed | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Equibop](https://github.com/Equicord/equibop) | Fork of Vesktop with extra plugins and features. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [WebCord](https://github.com/SpacingBat3/WebCord) | A Discord API-less client made with Electron | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 Active *(Variable[^2]\)* |
| [ChimeraCord](https://github.com/RoboChimera/ChimeraCord) | A functional but elegant unofficial Discord client for freeBSD, that aims for feature-parity with the official Discord client. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 On hiatus, since 2023 |
| [Discord-PWA](https://github.com/NeverDecaf/discord-PWA) | A wrapper for the Discord web client as a Progressive Web Application, for use with Chromium based browsers. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 On hiatus, since 2023 |
| [LemonCord](https://github.com/japandotorg/LemonCord) | A fast & light weight Discord Client made with love using the Rust programming language. | [![Rust][Rust-Badge]][Rust-Url] | 🟠 On hiatus, since 2023 |
| [Themecord](https://github.com/Theme-Cord/ThemeCord) | A lightweight application that allows users to customize the appearance of their Discord client using custom CSS themes. | [![Python][Python-Badge]][Python-Url] | 🟠 On hiatus, since Jun 2023 |
| [Discord-Sandbox](https://github.com/khlam/discord-sandboxed) | Open-source Sandbox Discord client for the privacy-minded. Say NO to intrusive data collection. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 On hiatus, since 2022 |
| [NativeCord](https://github.com/andre4ik3/NativeCord) | SSB (site-specific browser) for Discord. In other words, all it does is load Discord as a website... in an app. | [![Swift][Swift-Badge]][Swift-Url] | 🟠 On hiatus, since March 2022 |
| ~~[ArmCord](https://github.com/armcord/armcord)~~ | ArmCord is a custom client designed to enhance your Discord experience while keeping everything lightweight. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | ⛔ DMCA'd by ARM, rebranded to LegCord |
| [Sunroof](https://github.com/verticalsync/Sunroof) | A fork of Vesktop. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Discord-Lite](https://web.archive.org/web/20221230055539/https://github.com/therealcyber71/Discord-Lite) | A Light-Weight Discord Client written in Python for developers, by developers. | [![Python][Python-Badge]][Python-Url] | 🔴 Discontinued, Developer MIA, repo and account deleted |
| [2018cord](https://github.com/OldCord-Client/2018Cord) | A Client meant to replicate the look, and feel of Discord in 2018 | [![Python][Python-Badge]][Python-Url] | 🔴 Discontinued/ Abandon |
| [Discord Tauri](https://github.com/DiscordTauri/discord-tauri) |A lightweight Discord wrapper made in Tauri | [![Rust][Rust-Badge]][Rust-Url] | 🔴 Discontinued |
| [FeatherCord](https://github.com/OfficiallySp/FeatherCord) | FeatherCord is a lightweight alternative to the Discord client and uses up to 25% less resources compared to the default desktop client. | [Closed source] | 🔴 Discontinued |
| [GTK3cord](https://github.com/diamondburned/gtkcord3) | A Gtk3 Discord client in Golang | [![Go][Go-Badge]][Go-Url] | 🔴 Discontinued. development shifted to GTK4cord |
| [Rikka](https://github.com/rikka-org/Rikka) | Rikka is a fast, powerful, and extendable Discord modification. It can load plugins, manage plugins, and features a rich API. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] [![JavaSript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [RyU](https://github.com/Muunatic/RyU) | Powerful Discord Client written in JavaScript. Lightweight, Efficient, Feature-rich. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Broken |
| [Voidcord](https://web.archive.org/web/20230517194514/https://github.com/logoskosmos/voidcord) | A lightweight and extendable Discord web client on top of Neutralinojs. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued, Developer repo and account deleted |

### Third-Party Reimplementations

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Abaddon](https://github.com/uowuo/abaddon) | Alternative Discord client made in C++ with GTK | [![C++][C++-Badge]][C++-Url] | 🟢 Active |
| [AeroChat](https://aerochat.live/) | A Discord client themed to look like WLM 09. | [![React][React-Badge]][React-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url]| 🟢 Active |
| [Discord Lite](https://github.com/dosdude1/discord-lite) | An ultra-lightweight native Discord client for vintage and modern MacOS | [![Objective-C][Objective-C-Badge]][Objective-C-Url] | 🟢 Active |
| [Discord Messenger-DM](https://github.com/DiscordMessenger/dm) |Discord Messenger is a free Discord-compatible messaging client targeting both new and old Windows.  | [![C++][C++-Badge]][C++-Url] |  🟢 Active |
| [EveryDiscord](https://github.com/gaouservbf/EveryDiscord) |EveryDiscord is a light-weight FOSS Win32 client targeting old Windows, specifically NT5 but still trying to run on MS-DOS based Windows. Supports built-in plugins.  | Visual Basic 6.0 |   🟢 Active |
| [Discordo](https://github.com/ayntgl/discordo) | A lightweight, secure, and feature-rich Discord terminal client | [![Go][Go-Badge]][Go-Url] | 🟢 Active |
| [Oxicord](https://github.com/linuxmobile/oxicord) | Oxicord is a high-performance, memory-safe Discord TUI client written in Rust. | [![Rust][rust-Badge]][Rust-Url] | 🟢 Active |
| [Endcord](https://github.com/mzivic7/endcord) | Feature rich Discord TUI client, with RPC server, ascii art media player, message search and theming | [![Python][Python-Badge]][Python-Url] | 🟢 Active |
| [Fermi Chat](https://github.com/MathMan05/Fermi) |  A SpaceBar Client written in TS HTML and CSS | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active <br/> ⛔ Does not support discord.com instead is a spacebar client |
| [LibreDiscord](https://gitlab.com/zipdox/librediscord/-/tree/master?ref_type=heads) | LibreDiscord is a free and open source voice and video client for Discord written in C using GTK3 and GLib. | [![C][C-Badge]][C-Url] | 🟢 Active |
| [QTCord](https://github.com/mak448a/QTCord/) | A lightweight, native Discord client written in Python with QT. | [![Python][Python-Badge]][Python-Url] | 🟢 Active |
| [Unicord](https://github.com/UnicordDev/Unicord) | Discord Client for Windows 10 and Windows 10 Mobile | [![C#][C#-Badge]][C#-Url] | 🟢 Active |
| [Dissent](https://github.com/diamondburned/dissent) | Dissent (previously gtkcord4) is a third-party Discord client designed for a smooth, native experience on Linux desktops. | [![Go][Go-Badge]][Go-Url] | 🟢 Active <br/> ⛔ Does not mimic a real client[^7] |
| [MiniCord](https://github.com/thehatkid/Minicord) | A minimalist version of Discord based on the web version. | [![Python][Python-Badge]][Python-Url] | 🔵 Work In Progress </br>🟠 On hiatus, since Feb 2024  |
| [Paicord](https://github.com/llsc12/Paicord) | Discord client written in SwiftUI, with a goal of feature parity with customisation and Quality-of-Life additions! | [![Swift][Swift-Badge]][Swift-Url] | 🟢 Active  |
| [Spacebar Chat Client](https://spacebar.chat/) | Open source, themeable and extendable discord-compatible native Spacebar client | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟠 Inactive, Incomplete *(Variable[^5]\)* <br/> ⛔ Does not support discord.com instead is a spacebar client |
| [Accord](https://github.com/evelyneee/accord) | Client for modern Macs | [![Swift][Swift-Badge]][Swift-Url] | 🟠 On hiatus, since December 2022 |
| [Unofficial-discord-client](https://github.com/Coding-Bunker/unofficial-discord-client) | Unofficial client for discord build in C++ with Qt. | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since March 2022 |
| [Ripcord](https://cancel.fm/ripcord/) | Alternative desktop chat client for Slack (and Discord) designed for power users. | [Closed source] | 🔴 Broken *(Patchs[^3]\)* <br/> ⛔ *(Warning[^6]\)* |
| [MiniCord](https://github.com/OJddJO/MiniCord) | A minimalist version of Discord based on the web version. | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since Oct 2022  |
| [Swiftcord](https://github.com/cryptoAlgorithm/Swiftcord) | A completely native Discord client for macOS built 100% in Swift and SwiftUI! | [![Swift][Swift-Badge]][Swift-Url] | 🔴 Broken |
| [6cord](https://gitlab.com/diamondburned/6cord) | A terminal front-end for the Discord chat service | [![Go][Go-Badge]][Go-Url] | 🔴 Broken |
| [concord](https://github.com/volatide/concord) | Discord client made in Qt5 | [![Python][Python-Badge]][Python-Url] | 🔴 Discontinued |
| [Cordless](https://github.com/Bios-Marcel/cordless) | Cordless is a custom Discord client that aims to have a low memory footprint and be aimed at power-users. | [![Go][Go-Badge]][Go-Url] | 🔴 Broken, Developer got banned during development |
| [Discline](https://github.com/mitchweaver/Discline) | A terminal Discord client that you can actually use. | [![Python][Python-Badge]][Python-Url] | 🔴 Discontinued |
| [discord-curses](https://github.com/RX14/discord-curses) | Terminal-based discord client | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [DiscordFlex](https://github.com/ZenithRogue/DiscordFlex) | A custom Discord client built from the ground up. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![Vue.js][Vue.js-Badge]][Vue.js-Url] | 🔴 Discontinued |
| [DiscordQt](https://github.com/ruslang02/discord-qt) | A Discord desktop client powered by Node.JS and NodeGui. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [discord-screenaudio](https://github.com/maltejur/discord-screenaudio) | A custom Discord client that supports streaming with audio on Linux. | [![C++][C++-Badge]][C++-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [Discord-Terminal](https://web.archive.org/web/20221120040653/https://github.com/atlx/discord-term) | An extensible Discord terminal client. Can be used with bot or user tokens. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [Disorder](https://github.com/lexffe/discorder) | Command line discord client | [![Go][Go-Badge]][Go-Url] | 🔴 Discontinued |
| [Disrust](https://github.com/DvorakDwarf/disrust) | A discord TUI client written entirely in Rust | [![Rust][Rust-Badge]][Rust-Url] | 🔴 Discontinued |
| [Fast-Discord](https://github.com/EnyoYoen/Fast-Discord) | Client written in C++ and Qt | [![C++][C++-Badge]][C++-Url] | 🔴 Discontinued |
| [Harmony](https://github.com/hlafaille/Harmony) | A Java-based Discord client. | [![Java][Java-Badge]][Java-Url] | 🔴 Discontinued |
| [micro-discord](https://github.com/soukouki/micro-discord) | Simple discord client that doesn't use javascript | [![Ruby][Ruby-Badge]][Ruby-Url] | 🔴 Discontinued |
| [Mirdorph](https://gitlab.gnome.org/ranchester/mirdorph) | A crappy low feature Discord Client using libadwaita | [![Python][Python-Badge]][Python-Url] | 🔴 Discontinued |
| [Pesterchum-Discord](https://github.com/henry232323/Pesterchum-Discord) | A Discord client mimicking the Pesterchum chat client from Homestuck, for the few people who are still interested in that. | [![Python][Python-Badge]][Python-Url] | 🔴 Discontinued |
| [protocord](https://github.com/diamondburned/protocord) | A prototype CLI for a tiny Discord client. | [![Go][Go-Badge]][Go-Url] | 🔴 Discontinued |
| [Terminalcord](https://github.com/xynxynxyn/terminal-discord) | Simple terminal client for discord with a minimal look and UI. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [ToastCord](https://github.com/Traumatism/ToastCord) | Discord Terminal UI made in Python 3 | [![Python][Python-Badge]][Python-Url] | 🔴 Discontinued |

## Game console clients

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [A-client-for-Discord-for-3DS](https://github.com/XeathJP/A-client-for-Discord-for-3DS) | Applications that can use discord on 3DS | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since since January 2022 |
| [Quarrel](https://github.com/UWPCommunity/Quarrel) | Quarrel is a Discord client for Windows and Xbox that aims to bring voice chat to Xbox and improved support for varying screen sizes on devices running windows. | [![C#][C#-Badge]][C#-Url] | 🟠 On hiatus, since August 2022 |
| [NXCord](https://github.com/Grarak/NXCord) | Unofficial Nintendo Switch Discord client | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since April 2020 |
| [crcophony](https://github.com/freyamade/crcophony) | Fast, neat discord TUI written in Crystal (read: cacophony) | [![Crystal][Crystal-Badge]][Crystal-Url] | 🟠 On hiatus, since November 2019 |
| [VitaCord](https://github.com/devingDev/VitaCord) | Discord Client for PS Vita / PS TV | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since March 2018 |
| [Unofficial Discord 3DS Client](https://github.com/yourWaifu/Unofficial-Discord-3DS-Client) | This just a simple Discord client for the 3DS build using the `Sleepy Discord` library and the `Wslay` library. | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since November 2017 |
| [Switchcord](https://github.com/vbe0201/switchcord) | An unofficial Discord client for the Nintendo Switch console. | [![C++][C++-Badge]][C++-Url] | 🔴 Discontinued |
| [3DiScord](https://github.com/cheuble/3DiScord) | A Discord client for the Nintendo 3DS | [![C++][C++-Badge]][C++-Url] | ⛔ Discontinued. will get you banned |

## Other clients

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Discross](http://discross.rc24.xyz/index.html) | A webhook bridge to send messages on Discord through a webpage | [![JavaSript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [purple-discord](https://github.com/EionRobb/purple-discord) | A libpurple/Pidgin plugin for Discord | [![C][C-Badge]][C-Url] | 🟢 Active |
| [Reliable Discord-client IRC Daemon (rdircd)](https://github.com/mk-fg/reliable-discord-client-irc-daemon) | Reliable personal discord-client to irc-server translation daemon | [![Python][Python-Badge]][Python-Url] | 🟢 Active |
| [Sailcord (Previously SailDiscord)](https://github.com/roundedrectangle/SailDiscord) | A SailfishOS Discord Client | [![Python][Python-Badge]][Python-Url] [![Qt][Qt-Badge]][Qt-Url] | 🟢 Active |
| [discord-j2me](https://github.com/gtrxAC/discord-j2me) | Discord client for Java ME (MIDP 1.0 & 2.0) devices | [![Java][Java-Badge]][Java-Url] | 🟢 Active |
| [Weechat Discord](https://github.com/terminal-discord/weechat-discord) | Weechat plugin for Discord support. | [![Rust][Rust-Badge]][Rust-Url] | 🟢 Active |
| [DiskCord](https://github.com/maem0/diskcord) | Discord client for older web browsers </br> (made for BlackBerry10 OS in mind) | [![JavaSript][JavaScript-Badge]][JavaScript-Url] | 🟠🟢 Active, NEW be careful. |
| [DiscordBotClient](https://github.com/aiko-chan-ai/DiscordBotClient) | Discord Bot Client allows you to use your bot, just like any other user account. </br> (except Friends and Groups) | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active <br/> ⛔ This client is meant to be used with Discord Apps (Bots)  |
| [DiscordBotClient (2022 - 2025)](https://github.com/ChrisEric1/ChrisEric1.GitHub.io) | older-style Discord Bot Client (lighter, fewer features). | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active <br/> ⛔ This client is meant to be used with Discord Apps (Bots) |
| [Kori](https://github.com/cyan-2048/Discord4KaiOS) |Unofficial Discord Client for KaiOS made using SolidJS | [![TypeScript][TypeScript-Badge]][TypeScript-Url] |  🟢 Active |
| [Discord WAP](https://github.com/gtrxAC/discord-wap) |  Client for old mobile web browsers with Wireless Application Protocol 1.x support | [![JavaScript][JavaScript-Badge]][JavaScript-Url] |  🟢 Active |
| [Miranda NG](https://miranda-ng.org) | Multi Protocol Program that supports Discord | [![C++][C++-Badge]][C++-Url] | 🟢 Active | 
| [bitlbee-discord](https://github.com/sm00th/bitlbee-discord) | Discord protocol plugin for BitlBee. | [![C][C-Badge]][C-Url] | 🟠 On hiatus, since September 2021 |
| [discord-aos](https://github.com/ruslang02/discord-aos) | Discord client for Sailfish OS  | [![Qt][Qt-Badge]][Qt-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟠 On hiatus, since November 2021 |
| [crocodile](https://github.com/tbodt/crocodile) | Discord client for TempleOS. | [![Python][Python-Badge]][Python-Url] | 🟠 On hiatus, since November 2017 |
| [discord-ppc](https://github.com/vistafan12/discord-ppc) | Discord version for PowerPC architecture | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 On hiatus, since June 2017 |
| [Arcscord](https://github.com/Arcoz0308/arcscord) | NodeJS library written in typescript who interact with the Discord API | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |



## Third party server implementations

The following are server implementations that reimplement Discord's client-server API:

| Name | Features | Language(s) | Is Self-hostable | Development Status |
| :---: | :---: | :---: | :---: | :---: |
| [Polyphony](https://codeberg.org/polyphony) | Free, open source, federated communications software, compatible with the Discord API and built with [polyproto](https://polyproto.org/docs/intro/), Rust and love. | [![Rust][Rust-Badge]][Rust-Url] | 🟢 Yes | 🟠 Work in progress |
| [Spacebar Chat](https://spacebar.chat/) | Almost fully featured re-implementation of Discord API Server experimental branch implementing limited support for federation using ActivityPub as the server-server API | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Yes | 🟢 Active |
| [Hummus](https://hummus.sys42.net/) | 2017 Discord server reimplementation | [Closed source] | 🟠 Ask creator for permission | 🟢 Active |
| [Miranda NG](https://miranda-ng.org) | Multi Protocol Program that supports Discord | [![C++][C++-Badge]][C++-Url] | 🟢 Yes  | 🟢 Active |
| [Oldcord](https://github.com/oldcordapp/OldCordV3) | An open-source reimplementation of the old (2015-2018) Discord backend, including an on-demand client patcher. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Yes | 🔵 Active, official instance is down |
| [Reflectcord](https://github.com/V3L0C1T13S/reflectcord) | Reimplementation of Discord API Server on top of Revolt.chat | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Yes | 🟠 On hiatus, since Jan 2024 | 
| [Litecord](https://gitlab.com/litecord/litecord) | Partial reimplementation of Discord API Server | [![Python][Python-Badge]][Python-Url] | 🟠 Allowed, not intended | 🟠 On hiatus, since December 2023 |
| [Miranda NG](https://miranda-ng.org) | Multi Protocol Program that supports Discord | [![C++][C++-Badge]][C++-Url] | 🟢 Yes  | 🟢 Active | 

| AI  |     Description     |
| :-: | :-----------------: |
| 🚽  |     Vibe coded     |
| 💩  |     AI art used    |
| 🧻  |     AI assisted    |
| 🪠  | Previously used AI |
| 😇  |  No AI art used    |
| ❔  |  NA we don't know  |

[^1]: Aliucord is based on the legacy Discord Android app, which was replaced by RNA in 2022. Despite this, development efforts continue to backport features to Aliucord.
[^2]: Some occasional breaks might occur depending on the maintainers' free time.
[^3]: While the main client is still On hiatus, the community has made patchs for the client to extend its usages and fix bugs that have occured over time.
		- [Patcher](https://github.com/geniiii/patcher)
		- [Audio Hook](https://github.com/geniiii/ripcord-audio-hook)
[^4]: As of now we know little about this mod, but more info will be filled in as it is discovered.
[^5]: Client missing features SpaceBar server has. 
[^6]: Discord may temporarily suspend your account and ask you to reset password due to activities such as unauthorized token logins.
[^7]: Dissent makes no effort to spoof a real client, and intentionally omits `X-Super-Properties` among other things a real client has.
	  (source: [Hacker News](https://news.ycombinator.com/item?id=39763438))
	  Dissent may cause your account to be flagged as a spammer or cause it to be banned.
[^8]: While the owner does claim to have open-sourced the code, a long history of being behind scamming and stealing accounts has proven that they cannot be trusted nor any claims they make can be trusted. ([Source](https://drive.google.com/drive/folders/1Y2m2lMSpN3GlOcXyceaO88Ljnr8xuNcp?usp=drive_link))

## Contributing

Please refer to [CONTRIBUTING.md](/.github/CONTRIBUTING.md) if you want to contribute to this project.

## Further comments

Will update as needed!

If you would like feel free to reach out to [Nekopara#4266](https://discord.com/users/1074227433395470376) (Head of Team) on the official Discord:
https://discord.gg/qQQAnahBxZ

## Disclaimer

We (contributors) are not responsible for you getting banned from using a 3rd party or you getting kicked from servers.

[C-Badge]: https://img.shields.io/badge/C-%2300599C.svg?style=flat&logo=c&logoColor=white
[C-Url]: https://en.wikipedia.org/wiki/C_(programming_language) "C"

[C++-Badge]: https://img.shields.io/badge/C++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white
[C++-Url]: https://en.wikipedia.org/wiki/C++ "C++"

[C#-Badge]: https://img.shields.io/badge/C%23-%23239120.svg?style=flat&logo=c-sharp&logoColor=white
[C#-Url]: https://en.wikipedia.org/wiki/C_Sharp_(programming_language) "C#"

[Crystal-Badge]: https://img.shields.io/badge/Crystal-%23000000.svg?style=flat&logo=crystal&logoColor=white
[Crystal-Url]: https://en.wikipedia.org/wiki/Crystal_(programming_language) "Crystal"

[Dart-Badge]: https://img.shields.io/badge/Dart-%230175C2.svg?style=flat&logo=dart&logoColor=white
[Dart-Url]: https://en.wikipedia.org/wiki/Dart_(programming_language) "Dart"

[Go-Badge]: https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat&logo=go&logoColor=white
[Go-Url]: https://en.wikipedia.org/wiki/Go_(programming_language) "Go"

[Java-Badge]: https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white
[Java-Url]: https://en.wikipedia.org/wiki/Java_(programming_language) "Java"

[JavaScript-Badge]: https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E
[JavaScript-Url]: https://en.wikipedia.org/wiki/JavaScript "JavaScript"

[Kotlin-Badge]: https://img.shields.io/badge/Kotlin-%230095D5.svg?style=flat&logo=kotlin&logoColor=white
[Kotlin-Url]: https://en.wikipedia.org/wiki/Kotlin_(programming_language) "Kotlin"

[Nim-Badge]: https://img.shields.io/badge/Nim-%23161820.svg?style=flat&logo=nim&logoColor=%23ffe953
[Nim-Url]: https://en.wikipedia.org/wiki/Nim_(programming_language) "Nim"

[Objective-C-Badge]: https://img.shields.io/badge/Objective%20C-000000.svg?&style=flat&logo=Apple&logoColor=white
[Objective-C-Url]: https://en.wikipedia.org/wiki/Objective-C "Objective-C"

[Python-Badge]: https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54
[Python-Url]: https://en.wikipedia.org/wiki/Python_(programming_language) "Python"

[Qt-Badge]: https://img.shields.io/badge/Qt-%23217346.svg?style=flat&logo=Qt&logoColor=white
[Qt-Url]: https://en.wikipedia.org/wiki/QML "Qt"

[Ruby-Badge]: https://img.shields.io/badge/ruby-%23CC342D.svg?style=flat&logo=ruby&logoColor=white
[Ruby-Url]: https://en.wikipedia.org/wiki/Ruby_(programming_language) "Ruby"

[Shell Script-Badge]: https://img.shields.io/badge/Shell_Script-%23121011.svg?style=flat&logo=gnu-bash&logoColor=white
[Shell Script-Url]: https://en.wikipedia.org/wiki/Shell_script "Shell Script"

[Swift-Badge]: https://img.shields.io/badge/Swift-F54A2A?style=flat&logo=swift&logoColor=white
[Swift-Url]: https://en.wikipedia.org/wiki/Swift_(programming_language) "Swift"

[TypeScript-Badge]: https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white
[TypeScript-Url]: https://en.wikipedia.org/wiki/TypeScript "TypeScript"

[Vue.js-Badge]: https://img.shields.io/badge/Vue.js-%2335495e.svg?style=flat&logo=vuedotjs&logoColor=%234FC08D
[Vue.js-Url]: https://en.wikipedia.org/wiki/Vue.js "Vue.js"

[Zig-Badge]: https://img.shields.io/badge/Zig-%23F7A41D.svg?style=flat&logo=zig&logoColor=white
[Zig-Url]: https://en.wikipedia.org/wiki/Zig_(programming_language) "Zig"

[Rust-Badge]: https://img.shields.io/badge/Rust-%23000000.svg?&logo=Rust
[Rust-url]: https://en.wikipedia.org/wiki/Rust "Rust"

[React-Badge]: https://img.shields.io/badge/React-%2361DAFB?style=flat&logo=react&labelColor=black&color=blue
[React-url]: https://en.wikipedia.org/wiki/React_(software) "React"
