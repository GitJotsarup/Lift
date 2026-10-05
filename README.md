# Lift

Gym tracker app. The whole app lives in `app/src/main/assets/index.html`;
the Android part is a thin wrapper that shows it full screen.

## Get the APK (no Android setup needed)
1. Create a new GitHub repo and push this folder to it.
2. Open the repo's Actions tab. "Build APK" runs automatically (about 3 min).
3. Open the finished run, download Lift-apk at the bottom, unzip it.
4. Send app-debug.apk to your phone, open it, allow "install unknown apps".

## Build locally instead
Open this folder in Android Studio (or IntelliJ IDEA with the Android plugin),
let Gradle sync, then Build > Build APK(s).

## Updating the app
Replace app/src/main/assets/index.html with the new version, bump
versionCode in app/build.gradle, push. Install the new APK over the old
one and your data stays.
