# Pranay Gupta — Developer & AI Engineer

> A personal portfolio showcasing software development, AI engineering, projects, and a passion for building technology.

Welcome to my personal portfolio repository. This project is a modern, responsive website designed to present my work, technical interests, projects, and developer journey through a clean, minimal, and interactive experience.

The entire website is built inside **one standalone HTML file**, with HTML, CSS, and JavaScript integrated directly into `index.html`. There is no requirement for a separate frontend framework or a multi-file application structure.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Design Philosophy](#design-philosophy)
- [Website Sections](#website-sections)
- [Interactive Functionality](#interactive-functionality)
- [Technology Stack](#technology-stack)
- [Single-File Architecture](#single-file-architecture)
- [Getting Started](#getting-started)
- [Customization](#customization)
- [Responsive Design](#responsive-design)
- [Accessibility](#accessibility)
- [Performance Considerations](#performance-considerations)
- [Deployment](#deployment)
- [Browser Compatibility](#browser-compatibility)
- [Future Improvements](#future-improvements)
- [Author](#author)
- [License](#license)

## Overview

This portfolio is a personal website for presenting my identity as a developer and AI engineer. It combines a restrained visual design with interactive elements, structured content, and responsive layouts.

The interface uses a centered content layout, subtle borders, carefully spaced sections, and a blue accent color. Its design adapts to light and dark themes while maintaining readability and visual consistency.

The project is intentionally lightweight in architecture: the main HTML document contains the page structure, styling, and interactive JavaScript, making it easy to understand, edit, and deploy.

### Project Goals

- Establish a professional online presence.
- Showcase software projects and technical interests.
- Present development skills and technologies.
- Make it easy for visitors to explore projects and contact me.
- Provide a responsive experience across different screen sizes.
- Keep the source code accessible through a single HTML file.
- Avoid unnecessary frameworks and build-tool complexity.

## Features

### Modern Interface

- Minimal, developer-focused visual design.
- Centered content container with consistent spacing.
- Subtle background patterns and borders.
- Blue accent colors and carefully defined typography.
- Interactive hover states and visual transitions.
- Card-based layouts for presenting projects.
- Fixed navigation for convenient access to page sections.

### Responsive Layout

The website adapts to mobile phones, tablets, laptops, and desktop displays.

- Responsive typography and spacing.
- Flexible navigation and content layouts.
- Single-column project layout on smaller screens.
- Two-column project layout on wider screens.
- Adaptive profile image sizing.
- Mobile-friendly contact buttons and footer sections.

### Theme Support

The website supports light and dark appearances.

- Light theme with a white background and dark text.
- Dark theme with near-black backgrounds and light text.
- Theme-aware borders, muted surfaces, and text colors.
- CSS custom properties for centralized color management.
- Support for the operating system's preferred color scheme.
- A theme toggle button in the navigation bar.

### Interactive Profile

The profile image includes a flip animation.

- Click the profile image to flip between its front and back.
- Display the profile photograph on the front.
- Display a stylized initial on the reverse side.
- Use a three-dimensional rotation transition.
- Support keyboard activation through Enter and Space.

### Project Showcase

The projects section provides a visual way to present selected work.

- Responsive project cards.
- Preview-style illustrations created with CSS.
- Project titles and short descriptions.
- Technology or category labels where configured.
- Hover transitions and subtle visual feedback.
- Space to connect projects to their respective destinations.

### Skills and Technologies

A dedicated technology section presents development tools and technologies through compact labels.

The component styling supports a flexible collection of technology chips, making it easy to add, remove, or reorganize the technologies displayed.

### Contact and Social Links

The website includes social profile links and a contact-focused call to action.

- GitHub profile link.
- LinkedIn profile link.
- Dedicated contact section.
- Prominent action buttons.
- Footer navigation and social destinations.

### Accessibility Features

- Semantic HTML elements.
- Accessible labels for icon-only controls.
- Keyboard-operable profile interaction.
- Visible keyboard focus indicators.
- Reduced-motion preference support.
- Responsive viewport configuration.

## Design Philosophy

The visual direction prioritizes clarity, content, and usability rather than excessive decoration.

### Typography

The website uses three typefaces loaded from Google Fonts:

- **Space Grotesk:** Headings and selected display elements.
- **Inter:** Main interface text and body content.
- **JetBrains Mono:** Small technical labels and monospaced details.

System font fallbacks are provided for cases where external fonts cannot be loaded.

### Color System

The interface uses CSS custom properties to keep the design consistent.

| Variable | Purpose |
|---|---|
| `--background` | Main content background |
| `--canvas` | Outer page and secondary surfaces |
| `--fg` | Primary text color |
| `--muted` | Muted component backgrounds |
| `--mf` | Secondary text color |
| `--border` | Borders and dividers |
| `--brand` | Accent color |
| `--hatch` | Subtle patterned backgrounds |

The color system changes according to the active theme.

### Layout

The main content uses a centered container with a maximum width of approximately 768 pixels. Responsive padding and section spacing keep the interface readable without stretching the content across excessively wide screens.

## Website Sections

### 1. Home

The hero section introduces Pranay Gupta and identifies the portfolio as a developer and AI engineering profile.

It includes the interactive profile image and introductory identity elements.

### 2. About

The About section provides space for a personal introduction, development interests, technical background, and current direction.

The content can be updated to reflect current goals, experience, and interests.

### 3. Projects

The Projects section presents selected work using responsive cards and CSS-based preview illustrations.

Each card can be customized with a project name, description, technology labels, and a link to a live deployment or source repository.

### 4. Stack

The Stack section displays technologies and tools using compact labels.

It is designed to make the technical overview easy to scan without requiring visitors to read lengthy descriptions.

### 5. Now

The Now section provides a place to communicate current priorities, active projects, areas of learning, or recent development work.

Keeping this section current can help visitors understand what I am working on today.

### 6. Contact

The Contact section provides a prominent closing call to action for people interested in collaboration, software development, or technology discussions.

### 7. Footer

The footer contains profile information, navigation links, and supporting details. It provides a consistent ending to the page and makes important destinations accessible again.

## Interactive Functionality

The website includes several client-side interactions implemented using JavaScript and CSS.

| Component | Behavior |
|---|---|
| Navigation | Links to sections within the page |
| Theme toggle | Switches the website's theme |
| Profile image | Flips using a 3D rotation |
| Project cards | Provide hover-based visual feedback |
| Buttons and links | Offer interactive hover and focus states |
| Responsive layouts | Adapt based on viewport width |

The navigation uses in-page anchors, allowing visitors to move directly to the relevant section without loading a separate page.

The profile flip interaction is implemented directly in the HTML using a CSS class toggle and keyboard event handling.

## Technology Stack

The project uses standard web technologies rather than requiring a framework-specific runtime.

### HTML5

Used for the document structure, semantic sections, navigation, links, buttons, and content hierarchy.

### CSS3

Used for the visual design and responsive behavior, including:

- CSS custom properties.
- Flexbox and CSS Grid.
- Media queries.
- Gradients and background patterns.
- Hover and focus states.
- Transitions and 3D transforms.
- Dark theme styling.
- Reduced-motion handling.

### JavaScript

Used for client-side interaction, including the theme control and profile animation.

### Google Fonts

The website references Google Fonts for Space Grotesk, Inter, and JetBrains Mono. An internet connection may be required to retrieve these fonts.

## Single-File Architecture

The central design decision is keeping the website in one HTML file.

```text
portfolio-v2/
├── index.html
└── README.md
```

`index.html` contains:

- HTML document structure.
- Metadata and page title.
- External font references.
- CSS inside the `<style>` element.
- Page content and navigation.
- Inline SVG icons.
- Embedded profile image data.
- JavaScript interaction handlers.

`README.md` documents the project and is not required for the website to render.

The repository may contain additional files for documentation or deployment configuration, but the website itself is implemented in the standalone HTML document.

### Advantages

- Simple setup with no dependency installation.
- No compilation or bundling step required.
- Easy to inspect and customize.
- Straightforward static hosting.
- Convenient portability between environments.
- No framework runtime required.

### Trade-offs

- A large HTML file can become difficult to maintain as the website grows.
- Inline CSS and JavaScript are less modular than separate files.
- Reusing components across multiple pages is less convenient.
- External font requests still depend on a third-party service.
- A single HTML file does not automatically guarantee better performance or security; these depend on implementation and deployment.

## Getting Started

### Prerequisites

You need only:

- A modern web browser.
- A local copy of the repository.
- A text editor if you want to customize the website.

Node.js, npm, and a build process are not required to open the standalone HTML page.

### Clone the Repository

```bash
git clone https://github.com/Pranay6973/portfolio-v2.git
```

Move into the project directory:

```bash
cd portfolio-v2
```

### Run the Website

Open `index.html` directly in your browser.

Alternatively, if you have Python installed, start a local static server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

The local server is optional. It is useful for testing the website in an HTTP environment before deployment.

## Customization

### Update Personal Information

Open `index.html` in your preferred code editor.

Search for the existing profile content and update the name, introduction, professional description, and other personal details.

The browser tab title and search description can be updated through the document metadata.

### Update Social Links

The current source includes these profile destinations:

- GitHub: `https://github.com/Pranay6973`
- LinkedIn: `https://linkedin.com/in/pranay-gupta-56b607415`

Replace these URLs if your profile destinations change.

### Update Projects

Find the project card markup and customize each card's title, description, category, and destination.

Before publishing, ensure each project link points to the correct live website or repository. The visual project preview should not be mistaken for a live embedded application.

### Update Technologies

Modify the technology labels in the Stack section to reflect the tools you actually use.

Avoid listing technologies solely for appearance; the section is most useful when it accurately represents your experience.

### Customize Colors

Edit the CSS custom properties inside the `:root` and theme selectors.

For example, changing `--brand` updates the primary accent color in components that reference that variable.

### Customize Typography

The font imports appear near the beginning of the HTML document. You can change the requested Google Fonts and their weights there, along with the relevant CSS font-family declarations.

If you want the page to work entirely without external font requests, replace those declarations with suitable system font stacks and remove the Google Fonts imports.

### Change the Profile Image

The current profile image is embedded as a Base64-encoded JPEG in the HTML source. This keeps the image within the standalone document.

To replace it, update the image's `src` attribute with either:

- A new Base64-encoded image data URI.
- A hosted image URL.
- A relative image path, if you no longer require the page to be fully self-contained.

Using a separate image file simplifies image replacement, while embedding it preserves the single-file asset approach.

## Responsive Design

The stylesheet uses media queries to adjust layout behavior at different viewport widths.

- Small screens prioritize compact spacing and readable content.
- Wider screens provide larger profile elements and headings.
- Project cards switch from one column to two columns at larger widths.
- Footer layout adapts to available space.
- The navigation remains fixed at the top for convenient section access.
- Safe-area padding is considered for devices that expose display cutouts.

The website also uses `scroll-behavior: smooth` and scroll padding to improve navigation between anchored sections.

## Accessibility

Accessibility considerations included in the source are:

- A declared document language.
- Viewport metadata for mobile devices.
- Semantic header, navigation, main, section, and footer elements.
- Accessible names for icon-only GitHub, LinkedIn, and theme controls.
- A visible `:focus-visible` indicator.
- Keyboard support for the profile flip interaction.
- A reduced-motion media query to limit animations for users who request reduced motion.

These features provide a useful foundation, but they do not by themselves establish full accessibility compliance. Contrast, keyboard behavior, screen-reader output, and all interactive states should be tested before claiming conformance to an accessibility standard.

## Performance Considerations

The single-file design removes the need to download separate local CSS, JavaScript, and profile image files when those assets are embedded.

Additional considerations include:

- The embedded profile image increases the HTML document's size.
- External fonts introduce network requests to Google Fonts.
- Complex background patterns and visual effects may add rendering overhead.
- The fixed header uses backdrop filtering, which should be tested on lower-powered devices.
- Transitions and hover effects should remain subtle and usable.
- Static hosting and appropriate caching headers can improve delivery performance.

Actual performance depends on the file size, browser, network conditions, and deployment configuration. Measure loading behavior with browser developer tools or Lighthouse rather than assuming the site is optimized based on its architecture alone.

## Deployment

Because the website is a static HTML page, it can be hosted on a static web hosting service.

### Vercel

1. Push the repository to GitHub.
2. Import the repository into Vercel.
3. Configure the project for static HTML hosting.
4. Ensure `index.html` is available at the configured output root.
5. Deploy and verify the resulting URL.

For a plain HTML website, do not configure a Next.js build unless the project actually uses Next.js.

### GitHub Pages

1. Open the repository settings on GitHub.
2. Navigate to the Pages configuration.
3. Select the deployment source.
4. Configure the branch and root directory containing `index.html`.
5. Save the configuration and wait for deployment.

### Other Static Hosts

The website can also be deployed to any compatible static hosting service that can serve an HTML document.

After deployment, verify the navigation links, theme toggle, profile animation, social links, mobile layout, and browser console.

## Browser Compatibility

The website uses modern CSS features, including custom properties, CSS Grid, Flexbox, `color-mix()`, backdrop filters, and 3D transforms.

It is intended for modern browsers. Some visual effects may differ in older browsers or environments with limited CSS support.

Fallbacks are provided for some font and motion behaviors, but older-browser compatibility should be tested explicitly if it is a requirement.

## Security and Privacy

This project is a static portfolio website.

The provided source does not establish a backend, database, authentication system, or server-side contact form. A contact section with links or buttons should not be described as a working form submission system unless a real submission mechanism is implemented.

For production deployment:

- Use HTTPS through the hosting provider.
- Verify external links before publishing.
- Avoid embedding API keys, private tokens, or other secrets in client-side HTML.
- Review third-party font and asset requests.
- Configure appropriate security headers through the hosting platform where possible.
- Use a Content Security Policy compatible with the page's inline styles, scripts, and external resources.

A single-file architecture does not eliminate browser-side security risks. Inline scripts, external dependencies, and deployment configuration still require appropriate review.

## Future Improvements

Potential improvements include:

- Add verified live links for each project.
- Improve project previews with real screenshots.
- Refine the theme toggle's state persistence.
- Add richer project descriptions and outcomes.
- Improve metadata for search and social sharing.
- Test keyboard navigation and screen-reader behavior.
- Audit contrast and responsive behavior.
- Measure page performance with Lighthouse.
- Add a real contact mechanism if needed.
- Document the license and contribution policy explicitly.

These are possible future enhancements, not claims that they are already implemented.

## Author

**Pranay Gupta**

Developer & AI Engineer

- GitHub: [Pranay6973](https://github.com/Pranay6973)
- LinkedIn: [Pranay Gupta](https://linkedin.com/in/pranay-gupta-56b607415)

## License

No specific open-source license is established by the supplied HTML source. Unless a license is added to the repository, do not assume that the project is licensed for unrestricted redistribution or reuse.

## Acknowledgments

- The open web platform: HTML, CSS, and JavaScript.
- Google Fonts for the referenced typography.
- The developer community and open-source ecosystem for inspiration and learning.

---

**Built by Pranay Gupta — a personal space for showcasing projects, exploring technology, and documenting a journey in software development and AI engineering.**
