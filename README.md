# Luma Calendar development updates

This repository distributes signed development builds of Luma Calendar for
Android. The application source is maintained separately.

## Download and update

The current release is **Luma Calendar 0.4.0, build 2000015**.
[Download the APK](https://github.com/Videniye/luma-calendar-updates/releases/download/dev-2000015/Luma-Calendar-0.4.0-2000015-arm64.apk) or open the [latest release](https://github.com/Videniye/luma-calendar-updates/releases/latest).
The app requires an ARM64 device running Android 8.0 or later.

Version 0.4.0 adds optional ringing alarms for calendar events, Stop and Snooze
controls, an individual phone Clock alarm option, and a fixed phone-calendar
handoff. Enable an alarm in an event's **Edit details** and review **Alarm setup**.

Install the APK over your existing app. Do not uninstall Luma to update it:
uninstalling removes its local calendar and settings.

Luma checks for updates when opened. You can also use **Settings → Check for
updates**. Choose **Download update**, allow installation from Luma if Android
requests it, and approve Android's installation dialog.

Each release contains the signed APK, `update.json`, and `SHA256SUMS.txt`. These
are development builds and may contain unfinished features. APK downloads are
public. No user calendar data, API keys, signing keys, or private build logs
belong in this repository.

[Public update feed](https://github.com/Videniye/luma-calendar-updates/releases/latest/download/update.json)
