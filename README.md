# Aronno Keyboard - v1.1.6

**Release Date:** January 03, 2026

## 🚀 What's New in v1.1.6?

# Version 1.1.6 - Phonetic Polish & Zero-XML

## ✨ New Features
### **Visual Polish for Phonetic Input**
- **Underline Removal:** Implemented `setComposingTextNoUnderline` to remove the distracting system underline during phonetic typing. Text commits instantly for a cleaner, native feel.
- **Volume Key Cursor Control:** Use Volume Up/Down keys to move the cursor left/right precisely.

### **Layout Enhancements**
- **Increased Layout Limit:** Users can now select up to **4 active layouts** (previously 3).
- **Aronno Default:** Added "Aronno" layout to the default set for new users.

## 🧹 Maintenance & Cleanup
### **Zero-XML Architecture Complete**
- **Removed Legacy Artifacts:** Deleted all unused XML layout files (`keyboard_view.xml`, etc.) and legacy resources.
- **Pure Canvas Engine:** The keyboard now relies entirely on the `AronnoCanvasView` engine, with no XML overhead for key rendering.
- **Resource Optimization:** Cleaned up unused drawables while preserving essential Theme Preview resources.

### **Bug Fixes**
- **Lint Fixes:** Resolved unused parameter warnings in lifecycle methods.
- **Build Integrity:** Verified build success after extensive cleanup.

## 📥 Download
[Download AronnoKeyboard_v1.1.6.apk](app/release/AronnoKeyboard_v1.1.6.apk)
