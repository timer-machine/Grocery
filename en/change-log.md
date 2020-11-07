# Change Log

## 2020-11-7 5.1.0

- Added: An interactive tutorial.
- Improved: Better Whitelist Guideline.
- Improved: Timers in the trash are unable to start.
- Improved: Timer shortcuts are disabled when the timer is deleted.
- Fixed: Edited timers go into the default set sometimes.
- Fixed: UI becomes unresponsive when the next timer to start is missing.

## 2020-10-26 5.0.0

- Added: Timer Set for categorizing timers.
- Added: Several rules to sort timers.
- Added: More menu options when long clicking a timer.
- Improved: When deleting a timer, it goes to the trash instead of being deleted.
- Fixed: A crash when saving a notifier fails.

## 2020-10-5 4.7.0

- Added: A duplicate button when adding steps.
- Added: More variables for the Voice reminder.
- Added: A message notification when starting a timer from a shortcut.
- Improved: When entering the records screen, switch to the previously viewed tab.
- Fixed: Time picker crashes on some Samsung devices.
- Fixed: A crash when trying to add a record of a deleted timer.

## 2020-9-7 4.6.0

- Added: [Only for apps installed from Google Play Store] Cloud Backup as a subscription service. It's in the Backup & Restore.
- Improved: Better Whitelist Guideline. You need to whitelist this app on third-party manufacturer devices.
- Fixed: Dragged step's shadow is clipped.
- Fixed: Multiple crashes of the new ringtone picker under test.

## 2020-8-1 4.5.1

- Improved: Renamed "Behavior" to the more intuitive "Reminder."
- Improved: Renamed "Stopwatch" back to "Halt," since "Stopwatch" has no duration while "Halt" can have one. I apologize for the inconvenience and would like to thank M Lev for the feedback and patient explanation.
- Improved: Polished the app tutorial.
- Improved: "Beep" and "Halt" can work together.
- Improved: For Android Oreo and later, the app will remember backup and restore file location.
- Improved: The app will show an alert if the backup or restore file is empty.
- Fixed: Auto dark theme doesn't work sometimes.
- Fixed: Audio Focus Type doesn't get included when backup.
- Fixed: Time Picker crashes on some Samsung devices.
- Fixed: Some crashes related to the new ringtone picker.

## 2020-6-28 4.5.0

- Added: More versatile timer running records display.
- Added: New and polished icons in many places.
- Added: A "+ 1:00" button in the fullscreen popup.
- Added: [Experimental] New ringtone picker and a button for picking any ringtone file on the device.
- Improved: "Halt" is renamed to the more meaningful "Stopwatch."
- Improved: "Notification" behavior will show on smartwatches.
- Improved: Unified timer picker in different places.
- Fixed: Some typos.
- Fixed: Auto dark theme doesn't work sometimes.
- Fixed: A crash when you long-press a step to edit it.
- Changed: To remind you from smartwatches, "Notification" behavior's sound has been turned on. If you don't need it, turn it off when editing the behavior.

## 2020-5-24 4.4.0

- Added: Animation for switching between start and pause icons.
- Added: A "$total_loop" variable for the Voice behavior to represent the current total loop.
- Added: Support for setting every day of a week as the first day of the week.
- Added: "Text-to-speech Configuration" in Help & Feedback, replacing "Test Text-to-speech" in the app settings.
- Improved: Unified design among Backup, Settings, and Help & Feedback.
- Improved: More detailed timer state info when the fullscreen notification.
- Improved: Quicker animation when changing steps.
- Fixed: A crash when dragging and moving steps.
- Changed: "App Theme" is moved to "Settings," and "Toolbox" is renamed to "Backup & Restore."

## 2020-5-11 4.3.0

- Added: A setting item for showing the total time of the timer and groups in the edit screen.
- Improved: Group steps are wrapped into the group.
- Improved: Time panels have more straightforward icons and colors.
- Improved: Bigger click area for double-tap to jump to a step or long-click to edit a step.
- Improved: More easy-to-understand instruction manual.
- Fixed: Dialogs aren't shown in full size on small devices.
- Fixed: Auto dark won't work under certain circumstances.
- Fixed: Picture-in-picture and the floating window sometimes cause a crash.
- Fixed: Deleting steps sometimes causes a crash.
- Fixed: Long-click on entries of a popup menu on Android O causes a crash.
- Fixed: Group steps sometimes are wrongly shown and cause a crash on saving.
- Changed: "Night, Day Theme" is renamed to "Dark, Light Theme."

## 2020-4-17 4.2.0

- Added: A setting item for the audio focus action.
- Added: New audio type: Notification.
- Improved: After a timer ends, if it has the next timer, load it automatically.
- Improved: Dynamic theme on different widgets.
- Improved: More conspicuous elevation animation when moving a step.
- Improved: When moving untouchable steps, error messages show.
- Fixed: Sometimes export and import locations can't be memorized.
- Fixed: Beep won't work on some devices.
- Fixed: All paused timers are resumed after a phone call.
- Fixed: App blinks during automatically switching dark theme.
- Changed: Now you can't select alpha when picking custom colors.

## 2020-1-22 4.1.0

- Added: Support for reordering steps by long clicking them.
- Added: Settings for floating window transparency and size.
- Added: A confirmation dialog when you discard your edit of a scheduler.
- Added: Dark theme support for the in-app browser.
- Improved: Swiping to delete timers or steps becomes much harder to avoid mistaken deletion.
- Improved: The floating window is centered on the screen.
- Fixed: Automatically switching the dark theme won't work sometimes.
- Fixed: The app crashes on entering the timer edit screen on some devices.
- Fixed: Popup menu can't be dismissed by clicking outside on the Lollipop.

## 2019-11-2 4.0.0

- Added: Android Q support.
- Added: More versatile dark theme settings.
- Added: Count and Notification behaviors and Time Panels have graduated from labs!
- Added: When the timer discard dialog is shown, a save button is added.
- Added: When adding behaviors popup is shown, long clicking behavior to see its explanation.
- Improved: Bigger text size for the time picker.
- Improved: Better layout for the tweak-time dialog.
- Improved: Adding behaviors popup has margins.
- Improved: PIP doesn't require turning off the dark theme anymore.
- Fixed: Some previously created backup files cannot be imported.
- Fixed: Crashes when external intents fail.
- Fixed: Crashes related to timer deletion.
- Changed: Deprecated ways to export and import app data are removed. You should use the new ways which don't require permission.

## 2019-7-6 3.8.0

- **This app now is totally free. No more in-app purchases. Thank you for using this app and supporting it!**
- Added: New methods to import and export app data without permissions. Old methods are still kept.
- Improved: Much smaller APK size.
- Fixed: Imported and exported schedulers are disabled now.
- Fixed: Text-to-speech checker won't work well sometimes.

## 2019-6-30 3.7.1

- Added: Half behavior has two more reminders: music and vibration.
- Improved: Text cursor is changed to white to separate it from the background color.
- Improved: Music picker will immediately show the selected item without scrolling.
- Improved: Scrollable time picker's max time is 99h 59m 59s and the hour picker shows time in both directions.
- Improved: More straightforward lock and unlock icons.
- Fixed: After deleting timers or schedulers and leaving the app, deleted content isn't deleted.
- Fixed: Schedulers' enabled state is wrong while scrolling.
- Fixed: Music picker sometimes crashes the app during screen rotation.

## 2019-6-22 3.7.0

- Added: A second tweaking time main button.
- Added: In-app tutorials.
- Improved: Creating timer button is centered and stops blocking timers.
- Improved: When creating a new scheduler, time picker will show the current time by default.
- Improved: Now you can also edit tweak time settings in the Customize Screen.

## 2019-6-14 3.6.0

- Added: [Experimental] Timer Panels! After enabling in the labs, in the [Settings] - [Customize Screen], you can add panels for elapsed time, remaining time, end time and more.
- Added: Now you can apply timer templates in the timer edit screen.
- Improved: Step name can show multiple lines of text.
- Improved: Timing bar shows above the step list.
- \* You can enable experimental features in the [Settings] - [Labs].

## 2019-6-8 3.5.1

- Improved: Deleted timers and schedulers are batched together.
- Improved: TextToSpeech calls are batched together when possible, saving your battery!
- Improved: Voice content dialog can show multiple lines.
- Fixed: A crash when you try to create a shortcut for a missing timer.

## 2019-6-1 3.5.0

- Added: [Experimental] New behavior: Notification. It shows another notification at the start of a step.
- Added: An "Never show again" option in the website warning dialog.
- Improved: Better swipe animation.
- Improved: More specific notification categories.
- Fixed: A rare crash when a wrong timer is deleted.
- Fixed: A crash when you open a website but there is no default browser.
- \* You can enable experimental features in the [Settings] - [Labs].

## 2019-5-25 3.4.0

- Added: Vibration behavior has two more patterns: short and long.
- Added: When "Show Remaining Time In the Notification" is enabled, a progress bar will be shown in the notification.
- Added: [Experimental] New behavior: Half. It reads "Half of the time" when the step is over halfway.
- Added: [Experimental] New behavior: Count. It counts down the last several seconds of a step.
- Improved: The timer"ll be stopped when you update a step by long pressing its step number.
- Improved: Beep count will be shown in its chip.
- Fixed: Duplicating a timer sometimes crashes the app.
- Changed: The remaining time is more accurate. In previous versions, a 5-second step shows "4, 3, 2, 1, 0" and each of them lasts one second. From now on, it shows "5, 4, 3, 2, 1".
- \* You can enable experimental features in the [Settings] - [Labs].

## 2019-5-16 3.3.2

- Improved: Better dialog view for entering beep count
- Fixed: The beeps are triggered multiple times when there are many timers running
- Fixed: Stored notifier sometimes is missed
- Fixed: A crash when the beep behavior sometimes cannot initialize itself
- Fixed: A crash because wake locks sometimes are wrongly counted

## 2019-5-7 3.3.1

- Improved: Smaller exported file size
- Fixed: Occasionally wrong main screen after toggling night theme or app theme
- Fixed: A crash while importing the data that is exported with a newer version of this app.
- Fixed: A crash while adding behavior but the behavior name is lost somehow

## 2019-5-1 3.3.0

- Added: From now on, timer records will include start time.
- Added: A setting item for if pause all timers when the phone is on a call.
- Added: Fling animation when you move the floating window.
- Improved: Better floating window view.
- Improved: Smaller APK, (probably) smoother experience.
- Fixed: Timer overall info notification sometimes displays a wrong state.
- Fixed: The stop button in the screen window sometimes overlaps with the navigation bar
- Fixed: Still trying to fix the bug where stopping all timers sometimes crashes the app. If you encounter any bugs when controlling many timers, please tell me through feedback.
- Changed: Beep\'s \"Pause Other Sound\" is renamed to \"Respect Other Sound\" which means if the beep should pause others when it starts and stop itself when others start.

## 2019-4-15 3.2.0

- Added: Halt behavior shows current step's elapsed time like a stopwatch.
- Added: Voice behavior has an option to set a specific speech content and can read current loop.
- Added: Beep behavior has an option to pause other background sound (on by default).
- Fixed: Stopping all timers sometimes crashes the app.
- **Changed: Previously created timer which uses beep behavior may not pause other background sound unless you toggle those beep behaviors' option on and off once again manually.** Developer apologizes to you for this bug.

## 2019-4-5 3.1.0

- Added: Now timer record can be exported.
- Added: [Pro] A timer option to allow a timer to trigger another timer when it finishes.
- Added: [Pro] Tasker support (You can find this app in the Tasker\'s plugin option)
- Improved: Less disk space that a timer takes.
- Fixed: A bug that new version info cannot be fetched.
- Changed: "Import method" is moved to "Content Selection". Check "Wipe out…" to replace old data and uncheck it to append data.

## 2019-3-27 3.0.1

- New: An setting option for closing the floating window and PIP automatically.
- Improved: Better time picker view in the landscape mode.
- Fixed: Steps are doubled when the screen is turned on and off in the timer edit screen.

## 2019-3-23 3.0.0

- New: "Always Fullscreen" option for the screen behavior.
- Improvement: Better UI.
- Improvement: New time pick widget whose max time is 99h 99m 99s.
- Fixed: Broken timer screen after screen rotation.
- Fixed: Floating window won\'t work after the app is closed.
- Changed: The dialog for editing a scheduler becomes a screen.

## 2019-2-11 2.1.0

- Added: Now you can quickly jump to a step by double tapping a step number.
- Added: Now you can quickly edit a step by long clicking a step number.
- Added: Now you can customize timer actions in the [Settings] - [Customize Screen].
- Improvement: Better UI(The developer has tried his best although…)
- Changed: Notification toggle in the timer screen has been removed but you can still edit it in the timer edit screen.

## 2019-2-4 2.0.1

- Fixed: two crashes related to navigation

## 2019-2-1 2.0.0

- Added: New step type "Group" which has its own name and loop
- Added: A instruction manual in the Help & Feedback(click here to check it)
- Improvement: Step behavior edit layout becomes from selective to additive, which replaces behavior expanding and collapsing
- Improvement: Music will be stopped when the headset is unplugged
- Improvement: Screen brightness will be applied to the timer list screen
- Improvement: Better timer name and loop input layout
- Improvement: Better user panel layout
- Improvement: A running timer won't be reset any more when its shortcut is clicked
- Improvement: No more timer steps details are shown in the timer list screen, which saves some phone memory
- Fixed: A bug where notifier changes won't be saved sometimes
- Fixed: A crash that causes a scheduler cannot be started
- Changed: When a file exported by an old version is imported, app theme may not be applied correctly. Please set app theme manually.
- Changed: Dragging and dropping to sort steps is removed because it's hard to implement. You can still add and remove steps to achieve sort effect.
- Changed: App settings detailed items export is removed because it's too redundant.

## 2018-12-29 1.1.1

- New: supports the new Material Design
- New: toggles for enabling light status bar and tinting navigation bar in the theme settings
- New: a better step layout in the timer screen
- New: supports Google Sign In
- Improvement: more thorough night theme view
- Fix: a crash when click next step madly

## 2018-12-15 1.1.0

- New: Pro version is available to unlock some useless features
- New: new beep behavior which can beep every second
- New: now you can check timer completion record
- Improvement: better theme selection layout
- Improvement: show a message when you adjust timer but UI is locked

## 2018-12-2 1.0.6

- New: a setting item for changing the action when plus time at a notifier step
- New: a setting item for adding more time tweak actions
- Improvement: a little more reliable scheduler implementation
- Improvement: more good-looking auto night dialog layout
- Repair: a bug where the expand/collapse button state sometimes won\'t be saved
- Repair: a bug where the expand/collapse button sometimes shows wrong state
- Repair: a bug where the theme feature sometimes crashes the app
- Repair: a bug where the scheduler won\'t work on Android 9(Pie)
- Repair: a bug where the app crashes on MeiZu devices because of a MeiZu bug

## 1.0.5, Nov 20, 2018

- New: an switch to expand or collapse behaviors in the editing screen(there is also another setting item for showing that button on every step)
- Improvement: a little more reliable scheduler implementation
- Improvement: eliminate the gap between TTS and music playback
- Improvement: now the timing bar will be updated every second instead of every half second
- Repair: a bug where the behavior setting icon is still shown in the timing screen
- Repair: a bug where the default ringtone always loops
- Repair: a bug where the undo button is missing during auto theme changes

## 1.0.4, Nov 7, 2018

- New: An option to lock UI in the timer screen
- Improvement: More animation
- Improvement: Better import and export layout

## 1.0.3, Oct 25, 2018

- New: Picture in picture mode for Android O and supported devices
- New: Scheduler repeat settings(Please test it before relying on it)
- Improvement: Better scheduler editing layout
- Improvement: Better theme color matching to make them more conspicuous in the night theme
- Repair: Wrong notification content in some cases
- Repair: Broken Help &amp; Feedback screen in the night theme
- Repair: Some memory leaks
- Repair: Some bugs related to theme colors

## 1.0.2, Oct 3, 2018

- New: An setting item for switching night theme automatically
- New: When creating a shortcut, a field to change shortcut name and a switch to toggle if open timer screen when click it are added
- Improvement: Better behavior layout
- Improvement: Better awaken screen layout
- Improvement: Move check tts setting item back to app settings(I\'m sorry about this) and move app introduction setting items to toolbox
- Repair: A crash when exporting app data to nonexistent folder

## 1.0.1, Sep 25, 2018

- New: Toolbox screen that contains several functions and more in the future.
- New: App theme support<
- New: App data import and export
- New: A link to enroll or quit Google Play app beta test
- Improvement: Move music pick button to the bottom of the screen
- Improvement: Move TTS check and whitelist guideline to Toolbox screen
- Repair: Wrong message when checking new version

## 1.0.0, Sep 7, 2018

- New: Supports Android Pie and optimizes for it
- New: Instructions on how to use editing timer screen
- Repair: Recent bugs and crashes

## 0.3.3 Aug 18, 2018

- READ_PHONE_STATE is required for Lollipop devices to automatically start and pause all timers during calls.
- New: Timer settings(whether show timer notification and show remaining time in it)
- New: A notification to control all timers
- New: A setting item to open system notification settings
- Improvement: New timer list layout
- Improvement: Pause all timers if calls are in and resume all timers after calls
- Repair: Recent bugs and crashes

## 0.3.2 Jul 18, 2018

- New: Some options for you to customize timer screen
- New: A loop option has been added to music behaviour to determine if the music should be looped
- New: A setting item for turning on and off time counting in the notifications
- New: A whitelist guide
- Improvement: **Now adding 1 minute at a notification step will cause the timer going back to the last step and setting time to 1 minute**
- Improvement: Two new tips
- More...

## 0.3.1 Jul 2, 2018

- Improvement: Better help and feedback screen
- Repair: Some bugs and crashes

## 0.3.0 Jun 30, 2018

- New: New(and better?) timer detail screen
- Improvement: More easy to use music picker
- Repair: Data lost during screen rotation
- Repair: Wrong notification click action
- Repair: Some bugs and crashes

## Older

They're eaten by me.
