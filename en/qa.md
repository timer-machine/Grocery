# Common Q & A

## Table of Contents

- [App Permissions](#app-permissions)
- [Turn off all notifications](#turn-off-all-notifications)
- [Differences from CycleTimer](#differences-from-cycleTimer)
- [Run record is not saved](#run-record-is-not-saved)
- [iOS verison](#ios-version)
- [Google Play APK](#google-play-apk)

## App Permissions

- Foreground service, vibration, wake lock, ignore battery optimization, schedule alarms: for counting down time precisely and reminding on time.
- Run at startup: for rescheduling schedulers to make sure they keep working.
- Read files and media: for exporting and importing app data and picking custom ringtones.
- Read phone status and identity: **only for** pausing all timers when there is an incoming phone call.
- Network: for providing online services and collecting crash reports.
- Install shortcuts: for creating timer shortcuts that start timers with one click.
- Display over other apps: for showing floating timing window.

## Turn off all notifications

No, you can't. But you can

1. In the editing timer screen, click the gear icon on the left and turn off [Show Timing Notification]. This way, at runtime, there will only be one notification that shows the overview information.

1. Open app's [Settings] - [Open Notification Settings] and turn off specific notification permissions in the system settings.

## Differences from CycleTimer

1. There is no further maintenance for CycleTimer. But, the development task is still in progress. TimeR Machine is its successor.

2. In CycleTimer, reminders between steps are global and automatically added. You don't need to add them manually. In TimeR Machine, you must add a step with behaviors or you'll never get reminded.

## Run record is not saved

A record is saved in two cases.

1. The last step of the timer finishes naturally.
1. (Requires app version 5.2.0 or later) The user manually stops the timer at the last step.

Therefore, wait for the timer to finish at the last step or (requires app version 5.2.0 and later) stop manually, and the record will be saved.

## iOS version

No iOS version. Because of the lack of time, skills and equipment, there is no plan for developing an iOS version currently.

Here're some keywords to help you search alternatives:

- Interval Timer
- HIIT Timer
- Tabata Timer
- Repeating Timer
- Custom Countdown Timer

## Google Play APK

If you download an APK of this app directly from a third party to install it, the app may crash or become unusable. So when you can't or don't want to use Google Play, you can:

- [Install the app from APK Pure(You need to install APK Pure first)](https://apkpure.com/timer-machine-run-walk-interval-timer/io.github.deweyreed.timer.google)
- [Download the full APK here and install manually](https://drive.google.com/open?id=1YHIdW77fuxmyQ7sFza1LEIqmhzBygEZx).
