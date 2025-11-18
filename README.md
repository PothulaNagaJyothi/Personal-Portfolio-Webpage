# Personal-Portfolio-Webpage



## Overview
A fully responsive personal portfolio webpage built with pure HTML5 and CSS3 only. The project demonstrates modern web design principles and responsive layouts without using any frameworks or JavaScript.

## Project Structure
```
.
├── index.html      # Main HTML structure
├── styles.css      # Responsive CSS styling with CSS-only hamburger menu
└── readme.md       # Project documentation
```

## Features
- **Header Section**: Logo/name with navigation links (Home, About, Skills, Contact)
- **Hero Section**: Welcome headline, description, and "Contact Me" call-to-action button
- **Skills Section**: Grid layout displaying 6 technical skills with icons and descriptions
- **Footer Section**: Social media links (GitHub, LinkedIn, Twitter) with icons
- **CSS-Only Hamburger Menu**: Mobile navigation using checkbox technique (no JavaScript)

## Responsive Design Breakpoints
- **Desktop (≥1024px)**: Horizontal navigation, 3-column skills grid
- **Tablet (768-1023px)**: Horizontal navigation, 2-column skills grid, reflowing hero text
- **Mobile (≤767px)**: CSS-only hamburger menu with slide-in navigation, 1-column skills grid, no horizontal scroll

## Technical Stack
- HTML5 (semantic markup)
- CSS3 (Flexbox, Grid, Media Queries, :checked pseudo-class)
- No JavaScript or frameworks

## Recent Changes
- 2024-11-18: Initial portfolio webpage creation
  - Created responsive HTML structure with all required sections
  - Implemented mobile-first CSS with three responsive breakpoints
  - Added CSS-only hamburger menu navigation using checkbox technique
  - Configured workflow to serve website on port 5000
  - Removed JavaScript dependency for pure HTML/CSS implementation
