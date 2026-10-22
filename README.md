# Namaz Buddy

**A small Windows companion that reminds me to pray.**

## The problem

I wanted a lightweight desktop widget: a tiny cartoon or ball that appears on screen and asks me to pray in a thought bubble.

A straightforward request. Naturally, it became a small character with its own prayer timetable, settings, and snooze button.

## The solution

A native Windows prayer-time companion with a draggable character, city-based schedules, and text reminders, designed to stay small and easy to use.

## What it does

- Draggable on-screen character with thought-bubble reminders.
- City selection and downloaded prayer calendars.
- Prayed, snooze, and dismiss actions.
- Per-prayer time adjustments and fixed-time overrides.
- Offline operation with saved calendars or a complete fixed schedule.
- Tray controls, settings, and optional Windows chime.

## Engineering highlights

Pairs a small native character with city-specific calendar caching, adjustable prayer schedules, fixed-time overrides, and tray controls. The scheduling and storage logic keeps the desktop interaction simple while supporting both downloaded and manually configured times.

## Technology

C#, .NET desktop application, Windows tray integration, AlAdhan prayer-calendar API, local settings/cache.

## Source code

This repository documents the project, its capabilities, and the engineering behind it. The application source code is maintained privately.
