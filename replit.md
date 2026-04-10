# MarianLINK / Meowlink

A personal "biolink" style landing page with a dark aesthetic theme.

## Tech Stack

- Pure static HTML, CSS, and JavaScript (no build tools or frameworks)
- Custom fonts, background music, and visual effects (snowflakes, blood sparks)
- Bootstrap CSS (local copy)
- Font Awesome (CDN)

## Project Structure

```
.
├── index.html          # Main landing page with "click me" entry overlay
├── css/                # Stylesheets (main.css, style.css, bootstrap.min.css)
├── fonts/              # Custom TTF/WOFF font files
├── images/             # Profile pictures and backgrounds
├── $/                  # Members sub-section
│   ├── index.html      # Member landing page
│   ├── members.html    # User profiles list
│   └── styles.css      # Sub-section styles
├── snowstorm.js        # Snowflake visual effect
├── anti-inspect-element.js  # Disables right-click/devtools
├── homepage.mp3        # Background music
└── marian.mp3          # Alternate background music
```

## Running the Project

The site is served using Python's built-in HTTP server:

```
python3 -m http.server 5000 --bind 0.0.0.0
```

Workflow: "Start application" on port 5000.

## Deployment

Configured as a static site deployment with publicDir set to the project root.
