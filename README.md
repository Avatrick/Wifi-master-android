# WiFi Master (Android starter)

A small native Android starter app for legitimate Wi-Fi troubleshooting and recovery.

## Included
- Nearby Wi-Fi scan results (subject to Android permissions, device support, and scan throttling).
- Router password-change recovery guidance.
- Shortcut to Android Wi-Fi settings.
- Basic router security checklist.

## Important limitations
- This app does **not** crack Wi-Fi passwords or bypass network security.
- Android does not allow ordinary apps to extract passwords from arbitrary nearby protected networks.
- Saved-network password visibility depends on Android version, device manufacturer, and user/system permissions. This starter does not attempt to bypass those restrictions.
- Scanning generally requires Location permission and Location Services to be enabled. Android may throttle scans or return cached/empty results.
- A router factory reset can erase ISP and custom configuration. Follow the router manufacturer's instructions.

## Build
1. Install Android Studio (current stable) and Android SDK 35.
2. Open this folder in Android Studio.
3. Allow Gradle sync to finish.
4. Connect an Android phone or start an emulator with Wi-Fi support.
5. Press Run.

The project uses Android Gradle Plugin 8.7.3 and Kotlin 2.0.21.
