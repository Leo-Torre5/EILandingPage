# Standalone HTML Project

A self-contained HTML project that runs without any build tools or frameworks.

## Quick Start

Simply open the HTML file in your browser:

```bash
# Option 1: Double-click the file
open dist/index.html

# Option 2: Use the npm script
npm start

# Option 3: Serve locally (optional)
npm run serve
# Then visit http://localhost:8000
```

## Project Structure

```
/
├── dist/
│   ├── index.html     # Main page (self-contained)
│   └── README.md      # Technical documentation
├── package.json       # Minimal package file (optional)
└── README.md          # This file
```

## Features

- ✅ **No build tools required** - Just open index.html
- ✅ **No dependencies** - Pure HTML, CSS, and JavaScript
- ✅ **Responsive design** - Works on all screen sizes
- ✅ **Modern styling** - Clean, professional appearance
- ✅ **Cross-browser compatible** - Works in all modern browsers

## Technical Details

The `dist/index.html` file contains:
- Inlined CSS (compiled from Tailwind)
- Semantic HTML5 markup
- Responsive design with mobile-first approach
- Hover effects and smooth transitions
- Dark/light mode support via CSS media queries

## No Framework Dependencies

This project intentionally avoids:
- React, Vue, Angular, or other frameworks
- Build tools like Webpack, Vite, or Parcel
- CSS preprocessors or PostCSS
- Package managers for runtime dependencies

The result is a simple, fast-loading page that works anywhere.