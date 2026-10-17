# Falle TV — Android TV releases

Downloads for **Falle TV**, a movie & series app for Android TV / Google TV.
This repository only hosts the installable app; there is no source code here.

**Latest version:** see [Releases](https://github.com/vlkalex/falle-tv-releases/releases/latest).

Short install address (always the newest version) — type this on the TV:

    falletv.alexvlk.com

It redirects to https://github.com/vlkalex/falle-tv-releases/releases/latest/download/falle-tv.apk

## Install on your TV (no developer mode needed)

1. On the TV, open the **Google Play Store** and install **Downloader** (by AFTVnews).
2. Open Downloader. When asked, allow it to access files.
3. In Downloader's address box, type **falletv.alexvlk.com** and press **Go**.
4. When the download finishes, choose **Install**.
   The first time, Android asks you to allow Downloader to install apps:
   choose **Settings**, turn on **Allow from this source**, press **Back**, then **Install**.
   - If **Google Play Protect** says *"App blocked to protect your device"*, select **More details**,
     then **Install anyway**. It shows this for any app that isn't from the Play Store.
   When it finishes, choose **Done** (not Open); Downloader then offers to delete the file — choose **Delete**.
5. Open **Falle TV** from your apps. On the first screen, sign in to WebShare or choose *Skip for now*.

You can delete the downloaded file in Downloader afterwards.

## Updates

Falle TV checks this page when it starts and offers new versions itself ("Update now").
The first update asks once to allow Falle TV to install apps (Settings opens: turn it on, press Back).
Android then asks *"Do you want to update this app?"*: select **Update** (on some TVs *Cancel* is
highlighted first, so press Left). Play Protect may show the same warning as above: **More details →
Install anyway**.
You can also check manually in **Settings → About → Check for updates**.

## Verifying a download

Every release includes `falle-tv.apk.sha256`. All releases are signed with the same key:

    SHA-256 certificate: e1db7c9f3ae16e87ecc3281d7beb6520773ef4ecb053029cc5447b45af65d8e4

Android only installs an update over an existing Falle TV if it is signed with this same key.

## Troubleshooting

**"App not installed — package conflicts with an existing package"**
An older Falle TV signed with a different key is still on the TV. If the TV has several user
profiles, it may be installed in another profile even after you uninstalled it in yours: switch to
each profile and uninstall Falle TV there (Settings → Apps → Falle TV → Uninstall), then install again.
