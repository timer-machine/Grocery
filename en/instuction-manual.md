# TimeR Machine Instruction Manual

> Complex Task Requires Complex App

This article is trying its best to introduce how to use TimeR Machine.

## Table of Contents

1. [Basic Concepts](#Basic-Concepts)
1. [Timer Examples](#Timer-Examples)
1. [UI Instructions](#UI-Instructions)
1. [Differences from CycleTimer](#Differences-from-CycleTimer)
1. [Contact](#Contact)

## Basic Concepts

1. Timer

    This is NOT the traditional timer, but a task which contains several timers and loops.

1. Step

    This represents there is something to be done in a certain period.

1. Behavior

    A part of a step. It determines when this step is in progress, how the smartphone reminds you.

    - **A step without no behavior only counts down silently and goes to the next step silently. To get reminded when a step finishes, please add a step with behaviors.**
    - Current available behaviors: Music, Vibration, Screen (Pop up a reminding screen), Halt (Stay at this step until you move on manually), Voice (Read the step name), Beep (Play a beep every second)

## Timer Examples

### 1. Simple One

This is an exercise plan where we run and walk and repeat 3 times.

![Simple One](instruction-manual/simple-timer.webp)

Some steps have special colors. The first step and the last step are:

> Start Step and End Step: A timer may have loops and these two steps are the signals for the whole timer's start and end. Each of them will be executed only once at the start and the end of a timer.

"Timer Start" and "Timer End" is the beginning and finishing of the timer. They have some behaviors, or we'll never know when the timer starts or finishes.

The next "Run" step has no behavior and simply counts down silently. After it, that's a "notifier":

> Notifier Step: A convenient remind step
> - It remembers what you've edited and the same step will be added the next time you add a notifier.
> - When you tweak time at a notifier step, the timer will go back to the previous step and set time to 1 minute (This can be turned off in the app settings).

In this way, we'll know when we should stop running and start walking.

This timer has 3 loops. After (run + notifier + walk + notifier) * 3, we'll enter end step and then our exercise plan completes🎉

### 2. Complex One

In this plan, we warm up, run and walk 13 times, long run and rest.

![Complex One](instruction-manual/complex-timer.webp)

↓ Notice the timer loop is 1. Because our plan is too complicated to separate into loops. We need precise control.

![1](instruction-manual/complex-timer1.webp)

↑ First, start step and warm up step use voice and beep behaviors. But, there is no notifier after them. Actually, some behaviors only run once at the start of a step, so we can use them to remind us that a step starts (of course you can add notifiers alternatively).

The next notifier indicates a "Group" is coming:

> Group：kind of a sub-timer. It has its own name and loop and can contain steps.

↓ Here we put "Run" and "Walk" steps into the group and set loop to 13.

![2](instruction-manual/complex-timer2.webp)

↓ The next notifier tells us that the group is done and long run is about to start. After it, we add a step with halt behavior(Stay at this step until you move on manually) which is perfect for the situation where the time is indeterminate. After the long run, we'll go to the next step manually.

> Halt will make a timer stop counting down and ignore a step's duration.

We'll have some rest at the end step.

![3](instruction-manual/complex-timer3.webp)

## UI Instructions

- Add a step

    ![Add a step](instruction-manual/add-step1.webp)

    ![Add a step](instruction-manual/add-step2.webp)

- Remove a step

    ![Remove a step](instruction-manual/remove-step.webp)

- Add a behavior

    ![Add a behavior](instruction-manual/add-behavior.webp)

- Edit a behavior

    ![Edit a behavior](instruction-manual/edit-behavior.webp)

- Long click step or behavior to check its explanation

    ![Step explanation](instruction-manual/tooltip1.webp)
    ![Behavior explanation](instruction-manual/tooltip2.webp)

## Differences from CycleTimer

1. There is no further maintenance for CycleTimer. But, the development task is still in progress. TimeR Machine is its successor.

2. In CycleTimer, reminders between steps are global and automatically added. You don't need to add them manually. In TimeR Machine, you must add a step with behaviors or you'll never get reminded.

## Contact

In the app, click menu -> [Help & Feedback] -> Scroll to the bottom -> [Feedback] or [Here](mailto:ligrsidfd@gmail.com). You'll get replied within 24 hours.
