# Ciberusps

Full-stack(front-end heavy) developer, passioned about games, contact me [telegram](https://t.me/Ciberus), [email](mailto:ciberus.ps+github@gmail.com)

### **Experience**

- Web - 4 years commercial - react, react native, nodejs, electron
- GameDev - unity 1,5 years commercial, UE4-UE5 - 5 months hobby, playcanvas - a bit hobby

### **Preferable techs**

react, react native, nodejs, nextjs, electron, typescript, koa, styled-components, eslint, prettier, postgresql, redis, sequelize, sentry, jest, expo, playcanvas, ue5

### **Projects**

[@winstrike](https://winstrike.gg/) - esports holding

- [@winstrike/booking-mobile-app](https://github.com/winstrike/booking-mobile-app) - react-native + expo "bare", developed mobile app for booking seats in computer clubs from scratch, links on [android](https://plyay.google.com/store/apps/details?id=gg.winstrike.booking), [ios](https://apps.apple.com/us/app/id1493178030?platform=iphone) and [screenshots](https://drive.google.com/drive/folders/19WL4fDZenSHa6JQpl0V69f9lds3cnyJs?usp=sharing)
  - made authentication flow - register, login, password reset, authentication with socials
  - onboarding flow - city selection, club selection, club info screen
  - booking flow - home screen, club section selection, section info screen, date and time selection screen, pack selection screen, seats selection screen, checkout screen and checkout webview with payment provider
  - announcements screen - one of the main communication channel with players, by clicking on push user sended on specific announcement
  - settings screen - u know editing user data, link socials and so on... those interesting things...
- [@winstrike/winstrike-id](https://github.com/winstrike/winstrike-id) - nextjs(🙃) + koa, developed authentication service from scratch using oauth2/openid, it used in all @winstrike products like booking-mobile-app, booking-api, booking-widget, overplay, admin-desktop. Improved in authentication a lot, read some tech specs about OAuth2/OpenID and authentication security
- [@winstrike/booking-api](https://github.com/winstrike/booking-api) - developed backend for sending notifications in `booking-api`
- [@winstrike/booking_admin](https://github.com/winstrike/booking_admin) - react + CRA, backoffice for computer clubs admins, reworked whole frontend, simplified routing and simplified UX.
- [@winstrike/booking-widget](https://github.com/winstrike/booking-widget) - react + CRA, slightly helped with frontend
- [@winstrike/admin-desktop](https://github.com/winstrike/admin-desktop) and [@winstrike/booking-desktop](https://github.com/winstrike/booking-desktop) - electron apps, fixed several issues
- [@winstrike/xxxtension](https://github.com/winstrike/xxxtension) - react + CRA, twitch extension
- [@winstrike/nivea-ultra-games](https://github.com/winstrike/nivea-ultra-games) - react + CRA + firebase, twitch extension, special project for nivea, with 4 mini-games
- overplay - storybook components, еще чет

Open source

- [FireSave](https://github.com/Ciberusps/FireSave) - pet-project, electron app, videogames saves manager
- [user-scripts](https://github.com/Ciberusps/user-scripts) - js scripts, some user scripts like dark theme for [dtf](https://dtf.ru), [vc](https://vc.ru/), [tjournal](https://tjournal.ru/) and [steam](https://store.steampowered.com/)
- [@winstrike/react-native-webview](https://github.com/winstrike/react-native-webview) - made fork with temporary fix for applepay, [issue described here](https://github.com/react-native-webview/react-native-webview/issues/920#issuecomment-720305564), [npm package](https://github.com/winstrike/react-native-webview/packages/610545)
- [playcanvas-typescript-example](https://github.com/Ciberusps/playcanvas-typescript-example) - js, playcanvas game engine, example of small FPS game written on typescript, as typesafe as possible and showing some approaches on how its possible to write code on with playcanvas [read forum post](https://forum.playcanvas.com/t/example-template-project-with-typescript/25272)
- [find-steam-app](https://github.com/Ciberusps/find-steam-app) - pet-project, nodejs lib, helps find location of an installed Steam app

### Other projects - dead, old and forgotten

<details>
  <summary>Click me</summary>

- [Artifaction.gg](https://artifaction.gg/)

  Site about Artifact | Full-stack developer | 09.2018 | [screenshots](https://drive.google.com/drive/folders/1RidLVceBWTP1dMExlAsfBqtLKODKQVo-?usp=sharing)

  Artifaction.gg - site about [valve](https://www.valvesoftware.com/en/) game - Artifact started by DOTA2/Esports enthusiasts well known in DOTA 2 community([@SirActionSlacks](https://twitter.com/@SirActionSlacks), [@Cyborgmatt](https://twitter.com/@Cyborgmatt), [@SUNSfanTV](https://twitter.com/@SUNSfanTV), [@bukkadota](https://twitter.com/@bukkadota), [@followNoxville](https://twitter.com/@followNoxville)) to build best community project where people may come for anything they want - casual videos, twitch shows, stats, tournaments, hot news, cards info, learning, cardsmith to make their own cards, deck builder, pathfinder and much more.

  I joined the team at the end of september. At start i wanted to make twitch extension - [concept here](https://imgur.com/a/xtcJO9o) later @bukkadota suggest me to help with site development and gave full freedom of choice of technology stack. 
  There was many changes in project structure/tech stack, here some solutions we use:
  - firebase cloud storage as CDN for UGC(raw images, thumbnails...)
  - firebase hosting - for static assets(js, html, css, images, fonts...)
  - cdn.artifaction.gg - repo for fetching images from artifact client and valve API -> processing them(trim, resize, convert) -> and save them in normalized structure. It use [ValveResourceFormat](https://github.com/SteamDatabase/ValveResourceFormat) to decompile assets from client.

  Techs: React, TypeScript, MobX, styled-components, Webpack, Babel, PostgreSQL, Redis, express, Knex.js, Objection.js, Twitch API, Quill, firebase - cloud storage, firebase - hosting, passport, passport-discord, passport-steam, pg, discord.js, nodemon, yarn, yarn workspaces, prettier, sharp, express-session

- [Bubble Text](https://github.com/dkubatko/BubbleText)

  Twitch extension | Front-End developer & Co-founder | 04.2018 | [screenshots](https://drive.google.com/drive/folders/1BqGewZzHA5TSAwPi0dftpX47z6NAYIo1?usp=sharing)

  First of several exts using "Bits in Extensions". Selected by [Twitch.tv](https://twitch.tv/) for feature placement.

  Bubble Text - allows streamers to install an interactive speech bubble on their stream. Viewers can then use bits to get a set of text, animation and bubble style that will be displayed on the stream. By providing a variety of options, bubble text assures a unique and personalized experience for every user. This extension makes viewers feel more engaged by providing a gateway from Twitch to streamer’s screen. For streamers, this extension gives an opportunity to monetize their stream by giving them a portion of each sale.

  Made in collaboration with [@drazzzer](https://twitter.com/drazzzer)(Kubatko Daniil)

  Techs: React, TypeScript, MobX, styled-components, Webpack, socket.io, Twitch API, Twitch Extensions

- [GameStat](https://github.com/Ciberusps/gamestat)

  Twitch extension | Owner | 09.2017 | [screenshots](https://drive.google.com/drive/folders/1sNbjxvxU9S5ONYIgdLiKe2Wjp81BRsth?usp=sharing)

  [Twitch extension](https://dashboard.twitch.tv/extensions/4xthrtbw4oqjxl478qsjspia8vt3ra) provide in-game statistics for the streamers currently support DOTA 2
  Also integrated data from awesome personal esports training lab - GOSU.AI u can read about it here

  Techs: React, Postman, PostgreSQL, Webpack, MobX, Redis, yarn, yarn workspaces, lodash, Twitch API, Twitch Extensions

  Metrics:
    Installs - 2950,
    Uninstalls - 824,
    Activations - 1603,
    Views - 8,477,823,
    Uniq Viewers - 4,899,421,
    Uniq Viewers(09.01-07.02) - 240,888,
    Clicks - 9,927,763,
    Uniq Interactions - 1,123,464,
    Uniq Interactions(09.01-07.02) - 64,278,

- Treasure Simulator 2

  Prototype | Owner | 24.01.2017 | [screenshots](https://drive.google.com/drive/folders/1LLXjpPTuQ2oZtjRJUZdJtH9Wfc0x2GQz?usp=sharing)

  Second version of my "Treasure Simulator DOTA 2" app.
  Refactored and updated "DOTA 2 Wiki Parser" to v2.
  
  Techs: Unity3D, C#, Texture Packer, PVRTC, Photoshop, base64, AES, Visual Studio, Resharper, git, Bitbucket

- Treasure Simulator DOTA 2
  App(Android) | Owner | 07.2015-01.2016 | [screenshots](https://drive.google.com/drive/folders/1GCXxMIleoelPnjUELFFsoc8NutS5F4r6?usp=sharing)

  App simulate opening treasures from DOTA 2.
  Items are parsed from DOTA 2 Wiki with my "DOTA 2 Wiki Parser"

  UPDATE: currently unavalable due to changed Google Play policies, need to rebuild app and publish again

  Metrics
    Installs - 53.48K,
    Average rating - 4.04,

- [DOTA 2 Wiki Parser v2](https://github.com/Ciberusps/DOTA2WikiParser-V2)

  Unity3D app | Owner | 24.01.2017 | [screenshots](https://drive.google.com/drive/folders/1f90i-dzKWVPdOX8FL9x-P8X2onVR-j2E?usp=sharing)

  Moved to Unity codebase of "DOTA 2 Wiki Parser" with updated UI. Made for "Treasure Simulator 2" project

  Techs: Unity3D, HtmlAgilityPack, Json.NET

- [DOTA 2 Wiki Parser](https://github.com/Ciberusps/DOTA2WikiParser)
  .NET app | Owner | 07.2015-01.2016 | [screenshots](https://drive.google.com/drive/folders/1onh7GwZ3jwnA8vEfDSsNAELFvGOaOgvl?usp=sharing)

  DOTA 2 Wiki(dota2.gamepedia.com) parser for "Treasure Simulator DOTA 2" project.

  Techs: C#, .NET, Visual Studio, Resharper, HtmlAgilityPack, MetroUI, MiniJSON

- [FilmSearch](https://github.com/Ciberusps/FilmSearch) - [screenshots](https://drive.google.com/drive/folders/1heH23KzEVfOLYKyKstQUVjo2dVF7XpMq?usp=sharing)
- [Yandex Mobilization 2016](https://github.com/Ciberusps/YandexMobilization) - [screenshots](https://drive.google.com/drive/folders/1EfgUdYRu1t3mWhriPp-LVpuJeoMVnQNM?usp=sharing)
- [InstaGallery](https://github.com/Ciberusps/insta-gallery)

</details>
