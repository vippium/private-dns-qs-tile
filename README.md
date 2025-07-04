# THE REPOSITORY IS NO LONGER NEEDED AS THE DEVELOPER ITSELF ADDED `NO LAUNCHER` BUILD IN RELEASES ON MY CALL.


# Private DNS Quick Setting
 
Toggle and configure your Private DNS settings on Android 9+ from the comfort of your quick settings panel.

This is a fork of [joshuawolfsohn/Private-DNS-Quick-Tile](https://github.com/joshuawolfsohn/Private-DNS-Quick-Tile) with changes to add the following features:
- Add setting to require device to be unlock to toggle tile 
- Shizuku support

## Setup

In order to change the Private DNS settings, this app requires the
`WRITE_SECURE_SETTINGS` permission. It can be granted either by Shizuku or ADB.

### 1. Shizuku
As of v1.23, the permission can be granted automatically if you have [Shizuku](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api) 
installed and [started](https://shizuku.rikka.app/guide/setup/#start-shizuku).

### 2. ADB
The permission can be granted in an ADB shell with the command:
```
pm grant com.flashsphere.privatednsqs android.permission.WRITE_SECURE_SETTINGS
```

Check out https://private-dns-qs.web.app/help on how to use `adb` to grant the permission.

## About this Fork
This fork introduces a small but useful enhancement: the ability to hide the launcher activity, effectively removing the app icon from the app drawer. This is helpful for users who prefer a cleaner app list or consider the app icon unnecessary once the tile has been added to Quick Settings.

🔒 **Hide Launcher Activity**: Removes the app icon from the launcher to reduce clutter. The functionality of the Quick Settings tile remains unaffected.

✅ All core features from the original repository are preserved.

## Download
<div>
<a href="https://play.google.com/store/apps/details?id=com.flashsphere.privatednsqs" target="_blank">
    <img alt="Get it on Google Play" height="80" src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" /></a>

<a href="https://apt.izzysoft.de/fdroid/index/apk/com.flashsphere.privatednsqs" target="_blank">
    <img alt="Get it on F-Droid" height="80" src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png" /></a>
</div>
