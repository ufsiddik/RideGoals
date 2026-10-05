# RideGoal

Offline-first Android ride earnings goal tracker for Rapido/ride-hailing drivers.

## Stack
- Kotlin + Jetpack Compose + Material 3
- Local SQLite database via `SQLiteOpenHelper`
- Local `AlarmManager` reminders + notification channel
- Android Storage Access Framework for JSON/CSV export/import
- No login, Firebase, Supabase, API, or mandatory internet connection

## Main flow
Welcome → Goal setup → Plan summary → Dashboard → Add/Edit/Delete rides → Calendar → Dynamic remaining target → Modify goal → Completion → Goal history.

## Build
Open this folder in Android Studio with a current Android SDK and let Gradle sync. Select the `app` module and run it on an Android 8.0+ device/emulator.

The provided source was prepared in an environment without the Android SDK/Gradle executable, so a device APK was not compiled here. Android Studio should perform the normal dependency resolution and build.
