---
title: Privacy Policy — blockproc
lang: en
---

# blockproc Privacy Policy

[Versión en español](./)

**Last updated:** November 12, 2026

This policy describes how the **blockproc** app (package
`com.segutdev.blockproc`), developed by segutdev, handles user and device
information.

## 1. Summary

blockproc is a digital wellbeing app that lets you limit the apps you
choose by adding a moment of reflection and a question challenge before
opening them. **All information is processed and stored only on your
device.** blockproc has no user accounts, sends no data to any server,
includes no ads or analytics tools, and shares no information with third parties.

## 2. Data the app uses

blockproc does not collect personal data: nothing described below leaves
your device or reaches the developer.

- **Installed apps list:** used only so you can choose which apps to limit.
- **App usage (which app is in the foreground):** checked on the device to
  detect when you open an app you chose to limit and apply the block. No
  history is built and nothing is sent anywhere.
- **Your settings:** the blocks you create (apps, schedules, duration,
  extreme mode), the focus and block messages you write, the selected
  language, and the state of each ongoing block. Stored locally so the app
  works, including after a phone restart.
- **Challenge answers:** questions come from a bank bundled with the app,
  and your answers are only used at that moment to decide whether access is
  granted; they are not sent anywhere.

## 3. Device permissions

- **Usage access** (`PACKAGE_USAGE_STATS`): detect on the device which app
  is open, to apply the blocks you set up.
- **See apps with a launcher icon** (Android `<queries>` declarations,
  without the `QUERY_ALL_PACKAGES` permission): show you the list of apps so
  you can choose which ones to limit.
- **Display over other apps** (`SYSTEM_ALERT_WINDOW`): show the reflection
  and challenge screen on top of the blocked app.
- **Foreground service and notifications** (`FOREGROUND_SERVICE`,
  `FOREGROUND_SERVICE_SPECIAL_USE`, `POST_NOTIFICATIONS`): keep detection
  running with a visible notification and warn you before a scheduled block starts.
- **Run at startup** (`RECEIVE_BOOT_COMPLETED`) and **keep device awake**
  (`WAKE_LOCK`): resume saved blocks after a restart.
- **Internet access and vibration** (`INTERNET`, `VIBRATE`): normal
  permissions declared by the app framework (React Native / Expo).
  blockproc makes no network connections and sends no data.

blockproc does not use the Accessibility Service and does not access your
location, contacts, camera, microphone, photos, or files.

## 4. Sharing with third parties

blockproc **does not share, sell, or transfer** any data to third parties.
It includes no advertising, analytics, or tracking SDKs.

## 5. Storage, security, and retention

All data is stored in the app's private storage on your device, protected
by the Android system and inaccessible to other apps. It is kept while the
app is installed.

## 6. Data deletion

You can delete all data at any time by removing your blocks in the app,
using *Android Settings > Apps > blockproc > Storage > Clear data*, or by
uninstalling the app. Since the developer does not receive or store any of
your information, there is no server-side data to delete.

## 7. Children

blockproc is not specifically directed at children under 13 and does not
collect personal data from any user, including children.

## 8. Changes to this policy

If the way the app handles information changes, we will update this page
and its "Last updated" date before releasing the new version.

## 9. Contact

If you have questions about this policy, write to: **segutierrezdev@gmail.com**
