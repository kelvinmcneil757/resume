# Kelvin McNeil Jr. — Resume Website

This repository contains the static files for Kelvin McNeil Jr.'s resume website.

## Overview
- Single-page site built with Tailwind via CDN
- Highlights, About, Work Experience, Skills, Contact
- Prominent Download Resume button linking to `Kelvin_McNeil_Jr_Resume.pdf`
- No contact form (forms were removed)

## Quick start (local preview)
```bash
# From the repo root
python3 -m http.server 8000
# Visit http://localhost:8000
```

## Updating your resume PDF
1. Replace the file `Kelvin_McNeil_Jr_Resume.pdf` with your latest PDF (keep the same filename).
2. Refresh your browser; the Download button will serve the new file.

## Editing content
- Main page content lives in `index.html`.
- Supplemental copy/reference lives in `resume.md` (optional helper notes).
- Images: `IMG_0025.jpeg`, `durham.jpg`.

## Deploying with GitHub Pages
1. Push changes to `main`.
2. In GitHub, go to: Settings → Pages.
3. Set Source to `Deploy from a branch`, select `main` and `/ (root)`.
4. Save. Your site will be available at the Pages URL shown.

## Repo structure
```
├─ index.html                  # Main site
├─ Kelvin_McNeil_Jr_Resume.pdf # Downloadable resume
├─ resume.md                   # Supporting notes/content
├─ IMG_0025.jpeg               # Profile image
└─ durham.jpg                  # Contact section image
```
