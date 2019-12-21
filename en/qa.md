# Common Q & A

## Table of Contents

- [App Permissions](#App-Permissions)
- [Screen behavior won't work](#Screen-behavior-wont-work)
- [Turn off all notifications](#Turn-off-all-notifications)
- [Differences from CycleTimer](#Differences-from-CycleTimer)
- [Run record is not recorded](#Run-record-is-not-recorded)
- [iOS verison](#iOS-version)
- [Google Play APK](#Google-Play-APK)
- [Why is this app free?](#Why-is-this-app-free)

## App Permissions

- Read/Write SD card: for exporting and importing app data and picking custom ringtones.
- Network/View WLAN connections: for collecting crash reports.
- Run at startup: for rescheduling schedulers to make sure they keep working.
- Run foreground service/Prevent phone from sleeping：for counting down time precisely and reminding on time.
- Read phone status and identity (**Only on Android Lollipop: 5.0、5.1. For other system versions, it's not used and invisible**): for pausing all timers when there is an incoming phone call.
- Control vibration: for reminding by vibrating
- Install shortcuts: for creating timer shortcuts and starting timers with one click.

## Screen behavior won't work

Screen uses the system [Text-to-sppech] function. Please configure [Test Text-to-speech] in this app\'s settings, then select [No] to enter system settings. Use proper engine and right language and download voice data if you need it to work offline.

## Turn off all notifications

No, you can't. But you can

1. In the editing timer screen, click the gear icon on the left and turn off [Show Timing Notification]. This way, at runtime, there will only be one notification that shows the overview information.

1. Open app's [Settings] - [Open Notification Settings] and turn off specific notification permissions in the system settings.

## Differences from CycleTimer

1. There is no further maintenance for CycleTimer. But, the development task is still in progress. TimeR Machine is its successor.

2. In CycleTimer, reminders between steps are global and automatically added. You don't need to add them manually. In TimeR Machine, you must add a step with behaviors or you'll never get reminded.

## Run record is not recorded

When a timer finishes naturally, it'll be recorded. So you can add an end step and let it finish naturally. Then the record should be recorded.

## iOS version

No iOS version. Because of the lack of time, skills and equipment, there is no plan for developing an iOS version currently.

Here're some keywords to help you search alternatives:

- Interval Timer
- HIIT Timer
- Tabata Timer
- Repeating Timer
- Custom Countdown Timer

## Google Play APK

The app’s Google Play distribution uses [App Bundle](https://developer.android.com/platform/technology/app-bundle), which uses multiple APKs to reduce the APK size. It's safer, more convenient, and you can get the most timely updates.

If you download one APK of this app directly from a third party to install it, the app will crash or become unusable. So when Google Play is not available to you, you can [download the full APK here](https://drive.google.com/open?id=1YHIdW77fuxmyQ7sFza1LEIqmhzBygEZx).

## Why is this app free

Because there aren't enough users using this app and adding paid features costs more. After accumulating enough users, I'll consider adding some paid services which don't affect the app's current features.
