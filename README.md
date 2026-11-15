# Scooterio Scooter Rent App

> 👨‍💻 Developed by **[Suresh Kumar Meesala](https://github.com/SureshKumarMeesala)** · 🎨 UI design by **Iosi Pratama** (credits below)

A mobile app built with **React Native (0.88+)**, **Expo SDK 58+** and **Expo Router**, using **JavaScript and JSX (`.js`, `.jsx`)**. Every screen is built from the original Sketch design `scooter-rent-app-iosipratama.sketch` by **Iosi Pratama**: one route per artboard, with the artboard's layout, colours, images and text.

![Scooterio Scooter Rent App screens](./showcase.jpg)

## 📱 Screens (4 design artboards)

Listed in the order of the app's flow. "Taps" is the number of tap targets wired on the screen (buttons, tabs, back arrows, list rows).

| # | Screen (artboard) | Route | Size | Taps |
|---|---|---|---|---|
| 1 | **Screen/Splash Screen** · start screen | `src/app/screen-splash-screen.jsx` | 375 × 812 | 1 |
| 2 | **Screen/Detail** | `src/app/screen-detail.jsx` | 375 × 812 | 3 |
| 3 | **Screen/Payment** | `src/app/screen-payment.jsx` | 375 × 812 | 3 |
| 4 | **Screen/Scooter** | `src/app/screen-scooter.jsx` | 375 × 812 | 3 |

Screenshots of every screen are in [`screenshots/`](./screenshots).

## 🧩 How it's built

- `src/screens/*.json`: each design artboard converted to screen data (vector shapes, gradients, image fills, masks, shadows, blurs and rich text, positioned as in the design), plus its tap targets
- `src/sketch/SketchScreen.jsx`: draws a screen at the device's width with `react-native-svg`, native `Text`/`TextInput` and `expo-blur`, and handles navigation between screens
- `src/app/`: Expo Router routes, one per artboard (`index.jsx` opens the start screen)
- `assets/images/`: images used by the design

## 🛠️ Tech Stack

- **Framework**: React Native 0.88+ / Expo SDK 58+
- **Navigation**: Expo Router (file-based routing)
- **Language**: JavaScript & JSX (`.js`, `.jsx`)
- **Rendering**: `react-native-svg`, `expo-blur`
- **Fonts**: Google Fonts via `@expo-google-fonts` (DM Sans), standing in for the design's original fonts where those aren't free

<!-- run-locally:start -->

## ▶️ Run locally

```bash
npm install
npx expo start
```

Then press `i` for the iOS simulator, `a` for Android, or `w` for the web, or scan the QR code with Expo Go.

<!-- run-locally:end -->

<!-- developer:start -->

## 👨‍💻 Developer

This React Native app was developed by **Suresh Kumar Meesala**.

| | |
|---|---|
| Developer | [Suresh Kumar Meesala](https://github.com/SureshKumarMeesala) |
| GitHub | [@SureshKumarMeesala](https://github.com/SureshKumarMeesala) |
| Organization | [FreeAppSource](https://github.com/FreeAppSource) |
| Repository | <https://github.com/FreeAppSource/scooterio-scooter-rent-app> |

<!-- developer:end -->

---

<!-- design-credits:start -->

## 🎨 Design Credits

This app is based on the free **Scooter Renting App - Scooterio** design by **Iosi Pratama**, downloaded from Sketch App Sources. All visual design credit goes to the designer. The screens are reproduced from the original Sketch file; fonts that aren't free are replaced with similar Google Fonts, so some details may differ slightly from the original.

| | |
|---|---|
| Designer | [Iosi Pratama](https://www.sketchappsources.com/contributor/iosipratama) |
| Original design | [Scooter Renting App - Scooterio](https://dribbble.com/shots/10497188-Scooterio-Scooter-Rent-Mobile-App-Design-Exploration) |
| Downloaded from | [Sketch App Sources](https://www.sketchappsources.com/free-source/4315-scooter-renting-app-scooterio-sketch-freebie-resource.html) |
| Dribbble | <http://www.dribbble.com/iosipratama> |
| Twitter | <https://twitter.com/iosipratama> |
| Original file | `scooter-rent-app-iosipratama.sketch` |
| License / usage | Not stated on the page. Free download; give credit (Sketch App Sources Terms). Confirm with the designer before commercial use. |

**Attribution:**

> UI design: "Scooter Renting App - Scooterio" by Iosi Pratama (https://dribbble.com/shots/10497188-Scooterio-Scooter-Rent-Mobile-App-Design-Exploration), downloaded from Sketch App Sources (https://www.sketchappsources.com/free-source/4315-scooter-renting-app-scooterio-sketch-freebie-resource.html).

The original design source files are not included in this repository; get them from the links above. This app's **code** is released under the [MIT License](./LICENSE); the visual design remains the designer's (see [NOTICE](./NOTICE)).

Photos, brand logos and avatars inside the design may belong to third parties and are not covered by the designer's permission.

<!-- design-credits:end -->
