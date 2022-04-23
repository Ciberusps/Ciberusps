# ciberusps

Full-stack(front-end heavy) developer, passioned about games

[telegram](https://t.me/Ciberus)

## Experience

- Web - 4 years commercial - react, react native, nodejs, electron
- GameDev - unity 1,5 years commercial, UE4-UE5 - 5 months hobby, playcanvas - a bit hobby

## Preferable techs

react, react native, nodejs, nextjs, electron, typescript, koa, nodejs, styled-components, eslint, prettier, postgresql, redis, sequelize, sentry, jest, expo, playcanvas, ue5

## Projects

[@winstrike](https://winstrike.gg/) - esports holding

- [@winstrike/booking-mobile-app](https://github.com/winstrike/booking-mobile-app) - react-native + expo "bare", developed mobile app for booking seats in computer clubs from scratch, spended most time on it links on [android](https://play.google.com/store/apps/details?id=gg.winstrike.booking) and [ios](https://apps.apple.com/us/app/id1493178030?platform=iphone)
  - made authentication flow - register, login, password reset, authentication with socials
  - onboarding flow - city selection, club selection, club info screen
  - booking flow - home screen, club section selection, section info screen, date and time selection screen, pack selection screen, seats selection screen, checkout screen and checkout webview with payment provider)
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

### Other projects - dead, old and forgotten

<details>
  <summary>Click me</summary>

- artifaction.gg
- bubbletext
- gamestat
- treasure simulator 2
- treasure simulator
- dota 2 wiki parser v2
- film search
- Yandex Mobilization 2016

</details>


## Technical challenges
- вроде с аутентификацией чет было
- вроде с пушами чет сложно было пезда
- аутентификация с помощью apple - ебола с server-side генерацией всяких сертификатов и типо что нужно пушить раз в полгода заново
- вроде с архитектурой booking-admin, message-manager и прочей хуйни было интересно
- архитектура приложения для кассиров, данно - касса и принтер для печати чеков, они при подключении торчат на localhost'е на разных портах, кассы и принтеры могут быть от разных производителей. Нам нужно чтобы electron приложение поднимало сервисы написанные на java для кассы и принтера, которые будут торчать на localhost'е, при этом кассы и принтеры чеков могут быть от разных производителей, поэтому нам нужен был абстрактный сервис над ними который работал  который поднимался бы локально рядом с electron приложением и торчал в тырнеты(туннелился) через ngrok или localtunnel