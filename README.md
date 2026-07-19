 Light, Held Still — Photography Portfolio

**Author:** Asha Wanjiru *(replace with your own name)*

## Description

A single-page photography portfolio built with plain **HTML and CSS**. The site
introduces the photographer, showcases a "contact sheet" of favorite photographs,
and includes a contact form for inquiries. The visual language borrows from analog
film photography — sprocket-hole strips, negative frame numbers, and a darkroom
color palette — to match the subject matter of the site itself.

### Features

- Semantic HTML (`header`, `nav`, `main`, `section`, `footer`, ordered/unordered
  lists, `strong`, `em`)
- A fully custom stylesheet (`styles.css`) — no CSS framework
- A biography section with a portrait photo
- A gallery of 8 favorite photographs, numbered like film negatives
- A working contact form with labeled, validated fields
- Responsive layout down to mobile

## Project structure

```
photo-site/
├── index.html
├── styles.css
└── README.md
```

## Setup / running locally

No build tools or dependencies are required.

1. Clone this repository:
   ```
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open `index.html` directly in your browser, **or** serve it locally:
   ```
   cd <your-repo-name>
   python3 -m http.server 8000
   ```
   then visit `http://localhost:8000`.

## Deploying to GitHub Pages

1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch (or a `gh-pages` branch) and
   `/ (root)` folder.
4. Save. GitHub will publish the site at:
   ```
   https://<your-username>.github.io/<your-repo-name>/
   ```
5. Replace the placeholder link below with that URL.

## Live site

🔗 `https://<your-username>.github.io/<your-repo-name>/`

## Design

The design was planned before development began: a dark, film-developing-room
palette (near-black background, warm amber accent, cream "photo paper" highlights)
paired with a serif display face for personality and a monospace face for
film-strip-style labels. The gallery grid mimics a physical contact sheet, with
each photo numbered as a negative frame (N° 01–08) and full color revealed only
on hover, like a print lifting out of the developer tray.

## License

This project is released under the [MIT License](https://opensource.org/licenses/MIT).
You are free to use, copy, modify, and distribute it with attribution.

---

*Replace the sample name, photos, and copy in `index.html` with your own before
submitting — this template is a starting point, not the final deliverable.*
