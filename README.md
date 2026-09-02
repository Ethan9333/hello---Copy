# Mobile UI/UX Student Profile

An upgraded, responsive, accessible Student Profile built using HTML and CSS, bundled for Android via Apache Cordova.

## 1. Project Description
This application serves as a digital student profile. It highlights my personal background information, interests, education, goals, and technical skill sets.

## 2. Application Structure
Header: houses the user profile avatar, complete name, subtitle, and primary navigation bar.<br>
Navigation Menu: accessible links allowing intra-page navigation between sections.<br>
About Section: contains background information, personal interests, education details, and future aspirations.<br>
Skills Section: itemizes core technical skills alongside clear descriptive details.<br>
Footer: displays my copyright notice and year.

## 3. Responsive Design
The application utilizes a mobile-first fluid layout implemented with standard CSS media queries (`@media (min-width: 600px)` and `@media (min-width: 900px)`). 
Mobile: Single-column stacked layout avoiding horizontal scroll.
Tablet: Flexible inline header alignment and enhanced padding for medium screens.
Desktop: Two-column grid layout utilizing screen real estate efficiently while keeping line lengths comfortable to read.

## 4. UI/UX Principles Applied (Module 4)
Responsive Layout: Fluid width styling (`width: 90%`, `max-width: 1000px`) combined with CSS Grid/Flexbox to prevent overflow and text truncation.
Mobile-Friendly Spacing: Standardized outer padding and margins (`rem` units) ensure distinct boundaries between text blocks and cards.
Appropriate Typography: Uses scalable `rem` font sizes, high line-height (`1.6`), and modern system font stacks for optimal readability.
Clear Visual Hierarchy: Distinct font weights and colors separate section titles (`h2`), subtitles (`h3`), bold labels, and body copy.
Usable Controls: Touch-friendly navigation targets designed with minimum click targets ($\ge 44\text{px}$) and clear hover/focus indicators.
Basic Accessibility: Contrast-compliant background colors, semantic HTML structural tags (`<header>`, `<main>`, `<section>`, `<nav>`), dynamic image `alt` text, and clear focus styling.
Consistent Design: Utilizes CSS custom variables (`:root`) for color scheme, font stacks, border radiuses, and spacing patterns.

## 5. Navigation
The intra-page navigation uses native HTML anchor links (`href="#about"` and `href="#skills"`). It requires zero JavaScript and relies on standard HTML document fragment identifier scrolling with CSS `scroll-behavior: smooth`.

## 6. How to Run

# Clean previous builds
cordova clean android

# Build the Android APK
cordova build android

# Run android
cordova run android
```

## 7. Application Screenshots

### Desktop Layout
![Desktop View](screenshots/desktop.png)

### Tablet Layout
![Tablet View](screenshots/tablet.png)

### Mobile Layout
![Mobile View](screenshots/mobile.png)
