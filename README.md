# Aronno Keyboard - v2.0.0

**Release Date:** January 04, 2026

## 🚀 What's New in v2.0.0?

# Version 2.0.0 - Refactored Core, Performance & Stability

## 🚀 Major Architecture Overhaul
- **Refactored Codebase**: Complete restructuring of the project into `core`, `models`, `ui`, and `utils` packages for better maintainability and scalability.
- **Modernized Imports**: Cleaned up legacy code and streamlined dependencies.

## ⚡ Performance Improvements
- **Faster Suggestions**: Implemented a **Best-First Search (BFS)** algorithm with `maxSubtreeFrequency` pruning in the `SuggestionEngine`. This significantly reduces lookup time for predictions.
- **Optimized Typing**: Replaced memory-heavy `substring` operations with `startsWith` in `AvroParser` to reduce Garbage Collection (GC) pauses during fast typing.
- **Smart Debouncing**: Added a 2-second debounce to User Dictionary saving to prevent disk I/O lag while typing.
- **Enhanced Caching**: Increased Phonetic Cache size (100 -> 500) for smoother transliteration.

## 🐛 Critical Bug Fixes
- **Store Page Crash**: Fixed a crash on the "Store" page caused by an invalid `ThemeIconView` class path.
- **Service Robustness**: Added safety guards (`try-catch`) to `K_THEME` and `K_SETTINGS` to prevent crashes if external activities fail to launch.

## 🎨 Visual & APK Optimization
- **Optimization**: Reduced APK size to **3.8 MB** (from 4.4 MB) by converting app icons and assets to WebP.
- **New Icon**: Updated the App Icon to a premium **3D Green/Gold** design with a transparent adaptive background.
- **Stickers**: Organized and renamed sticker resources for better consistency.

## 📥 Download
[Download AronnoKeyboard_v2.0.0.apk](app/release/AronnoKeyboard_v2.0.0.apk)
