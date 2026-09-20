# Asta's Engineering Portfolio

A personal portfolio website built with plain HTML/CSS to showcase engineering projects — including CAD/manufacturing work, a GCSE Design & Technology NEA project, and the ongoing **Shadow Hunter** quadruped robot build.

## 🔗 Live Structure

The site is a static multi-page site — no build tools or frameworks, just HTML, CSS, and a shared stylesheet.

```
.
├── index.html          # Home page — intro + project cards + 3D model viewer
├── about.html           # About Me page
├── Project1.html        # Project #001 — Pewter Casting Project
├── Project2.html        # Project #002 — Bio-Integrated Composter (GCSE NEA, Grade 8)
├── Main.css             # Shared stylesheet for all pages
└── Assets/              # Images, SVG backgrounds, and graphics
    ├── Asta.png
    ├── BlackGrid.svg
    ├── HexagonBlue.svg
    ├── CompostTumbler.png
    ├── GCSE Certificate.png
    ├── Project1.png
    ├── Project1Heading.svg
    ├── Project2.png
    ├── Project2Heading.svg
    ├── Project3.png
    └── ResearchCone.png
```

## 📄 Pages

| Page | Description |
|---|---|
| **Home** (`index.html`) | Landing page with intro text, three project preview cards, and an embedded Sketchfab 3D model of the Shadow Hunter Leg V3. |
| **About** (`about.html`) | Background on Asta, engineering interests, and current work (IoT, robotics, embedded systems, Shadow Hunter). |
| **Project #001** (`Project1.html`) | Pewter casting jewelry project — design brief, client info, criteria, and an embedded Google Drive booklet. |
| **Project #002** (`Project2.html`) | Bio-Integrated Composter — full GCSE NEA writeup with research cone navigation (Introduction → Research → Theme exploration → Product design), an embedded reference image, and the original project booklet. |
| **Project #003** | Bamboo lunchbox business plan — linked from the home page directly to an external Google Drive doc (no dedicated page yet). |

## 🎨 Design Notes

- **Font:** [Space Mono](https://fonts.google.com/specimen/Space+Mono) (Google Fonts), loaded via `<link>` in each page's `<head>`.
- **Layout:** Section-based blocks (`.Main`, `.MainProject`, `.MainProject2`, `.Project1`, `.Project2`, `.Project3`, `.Footer`) styled independently in `Main.css`.
- **Navigation:** Anchor links with `scroll-margin-top` for smooth in-page jumping (used heavily in `Project2.html`'s research-cone navigation).
- **Backgrounds:** Repeating SVG textures (`BlackGrid.svg`, heading-specific SVGs) applied via `background-image`.
- **Embeds:** Google Drive file previews (`<iframe>`) for original project booklets, and a Sketchfab embed for the 3D leg model.

## 🛠️ Running Locally

No dependencies or build step required.

1. Download/clone all files, keeping `Assets/` in the same folder as the HTML files.
2. Open `index.html` directly in a browser, **or** serve the folder locally for correct relative asset paths:
   ```bash
   npx serve .
   # or
   python3 -m http.server 8000
   ```
3. Navigate to `http://localhost:8000` (or the port shown).

## ✅ Known Issues / To Do

- `Project1.html` and `Project2.html` have some empty `<h1>`/`<h2>` placeholder tags left over from editing — safe to clean up.
- `img #Compost { height: 0px; }` in `Main.css` currently hides the compost tumbler reference image on Project #002 — likely unintentional and worth revisiting.
- Project #003 (Bamboo lunchbox) doesn't yet have its own page — currently just links out to Google Drive.
- Minor copy typos throughout (e.g. "Portofolio," "trough," "athmosphere," "government") could use a proofread pass.
- `about.html` has an empty leftover `.Project1Body` / `.Footer` block at the bottom of the file.

## 📬 Contact

Links to email, Instagram, GitHub, and Stardance are in the footer of every page.
