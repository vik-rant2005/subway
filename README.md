# Dayline

Dayline is a transit-inspired personal calendar for Android. It includes the departure board, route map, monthly calendar, task terminal, event completion and local persistence. Completed departures are struck through and their station markers turn red. The app opens with an empty board; light/dark choice and schedule are saved on the device.

## Build an installable APK

The APK at `release/Dayline-v1.0.1.apk` can be attached to a GitHub Release or downloaded directly to an Android phone. On the Pixel 8, open the downloaded APK and allow the browser or file manager to install apps when Android prompts.

The APK is signed with a Dayline-specific upload key. Keep `android/keystores/dayline-upload.keystore` and `android/signing.properties` backed up privately to sign future updates. They are excluded from Git; do not publish them.

For future cloud builds with Expo EAS, run `eas build --platform android --profile preview`. The preview profile creates a directly installable APK. Production Play Store submissions should use an app bundle.

Application ID: `com.vikrantbhan.dayline`
