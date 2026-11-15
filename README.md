# Exercise #1 — HTML/CSS Personal Page

A responsive, one-page personal profile built with **HTML and CSS** (no JavaScript).
This is the individual version of the original group activity — instead of a team page,
it showcases one person: profile photo, details, and contact information.

## Folder structure

```
exercise-1-html-css-personal-page/
├── index.html          ← page content (edit your details here)
├── styles.css          ← all styling and responsive rules
├── images/
│   └── profile.jpg     ← your profile photo
└── README.md
```

## How to view it

Double-click `index.html`, or right-click → **Open with** your browser.
No installation or build tools needed.

## Make it yours

1. **Name & role** — replace every `Your Name` and `YN` in `index.html`
   (also update the `<title>` and meta description at the top).
2. **Photo** — your photo is already saved as `images/profile.jpg`. To use a different
   picture, replace that file (keep the same name) or update the `src` in `index.html`.
   A square image (for example 800 × 800 px) works best for the circular crop.
3. **About & quick details** — edit the bio, course, school, and location.
4. **Contact** — update your Gmail and GitHub links
   (both the visible text and the `href` values).
5. **Colors (optional)** — change `--accent`, `--teal`, `--bg`, or `--gradient`
   under `:root` at the top of `styles.css` to re-theme the page.

## Submitting on GitHub

```bash
cd exercise-1-html-css-personal-page
git init
git add .
git commit -m "Add Exercise #1 personal page"
git branch -M main
git remote add origin https://github.com/yourusername/exercise-1-html-css-personal-page.git
git push -u origin main
```

Then paste the repository link in the private comment of the assignment and turn in your work.

## Page sections

- Header with name and navigation
- Profile photo and short introduction
- About Me with quick details
- Contact section
- Footer

## Built-in features

- Semantic HTML5 structure (`header`, `nav`, `main`, `section`, `footer`)
- Responsive layout: multi-column on desktop, single column on mobile
- Accessible alt text, labels, skip link, and focus styles
- Subtle animations with reduced-motion support
- No frameworks, no JavaScript — easy to read and submit
