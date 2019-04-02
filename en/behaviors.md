# [WIP] Detailed Behaviors Explanation

## Music

Play a music at this step.

This will pause all other background audio playback. When it comes with [Voice](#Voice), [Voice](#Voice) will be followed by [Music](#Music).

### Options

- Pick Step Music: By default, A "beep" sound that comes with the app is played.
- Loop: By default, music will loop until the end of the step.

## Vibration

Vibrate the phone at this step.

## Screen

Pop up a reminding screen.

### Options

- Always Fullscreen: The default is off. At this time, when the mobile phone is used, only the notification will pop up; if the mobile phone is not used, a full-screen reminder window will pop up. After turning it on, whether you are using your phone or not, a full-screen reminder window will always pop up.

## Halt

Stay at this step until you move on manually.

## Voice

Read this step name.

This will pause all other background audio playback. When it comes with [Music](#Music), [Voice](#Voice) will be followed by [Music](#Music).

## Beep

Play a beep every second.

This **won't** pause all other background audio playback.

### Options

- Beep Count: The default is 0. It will continue to beep until the end of the step. After selecting other number of times, it will only be paused after the corresponding number of times.
- Select Beep Sound: Different beep sound.
