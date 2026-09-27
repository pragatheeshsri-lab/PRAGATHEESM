# Pragatheesh M — Matrix Labs portfolio

A responsive, framework-free portfolio built with semantic HTML, CSS and vanilla JavaScript. The reference ZIP’s cinematic motion, dark editorial styling and custom typography informed the direction; the new visuals and content focus on the engineering projects.

## Preview

Open `index.html` directly, or serve this folder locally:

```powershell
python -m http.server 8000 --directory outputs
```

Then visit `http://localhost:8000`.

## Files

- `index.html` — portfolio structure and metadata
- `styles.css` — responsive layout, visuals, motion and reduced-motion support
- `app.js` — skill selection, project filtering and detail dialogs, hardware explorer, journey interaction, and mobile navigation
- `resume.html` — printable profile and project resume; use **Print / Save as PDF** to create a PDF
- `assets/fonts/` — local Oswald and Anton fonts referenced by the design

## Update the content

Edit project descriptions and status in the `projects` array in `app.js`. Update skill groups, lab entries, component notes and journey stages in the arrays nearby. Add verified contact details in `index.html` and `resume.html` when they are available. Project status labels are intentionally kept explicit so concepts and prototypes are not presented as finished products.
