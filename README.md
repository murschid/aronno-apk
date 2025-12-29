# Aronno Keyboard - v1.1.4

**Release Date:** December 29, 2025

## 🚀 What's New in v1.1.4?

# Version 1.1.4 - UI Refinements & Code Optimization

## ✨ Visual Enhancements
### Toolbar Icon Sizing
- **Larger Icons**: Reduced toolbar icon padding from 14dp to 12dp (top/bottom), making icons more prominent and easier to tap
- **Better Visual Balance**: Icons now have ~24dp effective size vs. previous ~20dp

### Emoji & Sticker Optimization
- **Fixed Clipping**: Reduced emoji size from 44dp to 40dp and text from 28sp to 25sp to prevent bottom clipping
- **Sticker Refinement**: Reduced sticker size from 70dp to 64dp and padding from 8dp to 6dp/4dp for better fit
- **Maintained Minimal Padding**: Kept tight keyboard spacing while eliminating visual artifacts

## 🚀 Code Quality Improvements
### Removed Resource Reflection
- **DataSafetyActivity**: Replaced `getIdentifier()` with direct `com.google.android.material.R.id.design_bottom_sheet` reference
- **Better Performance**: Eliminated runtime reflection overhead for improved efficiency
- **Build Optimization**: Enabled ProGuard/R8 to optimize resources at compile-time

### LocaleHelper Refactoring
- **Cleaner Code**: Removed redundant `defaultLanguage` parameter by using constant `DEFAULT_LANGUAGE = "bn"`
- **Type Safety**: Improved compile-time verification and reduced code duplication

## 🐛 Bug Fixes
- Fixed emoji and sticker bottom clipping in keyboard views

## 📥 Download
[Download AronnoKeyboard_v1.1.4.apk](app/release/AronnoKeyboard_v1.1.4.apk)
