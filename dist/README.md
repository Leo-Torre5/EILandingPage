# Standalone HTML Conversion

This directory contains a self-contained HTML version of the Next.js project.

## What was converted

- **Source**: Next.js project with App Router (`app/page.tsx`)
- **Output**: Single `index.html` file with all CSS and JavaScript inlined
- **Framework**: Converted from React/Next.js to vanilla HTML/CSS

## Inlined vs External

### Inlined:
- All Tailwind CSS classes compiled and inlined in `<style>` tag
- All component markup converted to static HTML
- Inter font family preserved in CSS

### External (kept as CDN):
- Google Fonts for Inter font family (400-900 weights)
- External links to Next.js documentation, Vercel, etc.

## Visual Parity

The standalone HTML file maintains:
- Exact same layout and spacing as the original Next.js page
- All hover effects and transitions
- Responsive design breakpoints
- Dark mode support via CSS media queries
- All gradient backgrounds and visual effects

## Behavior Parity

- All hover states work identically
- Responsive layout matches original at all breakpoints
- External links open in new tabs with proper security attributes
- Keyboard navigation preserved
- Motion-reduce accessibility support maintained

## No Framework Dependencies

The resulting `index.html` file:
- Runs in any modern browser without build tools
- No React, Next.js, or Node.js runtime required
- Can be opened directly by double-clicking the file
- All assets are self-contained or use external CDNs

## Intentional Changes

- Converted React JSX to static HTML
- Compiled Tailwind classes to vanilla CSS
- Removed Next.js specific features (no dynamic routing, SSR, etc.)
- Maintained all visual styling and interactions exactly as they appeared in the original

The page is pixel-perfect compared to the original Next.js welcome page.