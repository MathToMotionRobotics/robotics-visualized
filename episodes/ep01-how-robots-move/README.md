# EP01 — How Does a Robot Actually Move?

## Chinese Title

机器人究竟是怎么动起来的？

## Central Question

How does a desired motion become physical movement in a real robot?

## Learning Objective

After watching this episode, the viewer should be able to explain the complete feedback loop:

```text
Target
→ Controller
→ Motor
→ Mechanical Motion
→ Sensor
→ Feedback
```

## Core Idea

A robot does not simply receive a command and move correctly.

It repeatedly:

1. receives a target
2. measures its current state
3. calculates the error
4. generates a control command
5. drives the motor
6. measures the result again

This repeated process forms a closed-loop control system.

## Scope

This episode introduces:

- target commands
- controllers
- motors
- mechanical motion
- sensors
- feedback
- closed-loop control

This episode does not explain:

- detailed PID mathematics
- motor electromagnetics
- robot dynamics equations
- communication protocol details
- state estimation algorithms

These topics will be covered in later episodes.

## Viewer Takeaway

By the end of the episode, the viewer should understand that robot motion is created by a continuous information loop rather than a single command.

## Required Outputs

- [ ] Concept document
- [ ] Storyboard
- [ ] Chinese script
- [ ] English script
- [ ] Manim animation
- [ ] Simulation
- [ ] Chinese voice-over
- [ ] English voice-over
- [ ] Chinese subtitles
- [ ] English subtitles
- [ ] Final video
- [ ] Thumbnail
- [ ] Source references

## Status

Planning
