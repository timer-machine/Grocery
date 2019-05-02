# Common Q & A

## Table of Contents

- [App Permissions](#App-Permissions)
- [Screen behavior won't work](#Screen-behavior-wont-work)
- [Turn off all notifications](#Turn-off-all-notifications)
- [Differences from CycleTimer](#Differences-from-CycleTimer)

## App Permissions

- Read/Write SD card: for exporting and importing app data and picking custom ringtones.
- Network: for collecting crash reports.
- Run at startup: for rescheduling schedulers to make sure they keep working.
- Prevent phone from sleeping：for counting down time precisely and reminding on time.
- Read phone status and identity (**Only on Android Lollipop: 5.0、5.1. For other system versions, it's not used and invisible**): for pausing all timers when there is an incoming phone call.

## Screen behavior won't work

Screen uses the system [Text-to-sppech] function. Please configure [Test Text-to-speech] in this app\'s settings, then select [No] to enter system settings. Use proper engine and right language and download voice data if you need it to work offline.

## Turn off all notifications

No, you can't. But you can

1. In the editing timer screen, click the gear icon on the left and turn off [Show Timing Notification]. This way, at runtime, there will only be one notification that shows the overview information.

1. Open app's [Settings] - [Open Notification Settings] and turn off specific notification permissions in the system settings.

## Differences from CycleTimer

1. There is no further maintenance for CycleTimer. But, the development task is still in progress. TimeR Machine is its successor.

2. In CycleTimer, reminders between steps are global and automatically added. You don't need to add them manually. In TimeR Machine, you must add a step with behaviors or you'll never get reminded.