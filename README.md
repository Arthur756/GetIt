# GetIt


<p align="center" style="background-color: #F8A65D;">
    <img alt="oss image" src="https://github.com/Arthur756/GetIt/blob/5cc11bcb49173b91913cf1102cd106bc15dc4dbe/LOGO-GETiT-PNG.png" width="180px">
    <h1 align="center">Forget pagers and endless lines</h1>
</p>
<h4 align="center">The best tool to automate service in restaurants </h4>

<br />

---

<p align="center">
  <img src="https://github.com/Arthur756/GetIt/blob/5cc11bcb49173b91913cf1102cd106bc15dc4dbe/iPhone%20X-XS-11%20Pro%20%E2%80%93%207.jpg" alt="screenshot-1" width="200">
  <img src="https://github.com/Arthur756/GetIt/blob/5cc11bcb49173b91913cf1102cd106bc15dc4dbe/IPHONE-LIST-GETiT.png" alt="screenshot-2" width="200">
  <img src="https://github.com/Arthur756/GetIt/blob/5cc11bcb49173b91913cf1102cd106bc15dc4dbe/GETiT-MESAPRONTA.png" alt="screenshot-3" width="200">
  <img src="https://github.com/Arthur756/GetIt/blob/3b583f161c06d741dbfb0adc6509c17a524f4742/GETiT-LOGINSCREEN-PNG.png" alt="screenshot-4" width="200">
</p>

---

# Forget pagers

![pagers](https://github.com/Arthur756/GetIt/blob/5cc11bcb49173b91913cf1102cd106bc15dc4dbe/NO%20PAGER-SYMBOL.png)


---

# Wait for less time

<img alt="oss image" src="https://github.com/Arthur756/GetIt/blob/3b583f161c06d741dbfb0adc6509c17a524f4742/5233.jpg" width="600px">


---

# QR code

![code](https://github.com/Arthur756/GetIt/blob/5cc11bcb49173b91913cf1102cd106bc15dc4dbe/GETiT-QRCODE-BOARD.png)


## :iphone: Try it on Expo

This app is bootstrapped with [Expo](https://expo.io), you can download the Expo app on the [App Store](https://itunes.apple.com/us/app/expo-client/id982107779) or [Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent), and enter the url provided below. We have 2 release channels:

| Release Channel                                                                           | Version | Description                                                                 | Url                                                                           |
| ----------------------------------------------------------------------------------------- | ------- | --------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| [Production](https://exp.host/@amaurymartiny/shootismoke?release-channel=production-v1.8) | v1.8.10 | Same version as Sh\*\*t! I Smoke on the App Store and Play Store.           | `https://exp.host/@shootismoke/mobile-app?release-channel=production-v1.8.10` |
| [Staging](https://exp.host/@amaurymartiny/shootismoke)                                    | v1.8.10 | Latest version currently in development: newest features, may contain bugs. | `https://exp.host/@shootismoke/mobile-app`                                    |

## :hammer: Build it yourself

Run the following commands:

```bash
# Clone this repo
git clone https://github.com/shootismoke/mobile-app && cd shoot-i-smoke
# Install dependencies
yarn install

# Copy the file that contains secrets
cp app.example.json app.json

# Run the app with Expo
yarn start
```

The [Expo](https://expo.io) packager will show, and you can either:

-   install the Expo app, scan the displayed QR code, and run the app on your mobile phone directly.
-   open the Android simulator.
-   open the iOS simulator.

#### Use your own API tokens

All required API tokens are already pre-filled in `app.example.json`. If you want to use your own API tokens, then in `app.json`, replace all the placeholders with the ones you generated for yourself. For those that are optional, you can just put `null` (without quotes).

| Service                  | Url                                                            | Comments                                                                    |
| ------------------------ | -------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Sh\*\*t! I Smoke Backend | https://github.com/shootismoke/backend                         | Required. Pre-filled with a staging token.                                  |
| World Air Quality Index  | http://aqicn.org/api/                                          | Required. You can use the public one in `app.example.json` for development. |
| Google Maps for iOS      | https://developers.google.com/maps/documentation/ios-sdk/start | Optional in development.                                                    |
| Google Maps for Android  | https://developers.google.com/maps/documentation/android-api/  | Optional in development.                                                    |
| Sentry Bug Tracking      | https://sentry.io                                              | Optional.                                                                   |
| Amplitude Analytics      | https://amplitude.com                                          | Optional. Note: we **never** track PII.                                     |

## :raising_hand: Contribute

If you find a bug, or if you have an idea for this app, please [file an issue here](https://github.com/shootismoke/mobile-app/issues). We really appreciate feedback and inputs!

🇬🇧🇫🇷🇪🇸🇨🇳 You may also contribute with translations with our online tool [POEditor](https://poeditor.com/join/project/iEsj0CSPGX). If you need context for some terms, here are [some screenshots](https://nx1394.your-storageshare.de/s/grS6CZJGapRSH6i).

For code contribution, the codebase heavily relies on functional programming principles via the [`fp-ts`](https://github.com/gcanti/fp-ts) library. The codebase itself is quite simple, so even if you're beginner to functional programming, it shouldn't be hard to follow along. You can start with these [easy tasks](https://github.com/shootismoke/mobile-app/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

More information on contributing [here](./CONTRIBUTING.md).

## :microscope: Tests

The codebase unfortunately isn't much covered by tests. Check out the `*.spec.ts` files in the project for tests. If you're interested to help out, have a look at [issue #19](https://github.com/shootismoke/mobile-app/issues/19).

# Client Space

![wall](https://github.com/Arthur756/GetIt/blob/5cc11bcb49173b91913cf1102cd106bc15dc4dbe/Prancheta%201%20%E2%80%93%2012.jpg)

## :star: Credits

Created with pride by Arthur Belfort.

![wall](https://github.com/Arthur756/GetIt/blob/5cc11bcb49173b91913cf1102cd106bc15dc4dbe/WALLPAPER%20GET%20IT!.jpg)
