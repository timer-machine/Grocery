# Change Log

## 2018-5-7 3.3.1

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
- <b>Changed: Previously created timer which uses beep behavior may not pause other background sound unless you toggle those beep behaviors' option on and off once again manually.</b> Developer apologizes to you for this bug.

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

Too lazy to copy and paste them...