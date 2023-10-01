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
		- [Third-Party Reimplementations](#third-party-reimplementations)
	- [Console clients](#console-clients)
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
| [Aliucord](https://github.com/Aliucord/Aliucord) | A modification for the Android Discord app | [![Java][Java-Badge]][Java-Url] [![Kotlin][Kotlin-Badge]][Kotlin-Url] [![Dart][Dart-Badge]][Dart-Url] | 🔵 Active *(Out of date[^1]\)* |
| [Vencord](https://github.com/Vencord/Android) | Vencord for Android! A WebView embedding the Discord site, loading Vencord and adding some goodies. | [![Java][Java-Badge]][Java-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [Vendetta](https://github.com/vendetta-mod/Vendetta) | A Discord mod that is compatible with Android and iOS! | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [CutTheCord](https://gitdab.com/distok/cutthecord) | Modular Client Mod for Discord's Android app. | [![Python][Python-Badge]][Python-Url] [![Java][Java-Badge]][Java-Url] | 🟠 On hiatus, since August 2021 |
| [OpenCord](https://github.com/X1nto/OpenCord) | An open-source implementation of the Discord Android app | [![Kotlin][Kotlin-Badge]][Kotlin-Url] | 🟠 On hiatus |
| [Treecord](https://github.com/Treecord/Treecord) | A modded Discord client for Android! | [![Shell Script][Shell Script-Badge]][Shell Script-Url] | 🟠 On hiatus, since April 2021 |
| [Bluecord](https://github.com/bluemods/Bluecord) | Modded client mod for Android | [![Java][Java-Badge]][Java-Url] [![Kotlin][Kotlin-Badge]][Kotlin-Url] | 🔵 Active *(Out of date[^1]\)* |

### iOS Clients & Mods

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Discord iOS](https://apps.apple.com/us/app/discord-chat-talk-hangout/id985746746) | Official iOS client | [Closed source] | 🟢 Active |
| [Enmity](https://enmity.app/) | The power of addons, all in your hand. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Vendetta](https://github.com/vendetta-mod/Vendetta) | A Discord mod that is compatible with Android and iOS! | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Discord Classic](https://github.com/cellomonster/iOS-Discord-Classic) | A bare-bones Discord client for iOS 5 and 6. | [![Objective-C][Objective-C-Badge]][Objective-C-Url] | 🔴 Discontinued |

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
| [Aero](https://github.com/aero-mod/aero) | A next-generation Discord mod empowering users and developers alike. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [BeautifulDiscord](https://github.com/leovoel/BeautifulDiscord) | Simple Python script that adds CSS hot-reload to Discord. | [![Python][Python-Badge]][Python-Url] | 🟢 Active |
| [BetterDiscord](https://betterdiscord.app/) | BetterDiscord extends the functionality of DiscordApp by enhancing it with new features.  | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [DiscoCSS](https://github.com/mlvzk/discocss) | A tiny Discord CSS injector for Linux and Mac OS. | [![Shell Script][Shell Script-Badge]][Shell Script-Url] | 🟢 Active |
| [Hykord](https://github.com/xHyroM/hykord) | xHyroM's @discord client modification. Supports BD themes and is working on BD and PC/RP plugin support. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] [![Zig][Zig-Badge]][Zig-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [Kernel](https://github.com/kernel-mod) | A super small and fast Electron client mod with the most capability. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [OpenAsar](https://openasar.dev/) | Alternative `app.asar` for Discord. Makes your client feel snappier. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![Nim][Nim-Badge]][Nim-Url] | 🟢 Active |
| [Replugged](https://replugged.dev) | A lightweight Discord client mod focused on simplicity and performance. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [shelter](https://github.com/uwu/shelter) | shelter is a new generation client mod built to be essentially bulletproof (i.e. Discord switch to SWC). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Vencord](https://github.com/Vendicated/Vencord) | Proper context isolation, inline patches, Custom CSS, Useful™ plugins | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Vesktop](https://github.com/Vencord/Vesktop) | Vesktop is a cross platform desktop app aiming to give you a snappier Discord experience with Vencord pre-installed | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Vizality](https://vizality.com/) | An Discord app client modification, allowing for a truly customizable experience through the use of plugins, themes, and built-in settings. *Runs on web browsers too* | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active *(Closed Alpha)* |
| [Acord Standalone](https://github.com/acord-standalone) | Fix Discord’s sloppy jobs and breathe new life to the client. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 On hiatus |
| [Crycord](https://crycord.geopjr.dev/) | A Discord Client modification with plugins. Uses BeautifulDiscord's CSS injector. Oh it's also written in Crystal! | [![Crystal][Crystal-Badge]][Crystal-Url] | 🟠 On hiatus, since May 2021 |
| [Demoncord](https://git.ruthenic.com/Demon/demoncord-rewrite) | A Discord client mod by satanists, for satanists. |[![JavaScript][JavaScript-Badge]][JavaScript-Url] |  🟠 On hiatus, since September 2022 |
| [Cumcord](https://github.com/Cumcord/Cumcord) | Cumcord is a Discord client mod that focuses on making the Discord plugin development experience easier. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [EnhancedDiscord](https://github.com/joe27g/EnhancedDiscord) | A lightweight Discord client mod. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandoned |
| [GooseMod](https://goosemod.com/) | GooseMod is a new, store-driven Discord mod. *Runs on web browsers too* | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [HolyMod](https://github.com/HolyMod/HolyMod) | A lightweight client mod focused on simplicity and performance. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Lightcord](https://github.com/Lightcord/Lightcord) | Lightcord is a simple and customizable client for Discord. It includes BandagedBD, Glasstron and a discord.js-like api. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued, and abandoned |
| [Powercord](https://powercord.dev/) | A lightweight Discord client mod focused on simplicity and performance. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Topaz](https://topaz.goosemod.com/) | Topaz is an upcoming mod which aims to be "next-gen" by using advanced tech to add never-before-seen innovative features. *Runs on web browsers too* | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [Velocity](https://github.com/Velocity-Discord/Velocity) | Velocity is a Discord Client modification that allows you to extend discord's functionality and capabilities. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |

#### Plugin bundlers

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Ittai (AAGaming's fork)](https://git.catvibers.me/Ittai/ittai) | Fork of Ittai that can bundle plugins to BetterDiscord, Powercord and Goosemod, making a plugin cross-platform. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Ittai (Original)](https://github.com/Kyza/ittai) | Bundler for BetterDiscord, Powercord and Goosemod, making a plugin cross-platform. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 On hiatus, since March 2021 |
| [BetterDiscordBuilder](https://github.com/BetterDiscordBuilder/bdbuilder) | Simplified plugin bundler for BetterDiscord. Supports JSX/TSX and TypeScript | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |

### Third-Party Reimplementations

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Abaddon](https://github.com/uowuo/abaddon) | Alternative Discord client made in C++ with GTK | [![C++][C++-Badge]][C++-Url] | 🟢 Active |
| [Armcord](https://github.com/armcord/armcord) | ArmCord is a custom client designed to enhance your Discord experience while keeping everything lightweight. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [ChimeraCord](https://github.com/RoboChimera/ChimeraCord) | A functional but elegant unofficial Discord client for freeBSD, that aims for feature-parity with the official Discord client. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [Datcord](https://github.com/gamingdoom/datcord) | An open-source discord client using firefox. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [Discord-PWA](https://github.com/NeverDecaf/discord-PWA) | A wrapper for the Discord web client as a Progressive Web Application, for use with Chromium based browsers. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [Discord-Sandbox](https://github.com/khlam/discord-sandboxed) | Open-source Sandbox Discord client for the privacy-minded. Say NO to intrusive data collection. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [discord-screenaudio](https://github.com/maltejur/discord-screenaudio) | A custom Discord client that supports streaming with audio on Linux. | [![C++][C++-Badge]][C++-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [Discordo](https://github.com/ayntgl/discordo) | A lightweight, secure, and feature-rich Discord terminal client | [![Go][Go-Badge]][Go-Url] | 🟢 Active |
| [Dorion](https://github.com/SpikeHD/Dorion) | Lightweight alternative Discord client with a smaller footprint and some fancy extensible features | [![Rust][Rust-Badge]][Rust-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url]  | 🟢 Active |
| [FeatherCord](https://github.com/OfficiallySp/FeatherCord) | FeatherCord is a lightweight alternative to the Discord client and uses up to 25% less resources compared to the default desktop client. | [Closed source] | 🟢 Active |
| [GTK4cord](https://github.com/diamondburned/gtkcord4) | GTK4 Discord client in Go, attempt #4. | [![Go][Go-Badge]][Go-Url] | 🟢 Active |
| [LemonCord](https://github.com/japandotorg/LemonCord) | A fast & light weight Discord Client made with love using the Rust programming language. | [![Rust][Rust-Badge]][Rust-Url] | 🟢 Active |
| [RyU](https://github.com/Muunatic/RyU) | Powerful Discord Client written in JavaScript. Lightweight, Efficient, Feature-rich. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [Swiftcord](https://github.com/cryptoAlgorithm/Swiftcord) | A completely native Discord client for macOS built 100% in Swift and SwiftUI! | [![Swift][Swift-Badge]][Swift-Url] | 🟢 Active |
| [WebCord](https://github.com/SpacingBat3/WebCord) | A Discord API-less client made with Electron | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 Active *(Variable[^2]\)* |
| [Spacebar Chat](https://spacebar.chat/) | Open source, themeable and extendable discord-compatible native Spacebar client | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Discord Tauri](https://github.com/DiscordTauri/discord-tauri) |A lightweight Discord wrapper made in Tauri | [![Rust][Rust-Badge]][Rust-Url] | 🟠 On hiatus, since January 2023 FAQ states "Is this project abandoned? No" |
| [Disrust](https://github.com/DvorakDwarf/disrust) | A discord TUI client written entirely in Rust | [![Rust][Rust-Badge]][Rust-Url] | 🟠 On hiatus, since January 2023 |
| [Accord](https://github.com/evelyneee/accord) | Client for modern Macs | [![Swift][Swift-Badge]][Swift-Url] | 🟠 On hiatus, since December 2022 |
| [Unicord](https://github.com/UnicordDev/Unicord) | Discord Client for Windows 10 and Windows 10 Mobile | [![C#][C#-Badge]][C#-Url] | 🟠 On hiatus, since April 2022 |
| [NativeCord](https://github.com/andre4ik3/NativeCord) | SSB (site-specific browser) for Discord. In other words, all it does is load Discord as a website... in an app. | [![Swift][Swift-Badge]][Swift-Url] | 🟠 On hiatus, since March 2022 |
| [Unofficial-discord-client](https://github.com/Coding-Bunker/unofficial-discord-client) | Unofficial client for discord build in C++ with Qt. | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since March 2022 |
| [ToastCord](https://github.com/Traumatism/ToastCord) | Discord Terminal UI made in Python 3 | [![Python][Python-Badge]][Python-Url] | 🟠 On hiatus, since February 2022 |
| [Discord Lite](https://github.com/dosdude1/discord-lite) | An ultra-lightweight native Discord client for vintage and modern MacOS | [![Objective-C][Objective-C-Badge]][Objective-C-Url] | 🟠 On hiatus, since January 2022 |
| [Voidcord](https://github.com/kunamech/voidcord) | A lightweight and extendable Discord web client on top of Neutralinojs. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 On hiatus, since January 2022 |
| [Mirdorph](https://gitlab.gnome.org/ranchester/mirdorph) | A crappy low feature Discord Client using libadwaita | [![Python][Python-Badge]][Python-Url] | 🟠 On hiatus, since September 2021 |
| [Ripcord](https://cancel.fm/ripcord/) | Alternative desktop chat client for Slack (and Discord) designed for power users. | [Closed source] | 🟠 On hiatus, since July 2021 |
| [DiscordQt](https://github.com/ruslang02/discord-qt) | A Discord desktop client powered by Node.JS and NodeGui. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟠 On hiatus, since July 2021 |
| [concord](https://github.com/volatide/concord) | Discord client made in Qt5 | [![Python][Python-Badge]][Python-Url] | 🟠 On hiatus, since May 2021 |
| [protocord](https://github.com/diamondburned/protocord) | A prototype CLI for a tiny Discord client. | [![Go][Go-Badge]][Go-Url] | 🟠 On hiatus, since January 2021 |
| [Pesterchum-Discord](https://github.com/henry232323/Pesterchum-Discord) | A Discord client mimicking the Pesterchum chat client from Homestuck, for the few people who are still interested in that. | [![Python][Python-Badge]][Python-Url] | 🟠 On hiatus, since July 2020 |
| [DiscordFlex](https://github.com/ZenithRogue/DiscordFlex) | A custom Discord client built from the ground up. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![Vue.js][Vue.js-Badge]][Vue.js-Url] | 🟠 On hiatus, since May 2020 |
| [micro-discord](https://github.com/soukouki/micro-discord) | Simple discord client that doesn't use javascript | [![Ruby][Ruby-Badge]][Ruby-Url] | 🟠 On hiatus, since March 2018 |
| [Disorder](https://github.com/lexffe/discorder) | Command line discord client | [![Go][Go-Badge]][Go-Url] | 🟠 On hiatus, since November 2016 |
| [Fast-Discord](https://github.com/EnyoYoen/Fast-Discord) | Client written in C++ and Qt | [![C++][C++-Badge]][C++-Url] | 🔴 Discontinued |
| [Rikka](https://github.com/rikka-org/Rikka) | Rikka is a fast, powerful, and extendable Discord modification. It can load plugins, manage plugins, and features a rich API. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] [![JavaSript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [Harmony](https://github.com/hlafaille/Harmony) | A Java-based Discord client. | [![Java][Java-Badge]][Java-Url] | 🔴 Discontinued |
| [6cord](https://6cord.diamondb.xyz/) | A terminal front-end for the Discord chat service | [![Go][Go-Badge]][Go-Url] | 🔴 Discontinued |
| [Terminalcord](https://github.com/xynxynxyn/terminal-discord) | Simple terminal client for discord with a minimal look and UI. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued |
| [discord-curses](https://github.com/RX14/discord-curses) | Terminal-based discord client | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |
| [Discline](https://github.com/mitchweaver/Discline) | A terminal Discord client that you can actually use. | [![Python][Python-Badge]][Python-Url] | 🔴 Discontinued |
| [GTK3cord](https://github.com/diamondburned/gtkcord3) | A Gtk3 Discord client in Golang | [![Go][Go-Badge]][Go-Url] | 🔴 Discontinued. development shifted to GTK4cord |
| [Discord-Terminal](https://github.com/atlx/discord-term) | An extensible Discord terminal client. Can be used with bot or user tokens. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Discontinued, Looking for maintainers |
| [Cordless](https://github.com/Bios-Marcel/cordless) | Cordless is a custom Discord client that aims to have a low memory footprint and be aimed at power-users. | [![Go][Go-Badge]][Go-Url] | ⛔ Discontinued, Developer got banned during development |
| [Discord-Lite](https://web.archive.org/web/20221230055539/https://github.com/therealcyber71/Discord-Lite) | A Light-Weight Discord Client written in Python for developers, by developers. | [![Python][Python-Badge]][Python-Url] | 🔴 Discontinued, Developer MIA, repo and account deleted |

## Console clients

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Quarrel](https://github.com/UWPCommunity/Quarrel) | Quarrel is a Discord client for Windows and Xbox that aims to bring voice chat to Xbox and improved support for varying screen sizes on devices running windows. | [![C#][C#-Badge]][C#-Url] | 🟢 Active |
| [A-client-for-Discord-for-3DS](https://github.com/XeathJP/A-client-for-Discord-for-3DS) | Applications that can use discord on 3DS | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since since January 2022 |
| [crcophony](https://github.com/freyamade/crcophony) | Fast, neat discord TUI written in Crystal (read: cacophony) | [![Crystal][Crystal-Badge]][Crystal-Url] | 🟠 On hiatus, since November 2019 |
| [NXCord](https://github.com/Grarak/NXCord) | Unofficial Nintendo Switch Discord client | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since April 2020 |
| [Unofficial Discord 3DS Client](https://github.com/yourWaifu/Unofficial-Discord-3DS-Client) | This just a simple Discord client for the 3DS build using the `Sleepy Discord` library and the `Wslay` library. | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since November 2017 |
| [VitaCord](https://github.com/devingDev/VitaCord) | Discord Client for PS Vita / PS TV | [![C++][C++-Badge]][C++-Url] | 🟠 On hiatus, since March 2018 |
| [Switchcord](https://github.com/vbe0201/switchcord) | An unofficial Discord client for the Nintendo Switch console. | [![C++][C++-Badge]][C++-Url] | 🔴 Discontinued |
| [3DiScord](https://github.com/cheuble/3DiScord) | A Discord client for the Nintendo 3DS | [![C++][C++-Badge]][C++-Url] | ⛔ Discontinued. will get you banned |

## Other clients

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Discross](http://discross.rc24.xyz/index.html) | A webhook bridge to send messages on Discord through a webpage | [![JavaSript][JavaScript-Badge]][JavaScript-Url] | 🟢 Active |
| [purple-discord](https://github.com/EionRobb/purple-discord) | A libpurple/Pidgin plugin for Discord | [![C][C-Badge]][C-Url] | 🟢 Active |
| [Reliable Discord-client IRC Daemon (rdircd)](https://github.com/mk-fg/reliable-discord-client-irc-daemon) | Reliable personal discord-client to irc-server translation daemon | [![Python][Python-Badge]][Python-Url] | 🟢 Active |
| [Weechat Discord](https://github.com/terminal-discord/weechat-discord) | Weechat plugin for Discord support. | [![Rust][Rust-Badge]][Rust-Url] | 🟢 Active |
| [bitlbee-discord](https://github.com/sm00th/bitlbee-discord) | Discord protocol plugin for BitlBee. | [![C][C-Badge]][C-Url] | 🟠 On hiatus, since September 2021 |
| [crocodile](https://github.com/tbodt/crocodile) | Discord client for TempleOS. | [![Python][Python-Badge]][Python-Url] | 🟠 On hiatus, since November 2017 |
| [discord-aos](https://github.com/ruslang02/discord-aos) | Discord client for Sailfish OS  | [![Qt][Qt-Badge]][Qt-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟠 On hiatus, since November 2021 |
| [discord-ppc](https://github.com/vistafan12/discord-ppc) | Discord version for PowerPC architecture | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 On hiatus, since June 2017 |
| [Arcscord](https://github.com/Arcoz0308/arcscord) | NodeJS library written in typescript who interact with the Discord API | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Discontinued |

## Third party server implementations

The following are server implementations that reimplement Discord's client-server API:

| Name | Features | Language(s) | Development Status |
| :---: | :---: | :---: | :---: |
| [Reflectcord](https://github.com/V3L0C1T13S/reflectcord) | Reimplementation of Discord API Server on top of Revolt.chat, intended for self hosting | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Spacebar Chat](https://spacebar.chat/) | Almost fully featured re-implementation of Discord API Server, intended for self hosting | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Active |
| [Litecord](https://gitlab.com/litecord/litecord) | Partial reimplementation of Discord API Server, not intended for self hosting | [![Python][Python-Badge]][Python-Url] | 🟠 On hiatus, since May 2023 |

[^1]: Discord brought a breaking change for the mod in question.
[^2]: Some occasional breaks might occur depending on the maintainers' free time.

## Contributing

Please refer to [CONTRIBUTING.md](/.github/CONTRIBUTING.md) if you want to contribute to this project.

## Further comments

Will update as needed!

If you would like feel free to reach out to [Nekopara#4266](https://discord.com/users/1074227433395470376) (Head of Team) on the official Discord:
https://discord.gg/3kv5yzTYQE

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

[Java-Badge]: https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat&logo=java&logoColor=white
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

