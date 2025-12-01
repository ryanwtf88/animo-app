# ANIMO Android App

[![Platform](https://img.shields.io/badge/Platform-Android-green.svg)](https://www.android.com/)
[![Min SDK](https://img.shields.io/badge/Min%20SDK-24-blue.svg)](https://developer.android.com/about/versions/nougat)
[![Target SDK](https://img.shields.io/badge/Target%20SDK-34-blue.svg)](https://developer.android.com/about/versions/14)
[![Version](https://img.shields.io/badge/Version-1.0-orange.svg)](https://github.com/ryanwtf88/animo-app/releases)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Official Android application for **ANIMO** - Your premium anime streaming platform.

## About

This Android app provides a native mobile experience for [ANIMO](https://animo.qzz.io/), a free anime streaming platform where users can watch anime online in HD quality with both DUB and SUB options.

The app uses a WebView implementation to deliver the full web experience with optimized mobile performance, offline capability, and native Android features.

## Features

- **HD Anime Streaming** - Watch anime in high-definition quality
- **DUB & SUB Support** - Choose between dubbed and subtitled versions
- **Native Android Experience** - Optimized WebView with smooth navigation
- **Back Navigation** - Native back button support for seamless browsing
- **Full Web Features** - Access all features available on [ANIMO](https://animo.qzz.io/)
- **Fast Loading** - Optimized settings for quick content delivery
- **Secure** - HTTPS-only content with secure browsing

## Technical Details

### Built With

- **Language:** Kotlin
- **Min SDK:** Android 7.0 (API 24)
- **Target SDK:** Android 14 (API 34)
- **Architecture:** WebView-based hybrid app

### Key Components

- **WebView Configuration:**
  - JavaScript enabled for full functionality
  - DOM storage for data persistence
  - Mixed content support
  - Responsive viewport settings
  - Custom WebViewClient and WebChromeClient

### Dependencies

```gradle
- androidx.core:core-ktx:1.12.0
- androidx.appcompat:appcompat:1.6.1
- com.google.android.material:material:1.11.0
- androidx.constraintlayout:constraintlayout:2.1.4
```

## Installation

### Download APK

Download the latest release APK: [**animo-release.apk**](https://github.com/ryanwtf88/animo-app/releases/latest/download/animo-release.apk)

### Install on Android Device

1. Download the APK file to your Android device
2. Enable "Install from Unknown Sources" in your device settings
3. Open the APK file and follow the installation prompts
4. Launch ANIMO from your app drawer

## Development

### Prerequisites

- Android Studio Arctic Fox or later
- JDK 8 or higher
- Android SDK with API 34

### Setup

1. Open the project in Android Studio
2. Sync Gradle files
3. Run on an emulator or physical device

### Build Configurations

- **Debug Build:** `./gradlew assembleDebug`
- **Release Build:** `./gradlew assembleRelease`

The release build includes:
- Code minification (ProGuard)
- Resource shrinking
- Signed with release keystore

## Website

Visit the web version at: **[https://animo.qzz.io/](https://animo.qzz.io/)**

The website offers:
- Free anime streaming
- HD quality video playback
- Extensive anime library
- User-friendly interface
- Regular content updates

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support and inquiries, please visit [animo.qzz.io](https://animo.qzz.io/)

---

Made with ❤️ for anime fans worldwide
