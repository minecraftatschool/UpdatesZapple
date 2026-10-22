# Zapple updates

Android builds of Zapple. The app checks `latest.json` and offers new versions automatically
(Settings → Updates). Manual download:

* Android 5.0 and newer: the `*-android5plus.apk` file in `apks/`
* Android 4.x: the `*-android4-legacy.apk` file in `apks/`

Published with `scripts/publish-update.sh` from the main Zapple repository. Each APK's SHA-256
and the signing certificate are listed in `latest.json`.
