# AI Usage Report

## Overview

AI was used as a learning support tool to assist with structuring logic, solving technical challenges, and improving code organization.
All final code was reviewed, tested, and adjusted manually to ensure full understanding.

## JavaScript – Most Challenging Parts

1. Scroll Spy (IntersectionObserver)
The most technically complex part was implementing the IntersectionObserver API to detect which section is currently visible on the screen and dynamically highlight the correct navigation link.

AI assisted with:
- Structuring the observer configuration (threshold, rootMargin)
- Sorting visible entries to select the most dominant section
- Mapping section IDs to navigation links efficiently
The final implementation was tested and refined manually to ensure correct behavior during scrolling.

2. Dynamic Project Rendering
Instead of hardcoding project cards in HTML, projects were generated dynamically using:

- A structured JavaScript array (PROJECTS)
- map() to create reusable project card templates
- Template literals for injecting project data into HTML
- .join("") to render the final output into the DOM
AI helped structure the rendering logic cleanly and efficiently.

3. Dark Mode with localStorage
Implementing theme persistence required:

- Toggling a data-theme attribute on <html>
- Updating UI elements (icon + text)
- Saving user preference in localStorage
- Loading the saved theme on page refresh
AI assisted with structuring the toggle logic and ensuring persistence worked correctly.


4. CSS Assistance
AI was used to help structure layout-related styling such as:

- Defining container widths for consistent page alignment
- Managing spacing between sections
- Setting responsive breakpoints
- Structuring grid layouts like project section
- Controlling padding and margin for clean content spacing
All layout sizing and spacing decisions were reviewed and adjusted manually.

## Learning Outcome
AI was used responsibly as a development assistant, not as a replacement.
The process improved understanding of:

- DOM manipulation
- Event handling
- State persistence
- Responsive layout structure
- JavaScript modular organization
The final project reflects independent understanding and applied problem-solving skills.


