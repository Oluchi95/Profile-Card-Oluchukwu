# Profile Card - Oluchukwu
A responsive, accessible profile card component built with semantic HTML, modern CSS, and vanilla JavaScript as part of the HNG13 Frontend Wizards Stage 0 task.

## Live Demo

[View Live Project](https://oluchi95.github.io/Frontend-Wizards-Profile-Card/) 

## Project Overview

This project implements a fully accessible, responsive profile card component that meets all requirements for the Frontend Wizards Stage 0 task. The component is built with semantic HTML, modern CSS patterns, and includes all required data-testid attributes for automated testing.

## Features

- **Semantic HTML Structure** - Proper use of `<article>`, `<section>`, `<nav>`, and other semantic elements
- **Full Accessibility** - Keyboard navigation, ARIA labels, screen reader friendly
- **Responsive Design** - Mobile-first approach with clean layouts across all screen sizes
- **Testable Elements** - All required data-testid attributes implemented
- **Modern CSS** - Flexbox/Grid layout, CSS custom properties, smooth transitions
- **Vanilla JavaScript** - Real-time timestamp updates without external dependencies

## Technologies Used

- **HTML5** - Semantic markup with accessibility features
- **CSS3** - Flexbox, Grid, custom properties, responsive design
- **Vanilla JavaScript** - DOM manipulation and real-time updates

## Project Structure
```
frontend-wizards-profile-card/
│
├── index.html          # Main profile card implementation
└── README.md           # Project documentation
```

## Quick Start

### Option 1: Direct File Opening
1. Download or clone this repository
2. Open `index.html` in your web browser

### Option 2: Local Development Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Testing

The component includes all required `data-testid` attributes for automated testing:

- `test-profile-card` - Root container
- `test-user-name` - User's name
- `test-user-bio` - Biography paragraph
- `test-user-time` - Current time in milliseconds (updates in real-time)
- `test-user-avatar` - Profile image with alt text
- `test-user-social-links` - Social links container
- `test-user-social-*` - Individual social links (github, twitter, etc.)
- `test-user-hobbies` - Hobbies list
- `test-user-dislikes` - Dislikes list

## Key Implementation Details

### Semantic HTML
- Used `<article>` for the main profile card
- Proper heading hierarchy with `<h2>` and `<h3>`
- `<figure>` and `<figcaption>` for the avatar
- `<nav>` for social links navigation
- `<section>` for content grouping

### Accessibility Features
- Alt text for all images
- ARIA labels where appropriate
- Keyboard navigation support
- Visible focus indicators
- Semantic structure for screen readers

### Responsive Design
- Mobile-first CSS approach
- Flexbox and media queries for layout adaptation
- Content stacking on mobile, side-by-side on desktop
- Fluid typography and spacing

### JavaScript Functionality
- Real-time timestamp updates using `Date.now()`
- Social links open in new tabs with security attributes
- Clean, maintainable vanilla JavaScript

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing
This is a task submission for HNG13 Frontend Wizards Stage 0. While contributions aren't expected for this specific project, feedback and suggestions are welcome!

## License
This project is created as part of the Frontend Wizards program. All rights reserved.

## Author
Built with Love for the HNG13 Frontend Wizards Stage 0 Task
