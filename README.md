# FITNESS PRO Android starter

A starter Android Studio project using Kotlin + Jetpack Compose with a black/neon-green theme, locally saved reminder preferences, and notification permission/channel setup.

## Open and build
1. Install Android Studio (current stable) and Android SDK 35.
2. Open this folder in Android Studio.
3. Let Gradle sync.
4. Connect an Android device or use an emulator and press Run.
5. To create an APK: Build > Build Bundle(s) / APK(s) > Build APK(s).

## Current scope
- Starter dashboard UI
- Workout reminder time field (HH:MM)
- Water reminder interval selector
- Local preference persistence using DataStore
- Notification channel and Android 13+ notification permission prompt

## Important
This is a starter project, not a finished production app. The current Save button persists reminder settings and demonstrates notification delivery; it does not yet schedule recurring exact-time workout or hourly water reminders. Those require AlarmManager/WorkManager scheduling, boot rescheduling, validation, and testing across Android versions. Cloud login/sync and full workout/diet/progress modules are not included yet.
