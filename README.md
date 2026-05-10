# Lift Log

Personal powerbuilding tracker. 4-day Upper/Lower split with Standard and BJJ modes.

**Live:** https://cheetostain.github.io/liftlog/

## Features
- Two program modes: Standard (no BJJ) and BJJ Mode (rolls 3x/wk). Assumes you're a natty and dialed in with 8+ hours sleep, maintenance calories, and 0.7g protein per lb bodyweight.
- Per-set logging with stepper buttons
- Auto-fill from last week's weights
- Mark-day-missed with automatic salvage exercise injection
- IndexedDB persistence (data survives app updates)
- Designed to install as a PWA on iOS

## Install on iPhone
1. Open the live URL in Safari
2. Tap Share → Add to Home Screen
3. Tap Add

## Programs
- **Standard:** Mon/Wed/Fri/Sat lifting, optional jogs
- **BJJ Mode:** Tue/Thu/Fri lifting, BJJ Mon/Wed/Sat, Sat AM hybrid optional

## Stack
Single HTML file. No build step. CSS Variables, vanilla JS, IndexedDB.
