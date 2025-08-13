# Overview

HIRU is a personal bio website that serves as a digital portfolio and personal branding page. The project is a single-page application built with vanilla HTML, CSS, and JavaScript, designed to showcase personal information, skills, and contact details in a clean, modern interface.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Single Page Application**: Built using vanilla HTML, CSS, and JavaScript without any frameworks
- **Mobile-First Design**: Responsive layout that prioritizes mobile experience and scales up to desktop
- **CSS Custom Properties**: Implements a theming system using CSS variables for easy color scheme modifications
- **Component-Based Styling**: CSS is organized around reusable components (header, avatar, container, etc.)

## Design System
- **Dark Theme**: Default dark color scheme with customizable theme variables
- **Typography**: Uses system fonts (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto) for optimal cross-platform rendering
- **Layout**: Flexbox-based layout system for responsive design
- **Spacing**: Consistent spacing system using gaps and padding

## File Structure
- **index.html**: Main and only HTML file containing the complete application
- **Inline Styles**: All CSS is embedded within the HTML file for simplicity and single-file deployment
- **Self-Contained**: No external dependencies or build process required

## Responsive Design Strategy
- **Container System**: Centered container with maximum width constraints
- **Flexible Grid**: Uses CSS Flexbox for layout management
- **Viewport Optimization**: Proper viewport meta tag for mobile rendering

# External Dependencies

## None Required
- **No JavaScript Frameworks**: Pure vanilla JavaScript implementation
- **No CSS Frameworks**: Custom CSS without external libraries
- **No Build Tools**: Direct HTML file that can be served statically
- **No External Fonts**: Relies on system font stack
- **No CDNs**: Self-contained application with no external resources

## Hosting Requirements
- **Static Hosting**: Can be deployed on any static file hosting service
- **No Server-Side Processing**: Pure client-side application
- **No Database**: All content is hardcoded in the HTML structure