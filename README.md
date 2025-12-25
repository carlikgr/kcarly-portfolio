# Portfolio for Minimalist and Creative Graphic Designers

> by carlikgr (artist name: KCarly)

🌐 **Live Demo:** [https://carlikgr.github.io/kcarly-portfolio/](https://carlikgr.github.io/kcarly-portfolio/)

---

# Preview

![Portfolio preview](https://ik.imagekit.io/carlikgr/myportfolio/showcase.gif)

---

## Project Goals

- Design and develop a professional UX/UI portfolio
- Apply responsive and mobile-first principles
- Implement a fluid typographic system using `clamp()`
- Ensure accessibility following WCAG 2.1 AA guidelines
- Use animations only when they add meaning or clarity
- Optimize performance and image loading

---

## Technologies

- **HTML5** — Semantic markup
- **CSS3** — Custom Properties, fluid typography with `clamp()`, Flexbox
- **Bootstrap 5** — Grid system, responsive utilities, components
- **JavaScript (Vanilla)** — Interaction logic
- **GSAP + ScrollTrigger** — Scroll-based animations
- **ImageKit** — Image optimization and delivery
- **Git & GitHub Pages** — Version control and deployment
---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/KCarly/portfolio.git
```

2. Open index.html in your browser

---

## Folder structure

```bash
├── index.html
├── 404.html
├── assets/
│ ├── css/
│ │ ├── index.css      # CSS barrel file (centralizes imports)
│ │ ├── base.css       # Reset, root variables, typography, base styles
│ │ └── otros.css      # Components, sections, animations, responsive rules
│ ├── js/
│ │ └── main.js        # GSAP animations and interactions
│ └── images/
├── docs/
│ ├── plan1.md                 # Sprint 1 – Base setup & deployment
│ ├── plan2.md                 # Sprint 2 – Visual design & UI implementation
│ ├── plan3.md                 # Sprint 3 – Animations & motion strategy
│ ├── project-brief.md         # Initial project definition
│ ├── project-inspiration.md   # Visual and conceptual references
│ └── project.yaml             # Project configuration and metadata
├── README.md
├── LICENSE
└── .gitignore
```

---

## Accessibility

Accessibility has been considered throughout the project:

- Semantic HTML structure
- Proper heading hierarchy
- Sufficient color contrast
- Fluid and scalable typography
- Decorative elements marked with aria-hidden
- Respect for prefers-reduced-motion
- Keyboard-friendly navigation

---

## Performance & Images

Images are served via ImageKit to improve performance:

- WebP format
- Responsive resizing via URL parameters
- Compression and quality control
- Reduced payload for mobile devices

---

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).  
© 2025 KCarly

---

## AI Usage Policy

This project utilized AI assistance (ChatGPT) for:

- Sprint planning and documentation
- Folder and file structure
- Visual design strategy discussion
- Accessibility considerations
- Review of code structure and best practices

All AI-generated suggestions were critically reviewed, adapted, and implemented manually by the author.
Final design decisions and code implementation are fully human-driven.

---

## Credits

- **[Bootstrap 5](https://getbootstrap.com/)** — Front-end framework
- **[GSAP](https://greensock.com/gsap/)** — Animation library
- **[ImageKit](https://imagekit.io/)** — Image optimization and CDN
