# Technical Documentation - C+N Hosting Website

## Architecture Overview

This is a single-page application (SPA) built with vanilla HTML, CSS, and JavaScript. The website uses a simple Node.js server for local development but can be deployed as static files.

## File Structure

```
├── index.html          # Main HTML structure
├── styles.css          # All styling and animations
├── script.js           # Client-side JavaScript functionality
├── server.js           # Express.js development server
├── package.json        # Node.js dependencies
├── README.md           # User-facing documentation
└── TECHNICAL.md        # This file
```

## Key Technologies

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Fonts**: Atkinson Hyperlegible (Google Fonts)
- **Icons**: Font Awesome 6.0
- **Development Server**: Express.js
- **Storage**: localStorage for email persistence

## JavaScript Features

### 1. Email Auto-fill System
Triggered when pricing plan buttons are clicked. Auto-fills contact form with:
- Plan name and price in subject
- Smart field focusing
- Email persistence with localStorage
- Visual feedback animations

### 2. Mobile Navigation
- Auto-hiding navbar on scroll
- Hamburger menu toggle
- Close on outside click
- Smooth scroll behavior

### 3. Form Validation
- Email regex validation
- Required field checking
- Success/error notifications
- Form reset after submission

### 4. Notification System
- Dynamic notification creation
- Auto-dismiss after 5 seconds
- Multiple notification types (success, error, info)
- Slide-in animations

## CSS Architecture

### Color Scheme
- Primary Background: #000000
- Accent Orange: #FF8C00
- Accent Pink: #FFB6C1
- Success Green: #00ff88
- Text Primary: #ffffff
- Text Secondary: #cccccc

### Key Animations
1. **Pulse Highlight** - Used for form field emphasis with scale and shadow animation
2. **Hero Parallax** - Subtle vertical translation on scroll
3. **Typing Effect** - Character-by-character reveal for hero title

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## Performance Optimizations

1. Intersection Observer for lazy animations
2. Debounced scroll events for navbar behavior
3. CSS animations preferred over JavaScript
4. Minimal dependencies (only Font Awesome external)

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- ES6+ JavaScript features used
- CSS Grid and Flexbox for layouts
- No IE11 support

## Security Considerations

1. Form Validation: Client-side only (server-side needed for production)
2. localStorage: Used for email only (no sensitive data)
3. External Resources: Font Awesome CDN (consider self-hosting)

## Deployment Notes

### Static Hosting
Remove server.js and package.json, deploy only:
- index.html
- styles.css
- script.js

### Node.js Hosting
Use included server.js with environment variable for port.

## Future Enhancements

1. Form Backend: Integrate with email service (SendGrid, Mailgun)
2. Analytics: Add privacy-friendly analytics (Plausible, Fathom)
3. A11y: Add ARIA labels and keyboard navigation improvements
4. Performance: Implement service worker for offline support
5. SEO: Add meta tags and structured data
