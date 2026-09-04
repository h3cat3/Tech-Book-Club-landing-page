# Tech Book Club Landing Page

A modern, responsive landing page for a tech book club community built with semantic HTML5, SCSS, and a mobile-first approach. This project demonstrates clean code practices with optimized utility classes and DRY principles.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Features](#features)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Build a landing page for Tech Book Club where users can:

- View the optimal layout on different device screen sizes (mobile, tablet, desktop)
- See hover and focus states for all interactive elements
- Explore membership tiers and join the community
- See testimonials and community information
- Navigate seamlessly between sections

### Features

✅ **Responsive Design** - Mobile-first approach with breakpoints at 768px and 1024px  
✅ **Multiple Sections**:
  - Hero section with membership call-to-action
  - "Read together, grow together" benefits showcase
  - "Not your average book club" description with tech company logos
  - Reading journey timeline (4-step process)
  - Membership options (Starter, Pro, Enterprise)
  - Member testimonials
  - Footer with links and social icons

✅ **Accessible** - Semantic HTML, ARIA labels for ratings, skip-to-main link  
✅ **Optimized Code** - Utility classes to reduce repetition and improve maintainability

### Links

- Solution URL: [GitHub Repository](https://github.com/yourusername/Tech-Book-Club-landing-page)
- Live Site URL: [View Live Site](https://your-live-site-url.com)

## My process

### Built with

- **Semantic HTML5** - Proper markup with header, main, section, article, footer
- **SCSS (Sass)** - Modular styling with partials for colors and typography
- **CSS Grid & Flexbox** - Responsive layout techniques
- **CSS Custom Properties** - Variables for consistent theming
- **Mobile-first Workflow** - Progressive enhancement from small to large screens
- **Accessibility Features** - ARIA labels, semantic structure, keyboard navigation

### What I learned

#### Responsive Typography
Used SCSS mixins for text styles that scale appropriately:
```scss
@include text-style(text-1-mobile); // Mobile size
@media (min-width: 48rem) {
    @include text-style(text-1);   // Tablet+ size
}
```

### Continued development

- [ ] Add interactive JavaScript for navigation menu toggle
- [ ] Enhance form validation for membership signup
- [ ] Add smooth scroll behavior to section links
- [ ] Implement dark mode toggle with CSS custom properties
- [ ] Convert repeated icon patterns to SVG sprites for performance
- [ ] Add animation effects on scroll
- [ ] Further optimize CSS with critical CSS inlining
- [ ] Consider converting to component-based architecture (React/Web Components)

## Author

**Created by:** [Your Name]  
**GitHub:** [@yourusername](https://www.github.com/yourusername)  
**Frontend Mentor:** [@yourusername](https://www.frontendmentor.io/profile/yourusername)  
**Twitter/X:** [@yourusername](https://www.twitter.com/yourusername)

### AI-Assisted Development

This project was developed with assistance from **GitHub Copilot**, which helped with:

- Code refactoring and identifying repeated patterns
- Debugging and optimization suggestions
