# Lily Pad Math

A talking kindergarten math game. Pip the frog hops one lily pad for every right answer; cross the pond to collect a new animal friend.

**Play:** https://dfreed.github.io/lily-pad-math/

## What it practises
Counting, quick-look dot recognition (subitizing), finding numbers to 100, more/fewer, what comes next and counting by 10s, adding and taking away to 20, and making 5 and 10 with ten-frames.

## How it adapts
Each skill has levels. Four first-try right answers out of the last five moves a skill up; a run of misses steps it back down. Missed questions come back a few turns later, and new games open as earlier skills grow. A wrong answer triggers a guided "let's count together" walkthrough instead of a buzzer.

Grown-ups: press and hold the button at the top right for names, voice, per-skill progress and level controls, and a "head start" for children who are already ahead.

## Install on an iPad
1. Open the link above in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. Launch it from the frog icon. It runs full screen and works offline after the first visit.

Progress is stored on the device (in the home-screen app's own storage). No accounts, no tracking, nothing leaves the iPad.

## Files
- `index.html`: the whole game (HTML, CSS and JS in one file)
- `sw.js`: service worker for offline play (bump `VERSION` after changes)
- `manifest.webmanifest`, `*.png`: app name and icons
