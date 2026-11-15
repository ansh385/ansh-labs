# ANSH LABS

> Independent technology studio exploring original products at the intersection of design and engineering.

**Live website:** https://ansh-labs.vercel.app/  
**GitHub:** https://github.com/ansh385/ansh-labs

---

## About

ANSH LABS turns curious ideas into considered objects and digital experiences. The studio explores hardware, robotics, software and product design with a focus on useful function, precise geometry and thoughtful colour, material and finish (CMF).

The website is a responsive studio portfolio built to present selected explorations, the studio's design principles and an interactive 3D product study.

## Featured Explorations

| Project | Area | Description |
| --- | --- | --- |
| **SPIKER 1 DUO** | Hardware / Audio | Compact wired stereo speaker system concept focused on balanced sound, intuitive controls and a precise desktop footprint. |
| **AL-BOT 1** | Robotics | Desktop companion concept exploring expressive movement, useful presence and an approachable interface. |
| **TOOLS FOR THINKERS** | Software | Focused digital experiences and utilities designed to remove friction from everyday work. |
| **THE MATERIAL STUDY** | Research / CMF | Exploration of finishes, textures, tolerances and product details. |

These are presented as explorations and concepts; the website does not claim that every project is a finished or commercially available product.

## Tech Stack

- **Structure:** HTML5
- **Styling:** CSS3, responsive layouts, CSS animations
- **Interaction:** Vanilla JavaScript (ES modules)
- **3D:** Three.js 0.170.0
- **Typography:** Manrope and DM Mono via Google Fonts
- **3D delivery:** Three.js via jsDelivr CDN
- **Hosting:** Vercel

No frontend framework or build step is required for the current static site.

## Website Features

- Responsive layout for mobile, tablet and desktop widths
- Custom ANSH LABS geometric A mark and matching favicon
- Graphite, muted green and CMF orange visual identity
- Interactive Three.js product viewer
  - Switch between speaker and robot studies
  - Drag to rotate the model
  - Scroll to zoom
- Project exploration cards and studio philosophy sections
- Mobile navigation
- Scroll-reveal effects and reduced-motion support
- Direct links to the studio's GitHub profile

## Run Locally

The site is a static page. You can open `index.html` directly, or serve the folder locally.

### Option 1 — Python

```bash
python -m http.server 8000
```

Open http://localhost:8000.

### Option 2 — Node.js

If you have a local static server available, run it from the project root. For example:

```bash
npx serve .
```

The interactive 3D viewer loads Three.js from jsDelivr, and the page loads web fonts and project imagery from external services. An internet connection is required for those remote assets.

## Project Structure

```text
ansh-labs/
├── index.html   # Complete website: markup, styles and JavaScript
└── README.md    # Project documentation
```

## Deployment

The production site is hosted on Vercel and connected to this GitHub repository.

- **Production URL:** https://ansh-labs.vercel.app/
- **Repository:** https://github.com/ansh385/ansh-labs
- **Production branch:** `main`

Pushing a commit to `main` triggers a deployment through the repository's Vercel integration.

## Design Direction

- **Form:** precise geometry and clear proportions
- **Material:** honest, tactile surfaces and durable finishes
- **Function:** every visible detail should have a purpose
- **Identity:** restrained graphite surfaces with CMF orange accents

## Contact

- **GitHub:** https://github.com/ansh385
- **Studio:** ANSH LABS · India

---

© 2026 ANSH LABS. Independent by design.
