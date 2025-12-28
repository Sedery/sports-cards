# STE Cards

## Overview
A static website for STE Cards - a custom sports cards business. The site showcases sports card products across NFL, NBA, and MLB categories and includes a contact form for custom card requests.

## Project Structure
- `index.html` - Main landing page with product showcase
- `contact.html` - Contact/request form page
- `style.css` - Stylesheet for the website
- `logo.jpg` - Company logo

## Technology Stack
- Static HTML/CSS website
- No build system required
- Python HTTP server for local development

## Running the Project
The website is served using Python's built-in HTTP server on port 5000:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a static site deployment serving files from the root directory.
