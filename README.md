# POE Part 1 - Hope for Tomorrow
## Student: Khanya Dyan (ST10483513)

### Project Overview
This project is Part 1 of the Portfolio of Evidence. It includes:
- Project Proposal (NPO: Hope for Tomorrow)
- Website structure and initial content
- Content bundle (research, images)
- GitHub documentation (README + CHANGELOG)

### Harvard References
Department of Social Development. (2023). *National Development Plan for Youth Empowerment*. Pretoria: Government of South Africa.

Statistics South Africa. (2022). *General Household Survey 2022*. Pretoria: StatsSA.

UNICEF South Africa. (2023). *Children’s Rights and Development in South Africa*. Available at: https://www.unicef.org/southafrica (Accessed 20 Aug 2025).


## Part 2 — CSS Styling & Responsive Design (WED602POE)

This update (Part 2) implements the styling and responsive design requirements:
- Added `website/style.css` (external stylesheet).
- Established base styles and CSS reset, using relative units (rem) and percentage widths.
- Applied typography scales (h1, h2, p) and accessible focus styles.
- Implemented layout using CSS Grid for desktop and single-column flow for smaller screens.
- Added responsive image rules (`max-width:100%`, `height:auto`), and instructions to use `srcset` for production images.
- Added `.card` styles, buttons, and navigation enhancements.
- Created sample screenshots (in `website/screenshots/`) for Desktop, Tablet, Mobile to include in README.
- Created `Changes.md` with a log of edits for Part 2.

### How to test locally
1. Open `website/index.html` in your browser (double-click or use a simple HTTP server).
2. Resize the browser window to see responsive breakpoints (desktop/tablet/mobile).
3. Replace placeholder screenshots in the README with real captures if desired.

### Screenshot evidence (sample placeholders included)
- website/screenshots/desktop-sample.png
- website/screenshots/tablet-sample.png
- website/screenshots/mobile-sample.png

- ## Part 3 – Functionality & SEO Enhancements

**Project goal:** Hope for Tomorrow — empower underprivileged children with education, nutrition and mentorship.

### What I added for Part 3
- JavaScript features:
  - Accordion interactive component for FAQs/services.
  - Lightbox gallery for program images.
  - Search/filter for programs and services.
  - Dynamic program listing (programs injected with JS).
- Forms:
  - `enquiry.html` — enquiry form with HTML5 and JS validation, AJAX simulation.
  - `contact.html` — contact form accepts general queries, complaints, partnership requests, feedback.
- SEO:
  - Appropriate `<title>` and `<meta name="description">` for pages.
  - `robots.txt` and `sitemap.xml` added.
  - `alt` attributes added to images and accessible markup.
- Docs:
  - `CHANGELOG.md` created with Part 3 entries.
  - Code organized in `/website/scripts/main.js` and `style.css`.

### Files added/edited
- `website/scripts/main.js` (new)
- `enquiry.html` (updated)
- `contact.html` (updated)
- `index.html` (new)
- `style.css` (add Part 3 styles)
- `robots.txt` (new)
- `sitemap.xml` (new)
- `CHANGELOG.md` (new)

---

## How to test locally
1. Clone the repo:
   ```bash
   git clone https://github.com/khanyadyan/POE---part1--Khanya-Dyan.git
   cd POE---part1--Khanya-Dyan
   ```
2. Add files above to the repo folders (or merge with your existing pages).
3. Open `index.html` in a browser or use a simple live server:
   ```bash
   python3 -m http.server 8000
   # then visit http://localhost:8000
   ```


