# Ngoc Le

### Mobile Developer · iOS & Android

I build mobile apps and native modules with **React Native, Expo, TypeScript, Swift, and Kotlin**. Based in Ho Chi Minh City, Vietnam, I focus on native integrations, gestures, animation, and graphics—and contribute fixes to the libraries behind them.

[Portfolio](https://ngocdevv.com/) · [LinkedIn](https://www.linkedin.com/in/ngocdevv/) · [Email](mailto:ngocdevv@gmail.com)

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

## What I work on

- **Native integrations:** Expo modules, iOS CallKit/PushKit, Android Telecom, share intents, and iOS Share Extensions.
- **Mobile UI:** gestures, spring animations, keyboard-aware components, and Skia rendering with Reanimated and Gesture Handler.
- **App architecture:** Redux Toolkit, Redux Saga, Context, MobX State Tree, REST APIs, Firebase, and Supabase.
- **Build & delivery:** Xcode, Android Studio, Fastlane, Xcode Cloud, and development/staging/production configurations.

## Selected projects

| Project | What I built | Stack |
| --- | --- | --- |
| [bottom-sheet-native](https://github.com/ngocdevv/bottom-sheet-native) | A bottom sheet with native gesture, detent, spring, and keyboard handling. In development; not yet published on npm. | React Native · Expo Modules · Swift · Kotlin |
| [expo-vicall-call-manager](https://github.com/ngocdevv/expo-vicall-call-manager) | A bridge to system call UI and lifecycle through iOS CallKit/PushKit and Android Telecom. | Expo Modules · TypeScript · Swift · Kotlin |
| [react-native-share-content](https://github.com/ngocdevv/react-native-share-content) | Incoming text and media sharing through Android intents and an iOS Share Extension, with queued delivery and typed events. | Expo Modules · Swift · Kotlin · Config plugins |
| [holodex-151](https://github.com/ngocdevv/holodex-151) | A holographic card demo with gesture/sensor-driven motion, Skia graphics, and reduced-motion support. | React Native · Expo · Skia · Reanimated |

## Open-source contributions

**10 accepted PRs across 6 projects**, including fixes in the React Native ecosystem:

| Project | Contribution | Evidence |
| --- | --- | --- |
| **React Native** | Preserved explicit transparent colors during Android prop reconciliation; fixed RTL glyph clipping on Android 15+. | [#58093](https://github.com/react/react-native/pull/58093) · [#58072](https://github.com/react/react-native/pull/58072) — landed upstream¹ |
| **React Native Gesture Handler** | Kept Swipeable gesture handlers stable when callbacks change; made DrawerLayout use the latest animation speed after a rerender. | [#4466](https://github.com/software-mansion/react-native-gesture-handler/pull/4466) · [#4470](https://github.com/software-mansion/react-native-gesture-handler/pull/4470) — merged |
| **React Native Reanimated** | Prevented React Native's development prop freezing from breaking animated styles in sticky headers. | [#10389](https://github.com/software-mansion/react-native-reanimated/pull/10389) — merged |
| **React Native Skia** | Fixed Android video-frame lifetime handling to avoid rendering disposed textures. | [#4019](https://github.com/Shopify/react-native-skia/pull/4019) — merged |
| **HeroUI** | Added accessible labels to Autocomplete search fields across documentation and Storybook examples. | [#6809](https://github.com/heroui-inc/heroui/pull/6809) — merged |

¹ React Native imports PRs through its internal workflow. These PRs appear closed on GitHub, but their changes landed in [022458f](https://github.com/react/react-native/commit/022458fbb64f4303b7872e738134c021c62bc291) and [57f4080](https://github.com/react/react-native/commit/57f408012d5f44ea2d14fe0172609a705973c209).

I also have open PRs for **React Native Screens, VisionCamera, React Native SVG, React Native PDF, and TanStack Query**.

**[View the full contribution list →](https://github.com/ngocdevv/ngocdevv/blob/main/OPEN_SOURCE.md)** — all 18 PRs and 3 authored issues, with source links and status notes. Checked on **October 1, 2026**.
