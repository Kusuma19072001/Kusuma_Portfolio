# Kusuma Portfolio

Personal portfolio for **Kusuma Satya Sreeja Chalasani** — Data Engineer and AI-focused builder, highlighting education, experience, projects, certifications, and creative work. The site is a single-page layout built with plain **HTML, CSS, and JavaScript**, styled with custom CSS variables for **light and dark** themes, and intended for hosting on **GitHub Pages**.

## Live site

[https://kusuma19072001.github.io/Kusuma_Portfolio/](https://kusuma19072001.github.io/Kusuma_Portfolio/)

## What’s on the site

| Section | Content |
|--------|---------|
| **Hero** | Headline, role tags, photo, links to resume, LinkedIn, and GitHub |
| **About** | Professional summary and focus areas |
| **Education** | UNT — M.S. Data Science |
| **Skills** | Grouped skill cards with cross-links to related projects |
| **Experience** | Work history |
| **Projects** | Featured and standard project cards; some open **detail modals** (e.g. LUMA 2.0) with screenshots and narrative |
| **Certifications** | Badges and certificate imagery |
| **Creative Corner** | Art gallery and Instagram link |
| **Contact** | Email and social links |

**Projects highlighted** include LUMA 2.0 (emotional wellness companion), Interview Prep RAG, Guardian Recruit, AI Data Analyst, DishGenie, Crime Rate Prediction, Emotion-Based Music, Energy Forecasting, and Smart Job Matcher.

## Tech stack

- **Markup & style:** HTML5, `style.css` (layout, responsive behavior, theme tokens)
- **Fonts:** [Google Fonts](https://fonts.google.com/) — Fraunces and Outfit
- **Script:** Vanilla JavaScript for theme persistence (`localStorage`), project modals, Escape-to-close, and scroll reveal (`IntersectionObserver`)
- **Hosting:** GitHub Pages (static assets only; no server-side runtime)

There is no bundler or framework required to view or deploy the site. A `package-lock.json` file is present in the repo from earlier tooling; there is currently no `package.json` or npm scripts in the root.

## Repository layout

```
Kusuma_Portfolio/
├── index.html          # Full page content and inline scripts
├── style.css           # Global and component styles, themes
├── README.md
├── package-lock.json   # Lockfile only (no package.json at repo root)
├── images/
│   ├── Profile.jpeg
│   ├── unt.png
│   ├── Dishgenie1.jpg
│   ├── dishgenie-logo.png
│   ├── ai-analyst-preview.jpg
│   ├── job-matcher-preview.png
│   ├── oracle-certificate.png
│   ├── art/            # Creative Corner images
│   ├── certs/          # Certification thumbnails
│   ├── certificates/   # Additional certificate assets
│   ├── guardian/       # Guardian Recruit project screenshots
│   ├── luma/           # LUMA 2.0 screenshots
│   └── rag/            # Interview Prep RAG imagery
└── resume/
    └── Kusuma_Chalasani.pdf   # Linked from the hero (add or replace as needed)
```

## Local preview

Open `index.html` in a browser, or serve the folder with any static file server, for example:

```bash
# Python 3
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Contact

- [LinkedIn](https://www.linkedin.com/in/kusuma-chalasani/)
- [Instagram — art](https://www.instagram.com/pencilart_love)
