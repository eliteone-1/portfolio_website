# Emmanuel Audu Jeremiah — Personal Portfolio Website

A professional, high-performance personal portfolio website built for **Emmanuel Audu Jeremiah**, a final year Computer Engineering student with an AI specialisation at Ahmadu Bello University (ABU Zaria), graduating in 2026.

This project strictly adheres to a **No-JavaScript** constraint, utilizing only standard **HTML5**, **CSS3**, and **JSON** to deliver smooth interactivity, responsive layouts, and structured search engine metadata.

---

## Live Demo & Deployment

- **GitHub Repository**: [github.com/eliteone-1/portfolio_website](https://github.com/eliteone-1/portfolio_website.git)
- **Live Vercel Deployment**: *Deployed via Vercel*

---

## Technical Stack & Architecture

- **Core Technologies**: HTML5, CSS3, JSON
- **Frameworks / Libraries**: None (0% JavaScript, 0% CMS, 0% External JS Frameworks)
- **Interactivity**: Pure CSS3 (`:hover`, `:focus`, `:target`, `:checked` checkbox hack)
- **Layout System**: Mobile-First CSS Flexbox & CSS Grid
- **Structured Data**: Schema.org JSON-LD (`Person`, `ItemList`, `ContactPage`)
- **Typography**: Inter (Google Fonts)

---

## Pages Sitemap

1. **Home (`index.html`)**: Hero section, headline keyframe animation, track record metrics, and `Person` JSON-LD schema.
2. **About Me (`about.html`)**: First-person story covering background in Nigeria, engineering journey at ABU Zaria, and technical/operational identity.
3. **Educational Background (`education.html`)**: B.Eng Computer Engineering details, coursework grid, and capstone **Smart AI Based Energy Meter** thesis showcase.
4. **Technical Skills (`skills.html`)**: 5-category CSS Grid matrix covering Programming Languages, AI & ML, Operations Tools, Media Tools, and Utilities.
5. **Projects (`projects.html`)**: Interactive project cards modeled from `data/data.json` with hover detail overlays and `ItemList` JSON-LD schema.
6. **Hobbies & Interests (`hobbies.html`)**: 6 personal interests (Technology & AI, Creator Economy, Fitness, Reading, Football, Building Systems).
7. **Curriculum Vitae (`cv.html`)**: Experience summary (3.4M sub media brand production coordinator), education, skills, and `@media print` print-friendly styling.
8. **Contact Me (`contact.html`)**: Contact details in Abuja Nigeria, pure CSS mailto contact form, and `ContactPage` JSON-LD schema.

---

## Directory Structure

```
.
├── index.html            # Page 1 — Home
├── about.html            # Page 2 — About Me
├── education.html        # Page 3 — Educational Background
├── skills.html           # Page 4 — Technical Skills
├── projects.html         # Page 5 — Projects
├── hobbies.html          # Page 6 — Hobbies & Interests
├── cv.html               # Page 7 — Curriculum Vitae
├── contact.html          # Page 8 — Contact Me
├── assets/
│   ├── css/
│   │   └── style.css     # Design system, mobile nav, keyframe animations, print media query
│   └── images/           # Profile headshot and project thumbnails
├── data/
│   └── data.json         # Structured project models and skills array
└── README.md             # Project documentation
```

---

## Local Development Setup

To run this project locally, simply open any `.html` file in your browser or run a simple local web server:

```bash
# Clone the repository
git clone https://github.com/eliteone-1/portfolio_website.git
cd portfolio_website

# Start local server (Python 3)
python -m http.server 8080
```

Then visit `http://localhost:8080` in your web browser.

---

## License & Copyright

© 2026 Emmanuel Audu Jeremiah. All rights reserved.
