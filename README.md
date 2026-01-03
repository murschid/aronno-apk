# Aronno Keyboard - v1.1.11

**Release Date:** January 03, 2026

## 🚀 What's New in v1.1.11?

# Version 1.1.11 - Layout Perfection & Bug Fixes

## ⌨️ Layout Updates
- **Aronno Layout**: Optimized for speed (Split-hand ergonomics). Removed duplicate keys. Added dedicated keys for vital characters.
- **National Layout**: Added Bengali numbers and missing secondary characters.
- **Probhat Layout**: Added missing 'Khanda-Ta' and Folas to popups.
- **Bijoy Layout**: Verified completeness.

## 🐛 Bug Fixes
- **Select All**: Fixed backspace not deleting selected text.
- **GIFs**: Fixed GIF loading issue in release builds.

### **Native Bengali GIF Integration**
- **Localized Categories:** Added dedicated categories: "ট্রেন্ডিং" (Trending), "খুশি" (Happy), "দুঃখ" (Sad), "ভালোবাসা" (Love), "রাগ" (Angry), "ওয়াও" (Wow), and "মজার" (Funny).
- **Smart Localization:** Implemented explicit "Bengali" search prefixes (e.g., "Bengali Love", "Bangladesh") to guarantee culturally relevant content from the Tenor API foundation.
- **Infinite Scroll:** Integrated seamless pagination (lazy loading) for endless GIF browsing.

### **Visual & UX Polish**
- **Unified Aesthetic:** GIF grid updated to 5 columns with 64dp height and 2dp margins, perfectly matching the Sticker UI for a cohesive look.
- **New Icon:** Updated GIF tab icon to `gif_box` (Material Symbols, weight 300) for a modern, refined appearance.
- **Auto-Loading:** Initial "Trending" category now loads instantly upon opening the tab.

## 🛠 Stability & Performance

### **System Improvements**
- **Memory Management:** Implemented `onTrimMemory` and aggressive view recycling in `ProgrammaticGifAdapter` to ensure the keyboard remains lightweight and crash-free.
- **Robust Error Handling:** Fixed JSON mapping issues ("No GIFs found") and added graceful error states for network failures.
- **Clean Code:** Resolved all lint warnings and optimized resource usage (strings.xml).

## 📥 Download
[Download AronnoKeyboard_v1.1.11.apk](app/release/AronnoKeyboard_v1.1.11.apk)
