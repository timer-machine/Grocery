# Change Log

## 2025-3-12 7.6.0

- Added: Image reminder
- Added: Portuguese translation. Thanks to @aescouto, @profmarcos, @cairobraga, and everyone!
- Improved: More intuitive backup screens
- Fixed: Voice and Music can't co-exist after enabling TTS Bakery

## 2024-6-13 7.5.1

- Fixed: A crash when signing in

## 2024-4-7 7.5.0

- Added: The support for Android 14
- Added: The background color of the full-screen reminder aligns with its step color
- Fixed: A crash when picking a ringtone
- Changed: On Android 14, the "Always fullscreen" option for the Screen reminder is removed because of the system's restriction

## 2024-1-1 7.4.0

- Added: TTS Bakery, which improves TTS performance
- Added: Dutch translation. Thanks to Stephan Paternotte!
- Added: The beep support for the Count reminder
- Fixed: The always-showing keyboard in the timer editing screen
- Fixed: Being able to duplicate the start step

## 2023-9-8 7.3.0

- Added: The themed icon
- Added: A new voice variable, `SNameNext`, representing the next step's name
- Added: The support for undoing a step deletion
- Added: Tasker events for the start and end of a timer
- Fixed: The missing voice variable table in the landscape mode

## 2023-5-15 7.2.0

- Added: Dynamic themes(Android 12 or later required)
- Improved: A more friendly tutorial
- Improved: No change of scroll position after changing the theme

## 2023-3-4 7.1.2

- Fixed: The tip for empty timers appears when there are timers
- Fixed: A crash of Text-to-speech
- Fixed: Some missing translations

## 2023-2-3 7.1.1

- Fixed: A crash when the audio focus changes
- Fixed: The tutorial appears again after completion

## 2023-1-26 7.1.0

- Added: Support for Android 13
- Added: Spanish translation. Thanks to Mario Ruiz!
- Improved: Faster Text-to-speech
- Improved: The music will play even if the volume is zero
- Improved: The music will continue after a temporary interruption
- Improved: The shortcut's name changes with the timer name
- Improved: The records screen remembers previously selected timers and time ranges
- Fixed: The tutorial appears again after completion

## 2022-9-8 7.0.0

- Added: Open-sourcing at <https://github.com/timer-machine/timer-machine-android>
- Added: Support for Android 12
- Improved: From Android 12, the app requires "Read phone status" to pause timers during phone calls
- Improved: More reliable Tasker support. From Android 12, the app requires battery optimization turning off to continue working
- Improved: The notification now uses the colors from the app theme
- Improved: The time text of the Screen reminder uses the same digital font
- Improved: The group loop shows in the Screen reminder
- Fixed: The missing time label if only one is added.
- Fixed: Occasional crashes caused by schedulers
- Fixed: The broken collaboration between Flashlight and Halt
- Changed: In-app purchases are restored.

## 2021-10-2 6.0.0

- Added: A new reminder: Flashlight
- Added: A new setting: "Screen Brightness Application Timing"
- Added: A new setting: "Media Style Notification"
- Added: A tip for whitelisting the app when a timer is stopped abnormally
- Improved: A Better music picker
- Fixed: A rare crash when exporting app data
- Fixed: The calendar doesn't show the last row of a month
- Changed: In-app purchases are under maintenance, which doesn't affect existing purchasers.
- Changed: The minimum supported Android version changes from 5 to 6

## 2021-8-12 5.8.0

- Added: Vibration count
- Added: Long press step time to edit it quickly
- Improved: Faster restore list load speed
- Improved: New voice variables and new ringtone picker finish testing and become stable
- Improved: Editing a step pauses the timer instead of stopping it
- Improved: Better tutorial
- Improved: Some UI details
- Fixed: Step position is lost after editing a step

## 2021-7-15 5.7.0

- Added: Long-press to share a timer in the timer list
- Improved: Volume setting now opens the system volume settings panel
- Improved: Better tutorial
- Improved: Renovated about page
- Improved: A better new voice dialog on the tablet
- Improved: Editing content of new voice dialog in the landscape mode stops showing the full-screen editor
- Fixed: The tutorial adds the sample timer multiple times after screen rotation

## 2021-6-5 5.6.0

- Added: New voice variables and dialog is under testing. Thank Martin Levy very much for the feedback and help!
- Added: Support for sharing the timer and importing from the clipboard in the edit screen
- Improved: Records from day one will start from the first record

## 2021-3-22 5.5.0

- Added: Baked count sound as a subscription service
- Added: A cancel all button in the timer picker
- Added: A duplicate group button in the add step popup menu of the group end divider
- Added: (Testing)New voice variables. Thank M Lev for the advice!
- Improved: When there is only one timer running, show its name in the overview notification
- Fixed: A crash when switching tutorial pages

## 2021-3-4 5.4.1

- Improved: Faster app startup speed

## 2021-2-16 5.4.0

- Added: Support for Android 11
- Added: Timers grid view
- Fixed: The wrong floating window position after screen rotation
- Fixed: Clicking a shortcut of a deleted timer crashes the app

## 2021-1-10 5.3.0

- Added: Some time-related Voice variables
- Improved: More straightforward writing
- Improved: Displayed time has the same 12/24 hours format as the system settings
- Improved: The error message of failed import includes the details

## 2020-11-30 5.2.0

- Added: Some beautiful app themes have been added to the subscription plan.
- Added: A popup menu to pick Voice variables.
- Added: Elapsed time and remaining time Voice variables that can calculate the value based on the group.
- Improved: The app will also record when manually stopping the timer at the last step of the timer.
- Improved: The fullscreen screen can contain more text.
- Improved: When browsing secondary screens, the menu bar shows a back icon instead of a menu icon.
- Fixed: The app generates corrupted data when exporting to an existing file.

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
