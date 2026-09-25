# Engr. Mathias Akuma Sarverun — Professional Portfolio

A frontend-only professional portfolio for **Engr. Mathias Akuma Sarverun**, presenting a development-focused practice across agricultural engineering, public policy, rural development and infrastructure.

## What was retained and improved

The site preserves the original prototype's verified professional profile, qualifications, public-sector experience, community initiatives, contact email and core portfolio figures. It redesigns the presentation into a more editorial, accessible single-page experience with:

- Clear narrative flow: identity → expertise → selected work → experience → credentials → impact → resources → contact.
- Responsive desktop and mobile navigation, including keyboard-accessible controls.
- Dedicated project case-study dialogs that distinguish facilitation, concepts and documented details from outcomes.
- Downloadable CV summary at `assets/mathias-sarverun-cv.txt`.
- Semantic sections, focus states, skip link, reduced-motion support and lightweight scroll reveals.
- SEO and Open Graph metadata in `index.html`.

## Technology

This project deliberately retains the original lightweight architecture:

- Plain HTML
- CSS with responsive design tokens and media queries
- Lightweight, dependency-free JavaScript

There is no build step, server, CMS or backend requirement.

## Run locally

Open `index.html` directly in a browser, or serve the repository with any static-file server. For example:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Project structure

```text
.
├── index.html                         # Single-page portfolio UI, styles and interactions
├── assets/
│   └── mathias-sarverun-cv.txt        # Downloadable verified portfolio summary
├── README.md                          # Project overview and local-run guidance
└── SRD.md                             # Original software requirements document
```

## Content maintenance

Portfolio text is intentionally limited to details present in the original prototype and SRD. Before adding project outcomes, publications, photography, social profiles or a full CV, verify the source material and update the corresponding content in `index.html` and `assets/mathias-sarverun-cv.txt`.

## Remaining limitations

- No approved professional portrait, project photography, social profile URL, or full CV PDF was included in the starting repository. The site therefore uses a typographic identity treatment and a downloadable text summary rather than inventing assets.
- The contact action uses an email link only, keeping this release frontend-only.
- The canonical URL is an intentional `https://example.com/` placeholder and should be replaced at deployment.
