# Copilot Instructions for AI Coding Agents

## Project Overview
This is a static web project for a headphone-related landing page or product showcase. The project consists of:
- `index.html`: Main HTML file, contains the page structure and content.
- `style.css`: All styling for the site. Custom fonts and images are referenced here.
- `img/`: Contains all image assets used in the site (logos, backgrounds, product images, social icons).
- `attribution.txt`: Attribution for assets or fonts.
- `mockup.png`, `Used fonts.jpeg`: Design reference and font usage documentation.

## Key Patterns & Conventions
- All assets are referenced with relative paths (e.g., `img/headphone.png`).
- The site is designed as a single static page. There is no JavaScript or build system.
- Custom fonts are likely referenced in `style.css` (see `Used fonts.jpeg` for details).
- Layout and design are based on the provided `mockup.png`.
- All styling is handled in `style.css`. Avoid inline styles in `index.html`.
- Use semantic HTML5 elements where possible.

## Developer Workflows
- **Preview:** Open `index.html` directly in a browser to view the site.
- **Edit:** Update `index.html` for content/structure, `style.css` for design/layout.
- **Assets:** Add new images to `img/` and reference them in HTML/CSS as needed.
- **Fonts:** Reference custom fonts in `style.css` and document them in `Used fonts.jpeg`.
- **Attribution:** Update `attribution.txt` if you add new third-party assets.

## Project-Specific Guidance
- Match the design in `mockup.png` as closely as possible.
- Maintain consistent class naming and CSS organization.
- Do not introduce frameworks, build tools, or JavaScript unless explicitly requested.
- Keep the project portable—no absolute paths or environment-specific settings.

## Example Asset Reference
```html
<img src="img/headphone.png" alt="Headphone" />
```

## Key Files
- `index.html`: Main entry point
- `style.css`: All styles
- `img/`: All images
- `mockup.png`: Design reference
- `Used fonts.jpeg`: Font documentation
- `attribution.txt`: Asset attributions

---
For any new features or changes, follow the established static site structure and reference the mockup for design consistency.
