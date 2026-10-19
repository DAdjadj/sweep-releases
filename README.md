# Sweep

A free macOS menu bar app that clears every notification at once, with one keyboard shortcut
(⌥⌘⌫ by default).

This repository only holds the downloads. Get the latest version from
[Releases](https://github.com/DAdjadj/sweep-releases/releases/latest).

## Install

1. Download `Sweep.zip` from the latest release and unzip it.
2. Move **Sweep** to your Applications folder and open it.
3. The first time, macOS may say it can't verify the app. Open System Settings > Privacy & Security,
   scroll down and click **Open Anyway**. This is needed once.
4. Allow Accessibility access when asked. macOS has no other way for an app to clear notifications:
   Sweep uses it only to open Notification Center, press each notification's clear button and close
   it again.

Requires macOS 26 or later, on Apple Silicon or Intel. Sweep updates itself: it checks once a day, or
choose Check for Updates from its menu.

The menu bar icon can be hidden in Preferences; the shortcut keeps working. Open Sweep again from
Spotlight or Finder to get back to Preferences.

## Privacy

Sweep never reads or keeps what your notifications say, and sends nothing anywhere: no accounts, no
analytics, no servers. The only network request it makes is the update check, which asks GitHub for
the latest version number and contains nothing about you.
