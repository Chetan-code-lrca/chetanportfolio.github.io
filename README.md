# Chetan Inaganti — Portfolio

A personal portfolio website built with HTML, CSS, and JavaScript.

The site presents my background, technical skills, education, certifications, and contact links in a responsive single-page layout.

## Run locally

Clone the repository:

```bash
git clone https://github.com/Chetan-code-lrca/chetanportfolio.github.io.git
cd chetanportfolio.github.io
```

Open `index.html` in a browser.

No build step or package installation is required. The site loads external fonts and icons through CDN links.

## Project structure

```text
.
├── index.html
├── style.css
├── script.js
├── .github/
│   └── workflows/
│       └── deploy.yml
└── README.md
```

## What is included

- Responsive layout for desktop, tablet, and mobile screens
- Hero, About, Experience, Skills, Certifications, and Contact sections
- Smooth scrolling and navigation highlighting
- Scroll animations
- Scroll progress indicator
- Back-to-top control
- External professional profile links

## Deployment

This is a static website and can be served by GitHub Pages or any static hosting service.

The repository includes a GitHub Actions deployment workflow. It publishes the repository root as the Pages artifact when changes are pushed to `main`, and it can also be started manually with `workflow_dispatch`. The deployment job requires GitHub Pages to be enabled for the repository and the `github-pages` environment to be available.

## Technologies

- HTML5
- CSS3
- JavaScript (ES6+)
- Google Fonts
- Font Awesome

## Notes

The portfolio is intentionally a small static site, so there is no framework, backend, database, or build pipeline in the repository.

The public website contains the profile information intended for the portfolio. The repository does not need additional personal information beyond what is already displayed on the site.

## Contact

Professional profile links are available from the website itself.
