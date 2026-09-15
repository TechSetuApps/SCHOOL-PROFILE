# SCHOOL-PROFILE

**+2 High School Pindaruch — A student-built school profile page.**

> This is an **unofficial student project**, not the official website of +2 High School Pindaruch. The school, the Bihar Education Department and the Government of Bihar are not responsible for any content here. See the in-page Disclaimer (link in the page footer) for full details.

---

## What this is

A single-page school-profile website built as a student academic submission. The page presents verified public information about +2 High School Pindaruch (a heritage rural school in Darbhanga, Bihar, established 1945) in a clean, modern, accessible, fully-responsive layout.

The page is **a single, self-contained static HTML file named `index.html`** — no external image files, no external JavaScript or CSS libraries, no third-party trackers, no backend. All three photographs are embedded directly in the file as base64 data URIs. The only external resource loaded is Google Fonts (OFL-licensed).

| Field | Value |
|---|---|
| Project type | Static single-page HTML school profile (self-contained) |
| Built by | Student (school-project author) |
| Hosting | GitHub Pages (static) |
| Repo name | `SCHOOL-PROFILE` |
| Single file | `index.html` (with all images embedded as base64) |
| License | MIT (source code) — see in-page License section |
| Last updated | 14 September 2026 |

---

## Live URL

```
https://techsetuapps.github.io/SCHOOL-PROFILE/
```

---

## Repository structure

```
SCHOOL-PROFILE/
├── index.html              # The complete self-contained school profile page
└── README.md                      # This file (developer documentation)
```

That's it — one HTML file (`index.html`) and one README (`README.md`). No `assets/` folder, no `node_modules/`, no build configuration, no `package.json`. All three photographs are embedded inside `index.html` as base64 data URIs.

---

## Verified information summary

All school information shown on the page has been compiled from public sources. Below is a summary of the key verified facts (see the in-page Credits section for full source attributions).

### School identity (UDISE+ 2025-26)

- **School name** — +2 High School Pindaruch, Dharbhanga
- **U-DISE code** — 10130209009
- **Status** — Operational
- **Address** — Pindaruch, Keoti Ranway, Darbhanga, Bihar — 847306
- **Block** — Keoti (LGD Block: Keotirunway)
- **District** — Darbhanga
- **State** — Bihar, India
- **Location** — Rural
- **School category** — Upper Primary + Higher Secondary (Class 6 to 12)
- **School type** — Co-educational
- **Medium of instruction** — Hindi (primary) + English (secondary)
- **Affiliation board** — State Board (Sec. and HSec.)
- **Management** — Department of Education (Government of Bihar)
- **Year of establishment** — 1945
- **Cluster** — MS Madhopatti
- **Building blocks** — 3 (all pucca / permanent)
- **Classrooms** — 12 (7 good, 2 minor repair, 3 major repair)

### Students (academic year 2025-26)

| Class | Boys | Girls | Total |
|---|---|---|---|
| Class 6 | 49 | 60 | 109 |
| Class 7 | 45 | 29 | 74 |
| Class 8 | 10 | 33 | 43 |
| Class 9 | 113 | 142 | 255 |
| Class 10 | 122 | 122 | 244 |
| Class 11 | 85 | 82 | 167 |
| Class 12 | 142 | 95 | 237 |
| **Total** | **566** | **563** | **1129** |

### Teachers (academic year 2025-26)

- **Total teachers** — 41 (28 male, 13 female, all regular appointment)
- **Postgraduate** — 38 teachers
- **B.Ed. or equivalent** — 37 teachers
- **Trained in computer** — 3 teachers
- **Aged above 55** — 7 teachers
- **Service training received** — 40 teachers

### Infrastructure (per UDISE+ 2025-26)

- Toilets — 2 boys + 2 girls (functional)
- Library — available
- Electric power — available
- Playground — available
- Drinking water — available and functional
- Medical check-ups — available
- Internet — available and functional
- ICT Lab — available (20 desktops, 2 tablets, 1 printer)
- Ramp and handrails — available (accessibility)
- Boundary wall — partial
- Handwash near toilet — available
- Handwash facility for meal — available
- Furniture — available

### Contact (verified from public sources)

| Field | Value | Source |
|---|---|---|
| Phone | +91 96311 71889 | School's public Facebook page |
| Email | Not publicly listed | — |
| Facebook | facebook.com/p/High-school-pindaruch-100025685575355 | — |
| UDISE+ report card | kys.udiseplus.gov.in/#/reportcard/2425049/13 | — |
| School hours | Approx. 9 AM — 4 PM, Monday to Saturday | Typical Bihar govt school (verify with office) |

### Government schemes active at the school

- **PM SHRI** (Pradhan Mantri Schools for Rising India) — school in 2024-25 list
- **Unnayan Bihar** (smart-class digital content) — launched 5 Sep 2019
- **Chetna Satra / Prarthna Sabha** (morning assembly) — mandatory since Aug 2018
- **Surakshit Shanivar** (Bagless Safe Saturday) — Mukhya Mantri Vidyalaya Suraksha Karyakram, 2025
- **Tarang** (art and sports festival) — annual inter-school
- **ICT / TCIL** instructor empanelled

### Village context (Census 2011)

- Village name — Pindaruch
- Census village code — 226883
- Block — Keotirunway (also referred to as Keoti in UDISE+ records)
- District — Darbhanga
- Pincode — 847306
- Total population — 4586
- Total households — 900
- Total literacy rate — 49.3% (Male: 68.34%, Female: 20.3%)
- Female population — 48.5% (2222)
- Child (0-6) population — 764
- Distance from Darbhanga HQ — 14 km north
- River — Kamla (Bagmati) flows through the village

---

## Tech stack

| Tool | Purpose | License |
|---|---|---|
| HTML5 | Page structure | — |
| CSS3 (custom properties, grid, flexbox) | Styling | — |
| Vanilla JavaScript (IntersectionObserver) | Reveal animations, mobile menu, smooth scroll | — |
| Google Fonts: Fraunces, IBM Plex Sans, IBM Plex Mono | Typography | SIL OFL 1.1 |
| Hand-coded SVG icons | All UI icons | CC0 / own work |
| Base64 data URIs | Embed images directly in HTML | No external requests |

**Not used**: jQuery, Bootstrap, Tailwind, React, Vue, Angular, Svelte, Alpine, HTMX, no external JS library, no analytics, no tracking pixels, no cookies, no CDN scripts.

---

## How to run locally

This is a pure static HTML project — no build step required.

1. Clone the repository (it contains two files: `index.html` and `README.md`).
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge).

That's it. The Google Fonts will load from the internet. If you're offline, the page falls back to system fonts gracefully. The three images are embedded as base64 data URIs, so they will always load — they don't depend on any external file or network request.

---

## In-page features

The `index.html` file contains the following sections in reading order:

1. **Sticky header** with brand mark, desktop navigation, "LEGAL INFO" button and "REACH OUT" button, and a hamburger menu for mobile.
2. **Hero** with background image and school name overlay.
3. **Quick-facts strip** (U-DISE code, established, students, teachers).
4. **About** the school — text and a representative photograph.
5. **Higher-secondary streams** — Science, Arts, Commerce.
6. **Academic stages** — Upper Primary, Secondary, Higher Secondary, Co-curricular.
7. **Faculty and staff** — stat blocks and faculty-areas list (no individual names).
8. **Morning assembly (Chetna Satra)** — image and 4-step routine.
9. **Campus and infrastructure** — 12 verified facility cards.
10. **Government schemes** — 6 scheme cards with verified info.
11. **Gallery** — 3 representative stock photographs with captions.
12. **Village context** — 4 verified Census 2011 stat cards.
13. **Contact** — full address, phone, email placeholder, UDISE+ link.
14. **Legal Information intro banner** — dark band announcing the legal section.
15. **Privacy Policy** — 9 sections of inline text.
16. **Terms of Use** — 11 sections of inline text.
17. **Disclaimer** — 10 sections of inline text with a callout box.
18. **Credits and Attributions** — 9 sections of inline text with source tables.
19. **MIT License** — full MIT License text.
20. **Footer** with brand, three navigation columns (Explore / Campus / Legal), disclaimer block, and last-updated date.

### Animations (subtle, smooth)

- Hero background: slow 20-second zoom-out on page load.
- Section reveal: gentle fade-in + 20px slide-up via IntersectionObserver.
- Card hover: subtle lift + shadow.
- Image hover: slow zoom (800ms).
- Button press: tactile feedback (translateY 1px).
- Mobile menu: slide-down overlay with body scroll lock.
- Smooth scroll: in-page links scroll with sticky-header offset.
- Active nav state: scroll-spy updates current section.
- Legal section "Back to top" buttons: scroll back to page top.
- All animations respect `prefers-reduced-motion`.

---

## Important notes on the photographs

The three photographs embedded as base64 data URIs in `index.html` are **stock images sourced from Google search**, used here for representative illustration only. They are **not** actual photographs of the Pindaruch campus. Where faces of people appear, they are intentionally blurred beyond recognition.

Before publishing this page on a public domain, **I should replace these stock images with my own campus photographs taken with the school's permission.** The stock photographs are not licensed for commercial reuse.

---

## License

The source code (HTML, CSS, JavaScript, SVG icons) is released under the **MIT License** — see the in-page License section for the full text.

- You may use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the source code.
- You may adapt the code for your own school-project pages.
- The photographs embedded as base64 data URIs are NOT licensed for commercial reuse — replace them with your own.
- Public facts about the school are not copyrightable; no copyright is claimed on facts.
- Names of government schemes and institutions remain the property of their respective owners; reference for identification only.

---

## Privacy

This page does **not** collect any personal data from visitors. No cookies, no analytics, no tracking scripts, no form submissions. See the in-page Privacy Policy for full details.

---

## Contributing / corrections

If you notice any inaccuracy on this page — particularly relating to the school's address, phone, operational hours, or any publicly identifiable fact — please open an issue on this GitHub repository. Corrections will be made promptly after verification.

---

## Disclaimer (short version)

This is a student-built project, not the official website of +2 High School Pindaruch. The school, the Bihar Education Department and the Government of Bihar are not responsible for any content here. All information is compiled from public sources and may be outdated. Always verify current operational details directly with the school office before relying on them. See the full in-page Disclaimer (link in the page footer).

---

*This README and the project page itself are educational artefacts released under the MIT License. They do not represent any official position of the school, the Bihar Education Department, or the Government of Bihar.*

