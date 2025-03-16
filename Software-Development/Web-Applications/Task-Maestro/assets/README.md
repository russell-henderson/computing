# Task Maestro - Frontend Assets

## Overview
This directory contains all necessary static assets for the **Task Maestro** frontend, including images, icons, fonts, and styles.

## Folder Structure
```
frontend/assets/
│-- images/
│   ├── logo.png        # Task Maestro logo
│   ├── background.jpg  # Background image for UI
│   ├── icons/
│       ├── add-task.svg
│       ├── delete-task.svg
│       ├── edit-task.svg
│       ├── priority-high.svg
│       ├── priority-medium.svg
│       ├── priority-low.svg
│-- fonts/
│   ├── Montserrat-Regular.woff2  # Primary UI font
│   ├── Montserrat-Bold.woff2
│-- styles/
│   ├── animations.css   # Custom animations for UI interactions
│   ├── themes.css       # Light & dark theme styles
│-- audio/
│   ├── task-complete.mp3   # Sound effect for completing a task
│   ├── achievement-unlock.mp3  # Sound effect for unlocking an achievement
```

## Asset Descriptions
- **Images**: Used for UI branding, background elements, and decorative assets.
- **Icons**: SVG icons for task interactions (adding, editing, deleting, prioritizing tasks).
- **Fonts**: Montserrat is used for a clean, modern look.
- **Styles**: Animation and theme stylesheets to enhance UI experience.
- **Audio**: Sound effects for task completion and achievements.

## Usage
- Place all task-related images/icons inside the `icons/` subfolder.
- Use `themes.css` to modify UI appearance dynamically (e.g., dark/light mode).
- Ensure that sound effects are used sparingly to enhance user engagement.

## Notes
- All SVGs should be optimized for performance.
- Fonts should be preloaded in the HTML `<head>` for better performance.
- Background images should be compressed to minimize load time.

## Contribution
New assets should follow the existing structure. If adding a new asset type, update this document accordingly.
