# Dog Website Project

Responsive website about dogs built with HTML5, SCSS, and modern build tools.

## Quick Start

```powershell
# Install dependencies
npm install

# Compile SCSS to CSS
npm run compile

# Development mode with watch
npm run dev

# Production build
npm run prod

# Lint SCSS files
npm run lint

# Validate HTML structure
npm run validate
```

## Project Structure

```
dog-website-project/
├── package.json
├── .prettierrc
├── .gitignore
├── .stylelintrc.json
└── src/
    ├── index.html
    ├── assets/
    │   ├── fonts/
    │   └── (images)
    ├── styles/
    │   ├── kit/
    │   │   ├── _variables.scss
    │   │   ├── _mixins.scss
    │   │   └── _functions.scss
    │   ├── style.scss
    │   ├── mobile.scss
    │   └── (component styles)
    └── dist/
        ├── style.css
        └── style.min.css
```

## Technologies

- HTML5 semantic markup
- SCSS/Sass with BEM methodology
- Flexbox & CSS Grid
- Responsive design (480px, 768px, 1200px)
- PostCSS with Autoprefixer
- CSS optimization and minification

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile devices
- IE11+ (with autoprefixer)
