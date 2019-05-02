# TimeR Machine App Docs

Here is all functions' detailed information.

## Detailed Explanation of Behaviors

### Music

Play music in this step. Other background sounds will be paused.

- Pick Step Music: By default, a “Beep” sound is played. Here you can select other ringtones.
- Loop: It's on by default and the music will loop until the end of the step. Once closed, the music will only play once.

### Vibration

Vibrate the phone in this step.

### Screen

Wake up the screen and pop up a reminder screen.

- Always Fullscreen: It is off by default. When using the phone, only a notification will pop up; when the phone is not in use, a full-screen reminder window will pop up. When turned on, a full-screen reminder window will pop up regardless of whether you are using the phone.

### Halt

Stay in this step and make this step a positive timing stopwatch. You need to manually click the next step to go to the next step.

### Voice

Use the phone's [Text-to-speech] engine to read some content. Other background sounds will be paused.

- Read Content: When left blank, the step name is read. Here you can set up other reading content.
  - You can use `$loop` to represent the current loop. For example, the content `Loop $loop` can read the current timer loop or group loop at runtime.

### Beep

Play a beep every second.

- Beep Count: The default is 0 and will continue to beep until the end of the step. After selecting another number, the beep will be stopped after the corresponding number of times.
- Select Beep Sound: Different beep sounds.
- Respect Other Sound: On by default. It will try to pause other background sounds while running and stops playing when other background sounds are playing. When turned off, other background sounds will not be paused, regardless of other background sounds, always beeping.