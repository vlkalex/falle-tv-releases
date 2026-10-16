# Falle TV — Android TV releases

Downloads for **Falle TV**, a movie & series app for Android TV / Google TV.
This repository only hosts the installable app; there is no source code here.

**Latest version:** see [Releases](https://github.com/vlkalex/falle-tv-releases/releases/latest).
Direct link to the newest APK (always up to date):

    https://github.com/vlkalex/falle-tv-releases/releases/latest/download/falle-tv.apk

## Install on your TV (no developer mode needed)

1. On the TV, open the **Google Play Store** and install **Downloader** (by AFTVnews).
2. Open Downloader. When asked, allow it to access files.
3. In Downloader's address box, enter the link above (or the short code you were given) and press **Go**.
4. When the download finishes, choose **Install**.
   The first time, Android asks you to allow Downloader to install apps:
   choose **Settings**, turn on **Allow from this source**, press **Back**, then **Install**.
5. Open **Falle TV** from your apps. On the first screen, sign in to WebShare or choose *Skip for now*.

You can delete the downloaded file in Downloader afterwards.

## Updates

Falle TV checks this page when it starts and offers new versions itself ("Update now").
The first update asks once to allow Falle TV to install apps; after that, updating is one click.
You can also check manually in **Settings → About → Check for updates**.

## Verifying a download

Every release includes `falle-tv.apk.sha256`. All releases are signed with the same key:

    SHA-256 certificate: e1db7c9f3ae16e87ecc3281d7beb6520773ef4ecb053029cc5447b45af65d8e4

Android only installs an update over an existing Falle TV if it is signed with this same key.
