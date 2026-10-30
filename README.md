# Luma Calendar development updates

This repository distributes signed development builds of Luma Calendar for
Android. The application source is maintained separately.

## Download and update

The current release is **Luma Calendar 0.4.2, build 2000020**.
[Download the APK](https://github.com/Videniye/luma-calendar-updates/releases/download/dev-2000020/Luma-Calendar-0.4.2-2000020-arm64.apk)
or open the [latest release](https://github.com/Videniye/luma-calendar-updates/releases/latest).
The app requires an **ARM64 device running Android 8.0 or later**.

## What's new in 0.4.2

Android paste handling now keeps copied text in the intended field when a
keyboard sends line breaks or tabs before the text itself. Single-line fields
turn line breaks into spaces; notes keep their line breaks and tabs.

Hold a text field to open Paste and Select All. Selecting text also provides
Cut, Copy, and Paste controls. In Settings, the API-key field now has a
**Paste from clipboard** button that replaces the current key and uses Luma's
automatic encrypted save. An empty or unavailable clipboard leaves the
existing field unchanged.

The changes were checked on a Galaxy Z Fold 7 running Android 16 with Samsung
Keyboard, using synthetic text. The other phone from the original report was
not available, so confirmation on that affected model remains pending.

## Alarm customization from 0.4.1

Customize Luma's ringing alarms with a phone alarm sound or your own audio
file, a background photo or color, photo dimming, and center/top/bottom photo
framing. Preview the sound or alarm screen before saving.

- **Settings → Alarm sound & appearance** chooses shared defaults.
- A saved event's **Edit details → Event alarm sound & appearance** can use
  its own sound and background or continue following the shared defaults.

The appearance screen keeps changes as drafts until Save. Event appearance
saves separately from the event details and applies to that saved occurrence.
Stop and ten-minute Snooze remain available on the ringing alarm screen.

Selected audio and photos are copied into Luma's private phone storage. These
media files and appearance preferences are device-local and are excluded from
calendar backups. If a selected file becomes unavailable, the alarm falls back
to the default phone sound or the selected background color.

## Install and receive future updates

Install the APK over your existing Luma app to preserve its local calendar,
encrypted key settings, and saved alarm sound/background choices.

Luma checks for updates when opened. You can also use **Settings → Check for
updates**. Choose **Download update**, allow installation from Luma if Android
requests it, and approve Android's installation dialog.

Each release contains the signed APK, `update.json`, and `SHA256SUMS.txt`. These
are development builds and may contain unfinished features. APK downloads are
public. User calendar data, API keys, signing keys, and private build logs are
not distributed in this repository.

[Public update feed](https://github.com/Videniye/luma-calendar-updates/releases/latest/download/update.json)
