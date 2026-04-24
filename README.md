# LinkHub

LinkHub is a powerful offline-first Android application (converted from a PWA) designed to seamlessly manage, organize, and access your links.

## Features

- **Offline-First Persistence (SQLite):** Your links are saved locally on your device for immediate access, even without an internet connection.
- **Link Previews:** Automatically generates visual previews for your saved links.
- **Smart Categories:** Intelligently organizes your links into relevant categories for easy discovery.
- **Favorites System:** Quickly access your most important and frequently visited links.
- **Deep Linking:** Open links directly in their respective native applications for a smoother experience.
- **Cloud Synchronization:** Securely sync your data across devices using a manual token flow, bypassing standard Android WebView security restrictions.

## Installation

You can install the application directly using the provided APK file:

1. Download the `linkHub.apk` file from this repository.
2. Ensure your Android device allows installing apps from unknown sources (Settings > Security > Unknown Sources).
3. Open the APK file to install the application.

## Development

This project was originally built as a Progressive Web App (PWA) and converted to a native Android APK to leverage device-specific capabilities like SQLite for local storage and deep linking.
