# Aronno Keyboard - v2.0.4

**Release Date:** January 05, 2026

## 🚀 What's New in v2.0.4?

# Version 2.0.4 - Crash Fixes & Smart Cursor

## 🛡️ Stability & Crash Fixes
- **Key Height Slider**: Fixed a critical crash ("crushing") when adjusting keyboard height. The slider is now fortified with deferred rendering and software-layer protection for a butter-smooth experience.
- **Service Stability**: Resolved a background crash that occurred when the active keyboard service tried to reload while settings were being changed.
- **Robustness**: Added multiple safety guards to prevent the app from crashing during rapid configuration changes.

## ⬅️➡️ Smart Volume Cursor
- **Native Cursor Control**: Volume keys now send **Arrow Key** (DPAD) events for reliable cursor movement in all apps. This also enables "press and hold" to scroll through text.
- **Strict Availability**: The feature now works **ONLY when the keyboard is visible**.
    - **Keyboard Open**: Volume Keys move cursor.
    - **Keyboard Closed**: Volume Keys accept standard volume control (Media/Ringer).
- **Default Behavior**: Enabled by default, with the smart safety check to prevent accidental volume changes.

## 🌍 Localization & Polish
- **Bengali Previews**: The Key Height settings preview now correctly displays Bengali text when applicable.
- **Code Hygiene**: Standardized internal logic for better maintainability.

## 📥 Download
[Download AronnoKeyboard_v2.0.4.apk](app/release/AronnoKeyboard_v2.0.4.apk)
