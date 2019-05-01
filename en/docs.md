# TimeR Machine App Docs

Here is all functions detailed information.

## Detailed Explanation of Behaviors

### Music

Play music in this step. Other background sounds will be paused.

- Pick Step Music: By default, the “Beep” sound that comes with the app is played. Here you can select other music.
- Loop: After the music ends, the default loops until the end of the step. Once closed, the music will only play once.

### Vibration

Vibrate the phone in this step.

### Screen

Wake up the screen and pop up the reminder screen.

- Always Fullscreen: It is off by default. When using the phone, only the notification will pop up; when the phone is not in use, the full screen reminder window will pop up. When turned on, the full screen reminder window will pop up whenever you are using your phone.

### Halt

Stay in this step, the time will be positive, you need to manually click the next step to continue running.

### Voice

Use the phone's [Text-to-speech] engine and read some content. Other background sounds will be paused.

- Read Content: When left blank, the step name is read. Here you can set up other reading content.
  - You can use `$loop` to represent the current loop. For example, the content `Cycle $loop` can read the current timer loop or group loop at runtime.

### Beep

Play a beep every second.

- Beep Count: The default is 0 and will continue to beep until the end of the step. After selecting another number, thee beep will be stopped after the corresponding number of times.
- Select Beep Sound: Different beep sounds.
- Respect Other Sound: On by default. It will try to pause other background sounds while running, and stops playing when other background sounds are playing. When turned off, other background sounds will not be paused, regardless of other background sounds, always beeping.