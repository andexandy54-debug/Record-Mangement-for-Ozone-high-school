# Ozone High School - Technical Documentation

This repository contains the web-based Record Management System for Ozone High School. 

## Project Architecture

### 1. Global Navigation & Layout
The project utilizes a persistent header and footer architecture. This ensures a consistent user experience and navigation across all sub-modules. 
- **Header**: Contains the primary site navigation and the Admissions dropdown interface.
- **Footer**: Standardized contact and copyright information.

### 2. Styling System (`styles.css`)
The design follows a modular CSS approach. Key variables and component styles are documented within the file for ease of maintenance.
- **Color Palette**: The primary brand colors (Red/Teal) are defined in the `header` and `footer` blocks.
- **Dropdown Logic**: Implemented using pure CSS hover states for the Admissions menu.

### 3. File Structure
- `index.html`: The main entry point and authentication portal.
- `Home.html`: The core informational landing page.
- `Admissions.html`: Contains the enrollment process and anchor points for the dropdown menu.
- `About.html`, `Academic.html`, `Staff.html`, `contact.html`: Specialized content modules.

## Maintenance Guide

### Modifying Content
When updating page-specific text, ensure you remain outside of the HTML tag definitions (`< >`). To update the navigation bar, changes must be reflected across all HTML files to maintain consistency.

### Styling Updates
To adjust the visual theme, modify the CSS rules in `styles.css`. Each section is clearly labeled (e.g., `/* 2. THE PERSISTENT HEADER */`) to facilitate rapid identification of style blocks.
