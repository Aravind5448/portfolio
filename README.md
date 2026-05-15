# Aravind D — Portfolio

3D interactive portfolio built with Three.js, featuring a galaxy particle system, bloom effects, universe travel transitions, and glass-morphism UI. Hosted on Netlify.

**Live:** [aravind5448.netlify.app](https://aravind5448.netlify.app)

## Tech Stack

- **Three.js r128** — 3D rendering, particle systems, bloom post-processing
- **Vanilla JS** — No frameworks. Page-based SPA with smooth transitions.
- **CSS** — Glass-morphism panels, dark/light theme, custom cursor
- HTML5 semantic structure with IntersectionObserver scroll reveals

## Features

- Interactive galaxy with 12,000 particles — mouse-controlled spin
- White hole core with emission rings and debris field
- Click explosions with ripple rings, particle bursts, and wave effects
- Universe travel transition on page navigation (camera zooms, particles streak)
- Glass-morphism content panels with backdrop blur
- Dark/light theme toggle with localStorage persistence
- Typerwriter hero animation
- Responsive (adapts to viewport)

## Sections

1. Landing — animated intro with typewriter
2. About — bio + stats (hackathons, certs, CTF rank)
3. Skills — ML, Python, MLOps, Data Science, LLMs, SQL, CTF, Java
4. Projects — Phishing Classifier, Salary Predictor, NIDS, Auto MPG, Vehicle Rental
5. Certifications — 8 credentials from AWS, Meta, Cisco, Infosys
6. Contact — email, LinkedIn, GitHub

## Local Dev

No build step — just serve the folder:

```bash
# Python
python -m http.server 8000

# Or VS Code Live Server extension
```

## Deploy

Auto-deploys from GitHub to Netlify on push to `main`.
