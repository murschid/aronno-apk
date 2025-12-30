# Aronno Keyboard - v1.1.5

**Release Date:** December 30, 2025

## 🚀 What's New in v1.1.5?

# Version 1.1.5 - Smooth Spacebar Swipe & Polish

## ✨ New Features
### **Smooth Spacebar Language Switcher**
- **Carousel Interaction:** Swiping the spacebar now reveals a smooth 3-item carousel (Previous | Current | Next) that slides with your finger.
- **Outside-In Animation:** Neighbors slide in from the edges for a polished "scrolling tape" effect.
- **Instant Response:** Optimized for zero-lag appearance immediately upon touch.
- **Smart Selection:** Clamped logic ensures the visual "Next" item is exactly what gets selected, preventing accidental skips.

## 🎨 Visual Refinements
- **Unified Popup Styling:** The language switcher popup now uses a unified opacity (solid alpha) for all items.
- **Clean Focus:** "Current" item uses normal font weight for a balanced, premium look.
- **Correct Positioning:** The popup appears distinctly *above* the key, not covering it.

## 🚀 Code Optimization
- **Zero-Lag Initialization:** Implemented pre-initialization on `ACTION_DOWN` to eliminate initial frame drops.
- **Clean Codebase:** Removed redundant calculations and improved loop efficiency for buttery smooth 60fps animations.

## 📥 Download
[Download AronnoKeyboard_v1.1.5.apk](app/release/AronnoKeyboard_v1.1.5.apk)
