# iOS 26 Design Update - Gluska Management Website

## Overview
The website layout has been updated with modern Apple iOS 26-inspired design principles, bringing a cleaner, more refined aesthetic to the Gluska Management brand.

## Key Design Changes

### 1. **Navigation Header** 
- **Fixed Position**: Header now stays at the top with blur effect
- **Glassmorphism**: Frosted glass background with `backdrop-filter: blur(20px)`
- **Apple Colors**: Changed from green (#009E66) to iOS blue (#0071e3)
- **SF Pro Font**: Using Apple's system font stack
- **Smooth Transitions**: Cubic-bezier easing for natural animations
- **Rounded Hover States**: 8px border radius on navigation items

### 2. **Hero/Slider Section**
- **Light Background**: Changed from dark with image to clean gradient
- **Modern Typography**: 48px SF Pro Display with negative letter spacing
- **Subtle Effects**: Soft gradient blur orbs instead of solid circles
- **Better Readability**: Dark text (#1d1d1f) on light background

### 3. **Service Cards (Brands Section)**
- **iOS Card Design**: 16px rounded corners with subtle shadows
- **Elevation on Hover**: Cards lift 8px with enhanced shadow
- **Light Theme**: White cards on white background
- **Modern Spacing**: 32px padding with 24px gaps
- **SF Pro Typography**: System fonts throughout
- **iOS Blue Accents**: #0071e3 for interactive elements
- **Arrow Indicators**: Animated arrows (→) instead of underlines
- **Smooth Interactions**: Cubic-bezier animations

### 4. **Typography System**
- **Headings**: SF Pro Display for large text
- **Body**: SF Pro Text for readable content
- **Letter Spacing**: Negative tracking on large headings (-0.5px)
- **Line Height**: 1.6 for optimal readability
- **Font Smoothing**: Antialiased rendering

### 5. **Color Palette**
#### Primary Colors:
- **iOS Blue**: #0071e3 (primary actions)
- **Text Dark**: #1d1d1f (primary text)
- **Text Secondary**: #6e6e73 (secondary text)
- **Text Tertiary**: #86868b (labels)
- **Background**: #ffffff (primary)
- **Background Secondary**: #f5f5f7 (sections)

#### Interactive States:
- **Hover**: rgba(0, 113, 227, 0.08) (8% blue tint)
- **Shadows**: Layered shadows with blue tint on hover
- **Borders**: rgba(0, 0, 0, 0.04) (subtle separation)

### 6. **About Section**
- **Light Background**: #f5f5f7 instead of dark
- **Modern Text**: 17px body text with improved line height
- **iOS Typography**: SF Pro font family
- **Better Hierarchy**: Refined heading sizes and spacing

### 7. **Animation & Transitions**
- **Easing**: `cubic-bezier(0.25, 0.46, 0.45, 0.94)` for natural motion
- **Smooth Scrolling**: Enabled globally
- **Transform Animations**: Scale and translateY for depth
- **Consistent Timing**: 0.3s transitions throughout

## Benefits

✅ **Modern & Professional**: Aligns with current design trends
✅ **Better Accessibility**: Improved contrast and readability
✅ **Smooth Interactions**: Professional animations and transitions
✅ **Brand Consistency**: Apple-like quality matches premium wellness brands
✅ **Mobile-Ready**: Design principles scale well to mobile devices
✅ **Faster Loading**: Lighter color scheme and optimized styles

## Files Modified

1. **style.css** - Main stylesheet with iOS 26 design system
   - Navigation header updates
   - Hero section redesign
   - Service cards styling
   - Typography system
   - Color palette updates
   - About section updates

## Browser Compatibility

- Chrome/Edge (Modern)
- Safari 14+
- Firefox 90+
- Mobile browsers with backdrop-filter support

## Next Steps (Recommended)

1. Test responsive behavior on various devices
2. Update remaining sections (portfolio, contact) with iOS 26 styling
3. Add iOS-style transitions between sections
4. Consider adding dark mode support
5. Optimize images for the new lighter background

---

**Date Updated**: January 21, 2026
**Design System**: Apple iOS 26 Inspired
**Framework**: Custom CSS with SF Pro Font Stack
