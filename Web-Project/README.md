# Web Development Internship — Week 1 Assignments

Three frontend exercises completed for the WeIntern Pvt Ltd Week 1 assignment. Each project focuses on a different part of HTML and CSS. I kept the JavaScript small so the layout code is easy to follow.

## Projects

| Task | Location | Description |
| --- | --- | --- |
| 1. Portfolio Website | `portfolio-website/` | Four-page developer portfolio with theme toggle, mobile navigation, project filters, and contact form |
| 2. Business Landing Page | `business-landing-page/` | Northside Digital fictional agency landing page with six services and validated enquiry form |
| 3. CSS Challenge | `css-challenge/` | Responsive three-card Flexbox layout, six-tile Grid, and three animation examples |

## Tech stack

- HTML5 semantic structure
- CSS3, Flexbox, CSS Grid, media queries, transitions, keyframes
- Vanilla JavaScript for progressive enhancement
- Google Fonts (requires internet; system fallbacks included)

## Run locally

1. Download and extract this repository.
2. Open `portfolio-website/index.html`, `business-landing-page/index.html`, or `css-challenge/index.html` in a modern browser.
3. For local cross-project links, keep the three project folders alongside one another.
4. Optional: use VS Code Live Server or run `python -m http.server 8000` in the repository root, then visit `http://localhost:8000/` followed by the project folder.

## Features and implementation

**Portfolio:** four separate semantic pages, responsive mobile menu, light/dark theme saved in localStorage, three sample projects, working project category filters, email-compose contact form, visible focus states, alt/ARIA descriptions.

**Business:** sticky navigation, responsive hero, six service cards, about/trust section, contact form with native HTML validation, email-compose action, mobile menu, and clear CTAs.

**CSS:** Flexbox `justify-content`, `align-items`, `gap`, flexible widths, three-to-one responsive layout; Grid `repeat()` and `minmax()` with six tiles and three/two/one-column breakpoints; transitions and keyframe animations with `prefers-reduced-motion` support.

## Important demo limitations

The portfolio's **Isha Pichholiya** identity and Northside Digital are fictional sample content. Replace all sample names, emails (`contact@example.com`), profile URLs, and claims before presenting as your own. Contact forms **do not send messages to a server**: they open a prefilled email in the visitor's mail application. To accept submissions directly, connect a backend or a hosted form service. The dashboard illustration is a design example, not a real business report.

## Deployment

**GitHub Pages:** create a public repository, upload these folders, and enable Pages under Settings → Pages → Deploy from branch (`main`, root). Open the projects at:

- `https://YOUR-USERNAME.github.io/YOUR-REPO/portfolio-website/`
- `https://YOUR-USERNAME.github.io/YOUR-REPO/business-landing-page/`
- `https://YOUR-USERNAME.github.io/YOUR-REPO/css-challenge/`

Alternatively, deploy each project folder separately using Netlify or Vercel.

## Screenshot checklist

Capture full-resolution screenshots and save them in `screenshots/`:

- `portfolio-home-desktop.png`
- `portfolio-home-mobile.png`
- `portfolio-projects.png`
- `portfolio-contact.png`
- `landing-desktop.png`
- `landing-hero-mobile.png`
- `landing-services.png`
- `landing-contact-form.png`
- `flex-desktop.png`
- `flex-mobile.png`
- `grid-layout.png`
- `animation-demo.png`

Screenshots must be captured from the actual rendered pages. They are not pre-generated in this package.

## QA checklist

- [ ] Replace demo personal details with actual author information
- [ ] Test all links, navigation, and form validation
- [ ] Test at 375px, 768px, 1024px, and 1440px widths
- [ ] Capture required desktop/mobile screenshots
- [ ] Verify no browser console errors
- [ ] Push repository to GitHub with meaningful commits
- [ ] Deploy live sites and check links from another device
- [ ] Add actual deployment URLs and screenshots to this README

## Author

**Name:** [Add your name]  
**GitHub:** [Add your GitHub URL]  
**Live demo:** [Add deployment URLs]

## Notes from the build

I started with the page structure and worked on spacing and smaller screen sizes afterward. The portfolio uses four HTML files because the assignment asks for separate pages. The business page is one scrolling page, while the CSS challenge keeps the layout exercises together for easier comparison.

The portfolio project examples are practice work, not paid client projects. Northside Digital is a fictional business used to demonstrate a landing page. The contact forms open an email draft and do not store or transmit form submissions themselves.

## Before submission

- Check the displayed name, email address, GitHub and LinkedIn links. The social links are placeholders until real profile URLs are provided.
- Open every page, test the menu and forms, and check layouts at narrow and wide screen sizes.
- Take the screenshots listed above from the actual running projects.
- Publish the repository and replace deployment placeholders with real URLs.
