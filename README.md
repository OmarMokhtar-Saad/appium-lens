<div align="center">

<img src="assets/logo.svg" alt="Appium Lens" width="120"/>

# Appium Lens

### Your complete Appium mobile-testing workspace — inside JetBrains IDEs

[![JetBrains Marketplace](https://img.shields.io/jetbrains/plugin/v/31156-appium-lens?label=Marketplace&logo=jetbrains&color=147EFB)](https://plugins.jetbrains.com/plugin/31156-appium-lens)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/31156-appium-lens?color=147EFB)](https://plugins.jetbrains.com/plugin/31156-appium-lens)
[![Rating](https://img.shields.io/jetbrains/plugin/r/rating/31156-appium-lens?color=147EFB)](https://plugins.jetbrains.com/plugin/31156-appium-lens/reviews)
[![IDE](https://img.shields.io/badge/IntelliJ%20IDEs-2025.2%2B-000000?logo=intellijidea)](https://plugins.jetbrains.com/plugin/31156-appium-lens)

[**Install from Marketplace →**](https://plugins.jetbrains.com/plugin/31156-appium-lens)

</div>

---

Setting up an Appium environment usually takes hours of installing tools, fixing
PATHs, and chasing version mismatches. **Appium Lens** does it in one click — then
keeps the entire mobile-testing workflow in your IDE: mirror and control devices,
inspect UI hierarchies, run the Appium server, and build & test REST APIs, all
without leaving your editor.

## Features

### 🚀 One-Click Environment Setup
Auto-detects **26 mobile-testing tools** across four phases and installs the missing
ones with a single click. Smart routing per tool (Homebrew, npm, nvm, Chocolatey, or
guided manual install), live health monitoring, automatic update detection, and
actionable fix suggestions.

### 📱 Device Mirroring & Control
Real-time screen mirroring of Android devices, emulators, and iOS simulators. Two
engines — a high-FPS scrcpy window or **embedded in-IDE H.264 streaming** (JavaCV).
Tap, swipe, pinch, and long-press straight from the IDE; create, launch, and
health-monitor Android AVDs.

### 🔍 UI Inspection
- **ADB Inspector** — inspect the live UI tree and extract XPath / ID / text locators
  **without** an Appium server.
- **Appium Inspector** — connect to a running server, build W3C capabilities visually,
  and inspect live sessions.

### ⚙️ Appium Server & API Forge
- Start, stop, and monitor the Appium server with port-conflict resolution and live logs.
- **API Forge** — build HTTP requests, import cURL, manage OAuth 2.0, and generate
  runnable test code.
- **Framework Generator** — scaffold ready-to-run test-automation projects.

## Screenshots

> _Screenshots live in [`assets/`](assets). Replace the placeholders below as you add them._

| Setup wizard | Device mirroring | Inspector |
|:---:|:---:|:---:|
| ![Setup](assets/setup.png) | ![Mirror](assets/mirror.png) | ![Inspector](assets/inspector.png) |

## Supported Tools

| Category | Tools |
|---|---|
| **Foundation** | JDK / OpenJDK, Node.js & npm, Homebrew, nvm, Xcode CLI Tools, Android Studio, Chocolatey |
| **Core** | Appium Server, Appium Doctor, Android Platform Tools, Android Command-line Tools, Maven, Gradle |
| **Drivers** | XCUITest, UIAutomator2, Espresso, Flutter |
| **Utilities** | scrcpy, ffmpeg, Allure, Android Emulator, iOS Simulator, Android Build Tools, Android SDK Platforms |

## Requirements

- **IDE:** IntelliJ IDEA (and other IntelliJ-based IDEs) **2025.2** or later
- **OS:** macOS (Homebrew-based) or Windows (Chocolatey / manual)

## Getting Started

1. Install **Appium Lens** from the [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/31156-appium-lens).
2. Open the **Appium Lens** tool window from the right sidebar (or **Tools → Open Appium Lens**).
3. On the **Setup** tab, let the wizard scan your machine, then click **Install All Missing**.
4. Switch to the **Testing** tab to mirror a device, inspect UI, run the Appium server, or test APIs.
5. Manage analytics consent anytime in **Settings → Tools → Appium Lens → Analytics**.

## Privacy

Appium Lens collects **opt-in, anonymous** usage analytics only (plugin lifecycle
events, installation success/failure, feature usage, and error reports) via Firebase
Analytics. **No personal data, project code, or file paths are ever collected.** You
are asked for consent on first use and can change it anytime in
**Settings → Tools → Appium Lens → Analytics**.

## Support & Feedback

- 🐛 **Found a bug or have a feature request?** [Open an issue](../../issues/new/choose).
- 📧 **Email:** support@appiumlens.com
- ⭐ Enjoying the plugin? [Leave a review](https://plugins.jetbrains.com/plugin/31156-appium-lens/reviews).

## License

Appium Lens is proprietary software. Use of the plugin is governed by the
[End User License Agreement](LICENSE.md).

---

<div align="center">
<sub>Built for mobile test-automation engineers who'd rather write tests than fight toolchains.</sub>
</div>
