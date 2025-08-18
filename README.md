# Personal Academic Website

Minimal, clean academic website with four pages: Homepage, Publications, News, and Design.

## Features
- Responsive layout (desktop and mobile)
- Montserrat font, Font Awesome icons
- Card-style publications with images (one per row)
- Compact spacing and shadowed sections

## Structure
```
personal_website/
├── index.html
├── publications.html
├── news.html
├── design.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   ├── muyi.png
│   ├── schools/ (hku.png, bjfu.png)
│   ├── publications/ (paper images)
│   └── design/ (project subfolders)
└── design-projects/ (project detail pages)
```

## Quick start
- Open `index.html` in a browser.
- Edit text directly in HTML files.
- Add images to `images/` (see READMEs under `images/`).

## Editing content
- Homepage: profile info, education logos, contact icons, featured publications, internships and awards.
- Publications: use single-column cards. Optional attributes: `data-status="ongoing"` and hidden `data-date="YYYY.MM.DD"` for sorting.
- News: add items under the lists in `index.html` and `news.html`.
- Design: add projects in `design.html` and a matching detail page in `design-projects/`.

## Images
- Schools: `images/schools/` (PNG recommended, white background inside circular frame)
- Publications: `images/publications/` (file name = exact paper title, PNG/JPG)
- Design: `images/design/<project>/cover.png`, `image1.png` ... `imageN.png`

## Deploy (GitHub Pages)
1) Push this folder to a GitHub repo. 2) In Settings → Pages, select branch `main` and root `/`. 3) Visit `https://<username>.github.io/<repo>/`.

Notes
- No PDF storage is included by default.
- Publication and project images are shown with `object-fit: contain` on a white background.
