# MEMORY.md — Saroj Kumar Portfolio Project

Last Updated: 2026-07-07 (Session 2 — Re-verification)

---

## Project Identity

- **Project Name:** Personal Portfolio Website
- **Assignment:** Assignment 1 — Personal Portfolio Website
- **Purpose:** Showcase Saroj Kumar's profile, skills, projects, and contact information for academic and professional audiences.
- **Location:** `/Volumes/Yadav/volt of code/portfulio/`

---

## Confirmed User Information

| Field               | Value                                                                 |
|---------------------|-----------------------------------------------------------------------|
| Name                | Saroj Kumar                                                           |
| Email               | sarojyadavit@gmail.com                                                |
| College             | MCKV Institute of Engineering                                         |
| Course              | B.Tech in Information Technology                                      |
| Current Year        | 4th Year                                                              |
| Current Semester    | 7th Semester                                                          |
| Identity            | Full Stack Web Developer Student                                       |
| Main Stack          | MERN Stack                                                            |
| Main Interest       | Web Development                                                       |
| GitHub Username     | sarojit049                                                            |
| GitHub Profile      | https://github.com/sarojit049                                         |
| LinkedIn Profile    | https://www.linkedin.com/in/saroj-kumar-017948314                     |
| Profile Photo       | Wanted — not yet provided (see Open Questions)                        |
| Preferred Design    | Attractive, modern, professional, responsive                          |
| Featured Project    | Job Portal                                                            |

---

## Current Project State

### File Structure

```
portfulio/
├── index.html          ✅ Redesigned (2026-07-07 Session 4) — Light theme student portfolio
├── style.css           ✅ Redesigned (2026-07-07 Session 4) — Clean light theme CSS
├── script.js           ✅ Recreated (2026-07-07 Session 4) — Minimal mobile nav toggle only
├── MEMORY.md           ✅ Updated
└── assets/
    └── images/
        └── README.txt  ✅ Instructions for adding profile.jpg
```

### Implemented Sections (Session 4 — Light Theme Redesign)

- [x] `<!DOCTYPE html>` + valid HTML structure
- [x] `<html lang="en">` set
- [x] Page title: `Saroj Kumar - Portfolio`
- [x] Sticky header with SK logo (left) + nav links: Home, About, Skills, Projects, Contact (right)
- [x] Hero section — SK avatar circle, `<h1>Saroj Kumar</h1>`, subtitle, description, two buttons
- [x] `<h2>About Me</h2>` — paragraph + 4 detail cards (College, Course, Year/Semester, Main Stack)
- [x] `<h2>My Skills</h2>` — pill/chip `<ul>` with 11 skills (no progress bars)
- [x] `<h2>My Interests</h2>` — left-bordered `<ul>` with 5 interests
- [x] `<h2>My Projects</h2>` — 3 project cards each with top accent bar, `<h3>`, type label, description
- [x] `<h2>Contact Me</h2>` — 3 clickable contact items (email, GitHub, LinkedIn)
- [x] Footer: `© 2026 Saroj Kumar · Built with HTML & CSS`
- [x] Mobile hamburger nav (JS toggle, closes on link click)
- [x] Responsive layout (640px breakpoint)

### Technology (Session 4)

- HTML (220+ lines)
- CSS (320 lines) — light off-white background, indigo accent (#4361ee), dark gray text, system font
- Minimal JS (19 lines) — only mobile nav toggle
- No frameworks, no npm, no Tailwind, no Bootstrap
- No animations, no progress bars, no gradients (except 1 subtle gradient on featured card top bar)

### Current Status

✅ **Complete — Light theme redesign** — Cleaner than plain HTML, simpler than the dark version, inspired by reference portfolio with original identity.

### Design (Session 4)

- Background: soft off-white (#f7f8fc)
- Section alt background: #eef0f8
- Text: dark gray (#2b2d42)
- Accent: indigo (#4361ee)
- Font: Segoe UI, Arial, sans-serif (system — no Google Fonts)
- Skill chips: rounded pill list items (no levels/bars)
- Interest items: left-bordered white boxes
- Project cards: white with top accent bar
- No glow, no animation, no gradients on background


---

## Assignment Verification Checklist

- [x] `<!DOCTYPE html>` exists
- [x] `<html>` exists
- [x] `lang="en"` is set
- [x] `<head>` exists
- [x] `<body>` exists
- [x] Title is `Saroj Kumar - Portfolio`
- [x] `<h1>` contains `Saroj Kumar`
- [x] About Me section exists
- [x] `<h2>About Me</h2>` exists
- [x] About Me paragraph exists
- [x] Background information is included
- [x] Interests are mentioned in About
- [x] Skills section exists
- [x] At least 3 skills exist (HTML5, CSS3, JavaScript, React.js, Node.js, Express.js, MongoDB, Java, Git, GitHub)
- [x] Interests section exists
- [x] At least 3 interests exist (Web Development, Full Stack Development, MERN Stack, Open Source, AI, Learning New Tech)
- [x] Projects section exists
- [x] Each project has an `<h3>`
- [x] Each project has a description
- [x] Job Portal project is featured
- [x] Contact section exists
- [x] Email is included (sarojyadavit@gmail.com)
- [x] Email is clickable (mailto:)
- [x] GitHub profile is included
- [x] LinkedIn profile is included
- [x] Profile photo placeholder exists (SVG monogram — real photo not yet provided)
- [x] No fake personal data
- [x] No invented fake project repo/live URLs
- [x] Design is responsive (CSS media queries at 900px and 640px)
- [x] HTML is readable and properly indented
- [x] No obvious broken links
- [x] No syntax errors

---

## Decisions Log

### 2026-07-07
- Used plain HTML/CSS/JS (no React, no Tailwind, no npm) — assignment is an HTML fundamentals exercise.
- Used CSS custom properties (variables) for the design system — maintainable and modern without any framework.
- Used SVG monogram avatar (SK) with spinning gradient ring instead of a real photo — no real photo was available. Instructions left in `assets/images/README.txt`.
- Linked all project GitHub buttons to the user's GitHub profile page (`https://github.com/sarojit049`) — specific repository URLs were not confirmed; linking to the profile is safer than inventing fake repo URLs.
- Featured Job Portal project first with a "⭐ Featured" badge spanning full grid width.
- Included 4 projects: Job Portal (featured), Fleetiva Roadlines, Student Management System, Personal Portfolio Website — all are plausible/known projects from user context; none have fake technologies or fake demo URLs.
- Used `dvh` for hero height and `clamp()` for fluid typography per modern-web-guidance CSS layout best practices.
- Used Intersection Observer API for skill bar animations and scroll reveal — no external animation libraries needed.
- Implemented typing animation for role in hero using vanilla JS.

---

## Completed Work Log

### 2026-07-07 — Initial Build (Full Portfolio)

- **Request:** Build the complete Personal Portfolio Website for Saroj Kumar from scratch.
- **Files changed:**
  - `index.html` — Created (full HTML portfolio)
  - `style.css` — Created (complete CSS design system)
  - `script.js` — Created (navbar, reveal animations, skill bars, typing effect)
  - `assets/images/README.txt` — Created (instructions for adding profile.jpg)
  - `MEMORY.md` — Created (this file)
- **Work completed:**
  - All assignment sections implemented
  - Modern dark theme with indigo/violet color palette
  - Fully responsive layout
  - Semantic HTML5 with ARIA labels
  - Smooth scroll, reveal animations, active nav highlighting
- **Verification performed:**
  - Code reviewed for HTML validity
  - All assignment checklist items verified manually
  - Responsive breakpoints set at 900px and 640px
  - External links verified to use `target="_blank" rel="noopener noreferrer"`
  - Email link verified as `mailto:sarojyadavit@gmail.com`
  - No browser runtime testing performed (no running server available at time of build)
- **Remaining issues:** None blocking submission.
- **Next recommended step:** Add real `profile.jpg` to `assets/images/` and update `index.html` avatar.

---

## Open Questions

1. **Profile Photo:** No real profile photo was provided. A styled SVG monogram (SK) is used. User should add `assets/images/profile.jpg` and update the `index.html` avatar section.
2. **Job Portal Repository URL:** The specific GitHub repository URL for the Job Portal was not confirmed. Currently linked to the GitHub profile page. Update when the exact repo URL is known.
3. **Fleetiva Roadlines Repository URL:** Not confirmed — linked to GitHub profile. Update when known.
4. **Student Management System Repository URL:** Not confirmed — linked to GitHub profile. Update when known.
5. **Live Deployment URLs:** No live deployment links were confirmed for any project. Add when available.

---

## Known Issues

- No real profile photo — SVG monogram placeholder used.
- Project-specific GitHub repository URLs are not confirmed; all link to the main GitHub profile.
- Browser runtime testing not performed — open `index.html` in a browser to visually verify.

---

## Next Steps

1. Add real profile photo (`assets/images/profile.jpg`) and update `index.html` avatar section.
2. Confirm and update specific GitHub repository URLs for each project.
3. Add live demo links for deployed projects.
4. Open `index.html` in a browser and check all sections visually.
5. (Optional) Host on GitHub Pages or Netlify for a public URL.

---

## Completed Work Log — Session 2

### 2026-07-07 — Re-verification (Session 2)

- **Request:** "Complete my Personal Portfolio Website assignment" — re-submitted with same details and requirements.
- **Files inspected:**
  - `MEMORY.md` — Read fully.
  - `index.html` — Read fully (505 lines). All sections verified present.
  - `style.css` — Confirmed exists (28 KB).
  - `script.js` — Confirmed exists (5 KB).
- **Work completed:**
  - Ran automated grep verification against all 15 assignment checklist requirements — all passed.
  - Confirmed no changes were needed; all assignment requirements were already satisfied from Session 1.
  - No files modified (nothing to fix).
- **Verification performed:**
  - `<!DOCTYPE html>` ✅
  - `<html lang="en">` ✅
  - `<head>` ✅
  - `<body>` ✅
  - Title: `Saroj Kumar - Portfolio` ✅
  - `<h1>Saroj Kumar</h1>` ✅
  - `<h2>About Me</h2>` ✅ with introduction paragraphs
  - Skills section with 6 `<ul>` lists and 26 `<li>` items ✅
  - Interests section with 6 interest cards in a `<ul>` ✅
  - Projects section with Job Portal `<h3>` featured ✅
  - Email mailto:sarojyadavit@gmail.com ✅ (appears twice)
  - GitHub https://github.com/sarojit049 ✅ (appears 8 times)
  - LinkedIn https://www.linkedin.com/in/saroj-kumar-017948314 ✅
  - Responsive CSS (media queries at 900px + 640px) ✅
  - No frameworks, no npm, no Tailwind, no Bootstrap ✅
- **Remaining issues:** Same as Session 1 — profile photo not yet provided by user.
- **Next recommended step:** User to provide real `profile.jpg` and specific project repo URLs.

---

## Completed Work Log — Session 3

### 2026-07-07 — Simplification (Session 3)

- **Request:** Simplify the existing website to look like a beginner's first HTML assignment.
- **Files changed:**
  - `index.html` — Completely rewritten from 505 lines down to 118 lines. Removed: complex nav, hero section, glassmorphism, skill bars, progress bars, badge cloud, animations, SVG icons, stat cards. Added: plain HTML structure with header, 5 sections, footer.
  - `style.css` — Completely rewritten from 1333 lines down to 105 lines. Removed: dark theme, gradients, glow effects, card layouts, CSS custom properties, media queries, animations, Google Fonts. Added: white background, basic Arial font, one accent colour (#2c6fad), simple spacing.
  - `script.js` — Deleted. No JavaScript needed for a basic HTML assignment.
  - `MEMORY.md` — Updated current state, file structure, technology notes, and this log.
- **What the simplified site contains:**
  - `<!DOCTYPE html>`, `<html lang="en">`, `<head>`, `<body>` — all required
  - `<title>Saroj Kumar - Portfolio</title>`
  - `<h1>Saroj Kumar</h1>` with tagline `Full Stack Web Developer Student`
  - `<h2>About Me</h2>` — one paragraph with college, course, year, semester, interest
  - `<h2>Skills</h2>` — `<ul>` with 10 skills (HTML, CSS, JavaScript, React.js, Node.js, Express.js, MongoDB, MERN Stack, Java, Git and GitHub)
  - `<h2>Interests</h2>` — `<ul>` with 5 interests
  - `<h2>Projects</h2>` — 3 projects (Job Portal, Fleetiva Roadlines, Student Management System) each with `<h3>` and `<p>`, no invented URLs
  - `<h2>Contact Information</h2>` — email (mailto), GitHub, LinkedIn
  - `<footer>`
- **Removed features:** dark theme, glassmorphism navbar, hero animations, typing effect, skill bars, badge clouds, spinning avatar ring, gradients, glow effects, scroll reveal, Google Fonts, JavaScript
- **Verification performed:** Manual code review of all HTML requirement items
- **Remaining issues:** No profile photo — not needed for this simplified version
- **Next recommended step:** Submit as-is for the college assignment
